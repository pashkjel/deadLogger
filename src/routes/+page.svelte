<script>
    function getValue(test) {
      // Get the input element
      let input = document.getElementById("myInput");
    
      // Get the value of the input
      let value = input.value;
    
      // Display the value
      console.log(value)
      // or you can use alert(value) to display it in an alert box
    }
    </script>
<input type="text" id="myInput">
<button onclick = "getValue()">Get Value</btton>