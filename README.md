<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Tracke - DIO</title>
  <style>
  /* estilos da página */
  body {
    font-family: 'Source Sans Pro', sans-serif;
    line-height: 1.5;
    color: #444;
  }

  .banner {
    background-color: #000;
    color: #fff;
    padding: 20px;
    text-align: center;
  }

  .banner .content {
    max-width: 800px;
    margin: 0 auto;
  }

  .banner .logo {
    margin-bottom: 20px;
  }

  .banner h1 {
    margin-bottom: 10px;
    font-size: 2.25em;
  }

  .banner p {
    margin-bottom: 20px;
  }

  .banner button {
    padding: 10px 20px;
    background-color: #f05d5e;
    border: none;
    color: #fff;
    font-size: 1.1em;
    font-weight: 600;
    cursor: pointer;
  }

  #course-content {
    padding: 20px 0;
  }

  #course-content h2 {
    font-size: 1.75em;
    margin-bottom: 10px;
  }

  #course-content .module {
    display: inline-block;
    margin-right: 20px;
  }

  #transform-world {
    background-color: #f05d5e;
    color: #fff;
    padding: 10px 0;
    text-align: center;
  }

  #transform-world p {
    font-size: 1.5em;
    font-weight: 600;
  }

  #professional-challenges {
    padding: 20px 0;
    text-align: center;
  }

  #professional-challenges h2 {
    font-size: 1.75em;
    margin-bottom: 10px;
  }

  #professional-challenges p {
    font-size: 1.2em;
    margin-top: 20px;
  }

  #professional-challenges img {
    max-width: 500px;
    margin-bottom: 20px;
  }

  footer {
    background-color: #222;
    color: #fff;
    padding: 20px 0;
    text-align: center;
  }

  footer .dio-logo {
    margin-bottom: 20px;
  }

  footer a {
    color: #f05d5e;
  }
  </style>
</head>
<body>
  <header class="banner">
    <div class="content">
      <div class="logo">
        <img src="assets/images/logo.png" title="CSS Track DIO Logo" alt="CSS Track DIO Logo">
      </div>
      <h1>CSS Track DIO</h1>
      <p>The new CSS Track from DIO is now available. Access now and learn from scratch how to develop professional websites.</p>
      <button>I want to enroll</button>
    </div>
  </header>
  <main>
    <section id="course-content">
      <h2>What will I learn?</h2>
      <p>We have 3 modules full of content from basic to advanced so you can learn how to develop professional websites using only HTML and CSS: without any extra library or framework.</p>
      <div class="module-list">
        <div class="module">
          <span>Module 01: </span>Getting started with CSS
        </div>
        <div class="module">
          <span>Module 02: </span>Working with layouts in CSS
        </div>
        <div class="module">
          <span>Module 03: </span>Refining CSS styles of our pages
        </div>
      </div>
    </section>
    <section id="transform-world">
      <p>TRANSFORM THE WORLD WITH US</p>
    </section>
    <section id="professional-challenges">
      <h2>Evolve and face new professional challenges</h2>
      <img src="assets/images/professional-challenges.png" title="Man Reading Testimonials in a Tablet" alt="Man Reading Testimonials in a Tablet">
      <p>Join our ecosystem and transform the world with us! Every day dozens of companies access our platform in search of the most creative, dynamic and collaborative talents, in addition to technical knowledge. Our mission is to prepare you so that you connect with the best opportunities.</p>
    </section>
  </main>
  <footer>
    <img class="dio-logo" src="assets/images/dio-logo.png" title="DIO Logo with the text make the change" alt="DIO Logo with the text make the change">
    <p>Access <a href="https://dio.me">dio.me</a> and register now</p>
  </footer>
</body>
</html>
