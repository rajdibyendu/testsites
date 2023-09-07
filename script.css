function validateDate() {
  var inputDate = new Date(document.getElementById("calendar").value);
  var currentDate = new Date();

  // Set the time of the current date to midnight for accurate comparison
  currentDate.setHours(0, 0, 0, 0);

  if (inputDate < currentDate) {
    alert("Past dates are not allowed.");
    // Clear the input field
    document.getElementById("calendar").value = "";
  }
}
