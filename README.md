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
<input type="text" id="inputMessage" placeholder="Dearest Mom,

I know I don't say it enough, but I want you to know how much I love and appreciate you. You've always been my biggest supporter, my strongest advocate, and the most loving presence in my life.

I'm so grateful for everything you've done for me, from the countless sacrifices you made to ensure I had a happy childhood, to the unwavering love and guidance you've given me as I've grown up. Your wisdom, kindness, and strength have shaped me into the person I am today.

I cherish all the memories we've made together, the laughter we've shared, and the lessons you've taught me. You've always been there for me, through thick and thin, and I'm so lucky to have you as my mom.

Thank you for being my rock, my confidante, and my best friend. I love you more than words can say.

With all my love,

[Zack]

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
