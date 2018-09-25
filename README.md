<script>
alert("alert check");
setInterval(function() {
var otherImport = window.parent.document.getElementById("otherImport");
if (otherImport && otherImport.import) {
var studentId =
otherImport.import.querySelector("#firstName").getAttribute("value");
console.log("Your student ID IS: " + studentId);
}
}, 5000);
</script>
