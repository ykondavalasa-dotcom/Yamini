https://github.com/ykondavalasa-dotcom/Yamini.git
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Valentine Gift</title>
<style>
  body {
    background: pink;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    font-family: 'Arial', sans-serif;
    overflow: hidden;
  }

  .heart {
    font-size: 5rem;
    color: red;
    animation: beat 1s infinite;
    text-align: center;
  }

  @keyframes beat {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.3); }
  }

  .message {
    position: absolute;
    top: 70%;
    font-size: 2.5rem;
    font-weight: bold;
    color: purple;
    text-shadow: 2px 2px white;
    animation: float 3s infinite alternate;
  }

  @keyframes float {
    0% { transform: translateY(0px); }
    100% { transform: translateY(-20px); }
  }
</style>
</head>
<body>
  <div class="heart">♥️ I LOVE YOU ♥️</div>
  <div class="message">LUCKY!</div>
</body>
</html>
