<!DOCTYPE html>
<html>
<head>
  <title>Please Participate in Our Survey!</title>
  <link href="https://fonts.googleapis.com/css?family=Oswald:300,700|Varela+Round" rel="stylesheet">
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <header>
    <ul>
      <li><a href="#q1">Question 1</a></li>
      <li><a href="#q2">Question 2</a></li>
      <li><a href="#q3">Question 3</a></li>
      <li><a href="#q4">Question 4</a></li>
      <li><a href="#q5">Question 5</a></li>
    </ul>
  </header>
  <div class="welcome">
    <h1><strong>Welcome</strong> to our survey!</h1>
    <p>We're looking forward to getting your answers so we can make sure our products and services are the best they can be!</p>
  </div>
  <div class="question" id="q1">
    <h4>Question 1</h4>
    <h2>I like participating in physical activity such as running, swimming, or biking.</h2>
    <label for="answer">
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Agree</h3>
     </div>
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Disagree</h3>
     </div>
     <div class="answer">
       <input type="text" name="answer" id="answer">
       <h3>Other:</h3>
     </div>
     </label>
    </div>
  <div class="question" id="q2">
    <h4>Question 2</h4>
    <h2>I try to keep up to date with the latest fashion in active wear.</h2>
    <label for="answer">
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Agree</h3>
     </div>
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Disagree</h3>
     </div>
     <div class="answer">
       <input type="text" name="answer" id="answer">
       <h3>Other:</h3>
     </div>
     </label>
    </div>
  <div class="question" id="q3">
    <h4>Question 3</h4>
    <h2>I purchase clothing online regularly.</h2>
    <label for="answer">
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Agree</h3>
     </div>
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Disagree</h3>
     </div>
     <div class="answer">
       <input type="text" name="answer" id="answer">
       <h3>Other:</h3>
     </div>
     </label>
    </div>
  <div class="question" id="q4">
    <h4>Question 4</h4>
    <h2>I try to buy goods that are designed and/or manufactured in my home country.</h2>
    <label for="answer">
     <div class="answer">
      <input type="radio" name="answer" id="answer" value="579">
       <h3>Agree</h3>
     </div>
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Disagree</h3>
     </div>
     <div class="answer">
       <input type="text" name="answer" id="answer">
       <h3>Other:</h3>
     </div>
     </label>
    </div>
  <div class="question" id="q5">
    <h4>Question 5</h4>
    <h2>I look to famous athletes when trying to choose what to wear when training.</h2>
    <label for="answer">
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Agree</h3>
     </div>
     <div class="answer">
      <input type="radio" name="answer" id="answer">
       <h3>Disagree</h3>
     </div>
     <div class="answer">
       <input type="text" name="answer" id="answer">
       <h3>Other:</h3>
     </div>
     </label>
    </div>
</body>
</html>
body {
  background-color: #f5f5f5;
  margin: 0 auto;
}

header {
  background-color: #466995;
  border-bottom: 1px solid #466995;
  position: fixed;
  width: 100%;
  z-index: 10;
}

ul {
  margin: 30px auto;
  padding: 0 20px;
  text-align: center;
}

li {
  color: #FFF;
  font-family: 'Oswald', sans-serif;
  font-size: 16px;
  font-weight: 300;
  text-transform: uppercase;
  display: inline-block;
  width: 80px;
}

li:hover {
  color: #DBE9EE;
}

h1 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 32px;
  font-weight: 300;
  text-transform: uppercase;
}

h2 {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 26px;
  font-weight: 100;
  margin: 0 auto 20px auto;
}

h3 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  text-align: center;
  font-weight: 700;
  text-transform: uppercase;
  padding: 30px;
}

h4 {
  color: #466995;
  font-family: 'Oswald', sans-serif;
  font-size: 18px;
  font-weight: 300;
  letter-spacing: 2px;
  text-align: center;
  text-transform: uppercase
}

p {
  color: #333;
  font-family: 'Varela Round', sans-serif;
  font-size: 18px;
}

footer {
  background-color: #DBE9EE;
  text-align: center;
  height: 100px;

}

.welcome {
  background-color: #DBE9EE;
  box-sizing: border-box;
  padding: 40px;
  text-align: center;
  width: 100%;
  position: relative;
  top: 50px;
}

.question {
  text-align: center;
  position: static;
  top: 40px;

}

.answer {
  border: 1px solid #466995;
  margin: 20px;
}

.answer:hover {
  background: #C0D6DF;
  color: #FFF;
}
