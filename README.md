<!DOCTYPE html>
<html>
<head>
<title>Magma Message</title>
<style>
  body {
    background-image: url('https://cdn.pixabay.com/photo/2017/12/18/18/36/lava-3026884_960_720.jpg'); /* Magma background image */
    background-size: cover;
    color: white; /* Text color */
    font-family: Arial, sans-serif;
    text-align: center;
    padding-top: 100px; /* Adjust for spacing */
  }
  #message {
    font-size: 3em;
    margin-bottom: 20px;
  }
  input[type="text"] {
    padding: 10px;
    font-size: 1em;
  }
</style>
</head>
<body>

<h1 id="message">Your Magma Message Here</h1>
<input type="text" id="inputMessage" placeholder="I Love You both

pen_spark




tune

share


more_vert
">

<script>
  const input = document.getElementById('inputMessage');
  const message = document.getElementById('message');

  input.addEventListener('input', function() {
    message.textContent = this.value;
  });
</script>

</body>
</html>
