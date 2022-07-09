# myFirstLearningProject
To create a simple webpage 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | Insure landing page</title>
  <link rel="stylesheet" href="styles.css">

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <!-- <style>
    .attribution { font-size: 11px; text-align: center; }
    .attribution a { color: hsl(228, 45%, 44%); }
  </style> -->
</head>
<body>
  
  <header class="hero">
    <nav class="nav">
      <div class="nav__container container">

        <figure class="nav__figure">
          <img src="images/logo.svg" class="nav__img" alt="" >
        </figure>

        <figure class="nav__hamburger">
          <img src="images/icon-hamburger.svg" class="nav__icon" alt="">
        </figure>

        <div class="nav__links">
          <a href="#" class="nav__link">How we work</a>
          <a href="#" class="nav__link">Blog</a>
          <a href="#" class="nav__link">Account</a>
          <a href="#" class="nav__link nav__link--cta">View plans</a>

        </div>


      </div>
    </nav>

    <section class="hero__main container">

      <div class="hero__texts">
        <h1 class="title">Humanizing your insurance</h1>
        <p class="hero__paragraph">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vero, aliquid assumenda ad non ipsa consequatur placeat quia corporis cumque, molestias quam nesciunt maxime itaque unde ipsam nostrum recusandae, quis fugit? </p>

        <a href="#" class="cta">View plans</a>

      </div>
   
    </section>

  </header>

  <main class="main">

    <section class="different container">
      <h2 class="title title__different">We are different</h2>
      <div class="different__items">
        <article class="different__item">
          <img src="images/icon-snappy-process.svg" alt="" class="different__icon">

          <h3 class="different__title">Snappy Process</h3>
          <p class="different__paragraph">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptate illo nisi sit sed </p>

        </article>

        <article class="different__item">
          <img src="images/icon-affordable-prices.svg" alt="" class="different__icon">

          <h3 class="different__title">Affordable Prices</h3>
          <p class="different__paragraph">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptate illo nisi sit sed </p>

        </article>

        <article class="different__item">
          <img src="images/icon-people-first.svg" alt="" class="different__icon">

          <h3 class="different__title">People first</h3>
          <p class="different__paragraph">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptate illo nisi sit sed </p>

        </article>
      </div>
    </section>

    <section class="find">
        <div class="find__container container">
          <h2 class="title title--find">Find out more about how we work</h2>
          <a href="#" class="cta cta--find">How we work</a>
        </div>
    </section>

  </main>

  <footer class="footer">
    <section class="footer__container container">

      <div class="footer__brand">
        <figure class="footer__picture">
          <img src="images/logo.svg" class="footer__img" alt="">
        </figure>

        <div class="footer__contact">
          <a href="#" class="footer__media">
            <img src="images/icon-facebook.svg" class="footer__icon" alt="">
          </a>

          <a href="#" class="footer__media">
            <img src="images/icon-twitter.svg" class="footer__icon" alt="">
          </a>

          <a href="#" class="footer__media">
            <img src="images/icon-pinterest.svg" class="footer__icon" alt="">
          </a>

          <a href="#" class="footer__media">
            <img src="images/icon-instagram.svg" class="footer__icon" alt="">
          </a>



        </div>

      </div>

      <div class="footer__navigation">
        <nav class="footer__nav">
          <a href="#" class="footer__link footer__link--first">Our company</a>
          <a href="#" class="footer__link">How we work</a>
          <a href="#" class="footer__link">Why ensure?</a>
          <a href="#" class="footer__link">View plants</a>
          <a href="#" class="footer__link">Reviews</a>
        </nav>

        <nav class="footer__nav">
          <a href="#" class="footer__link footer__link--first">Help me</a>
          <a href="#" class="footer__link">FAQ</a>
          <a href="#" class="footer__link">Terms of use</a>
          <a href="#" class="footer__link">Privacy policy</a>
          <a href="#" class="footer__link">Cookies</a>
        </nav>

        <nav class="footer__nav">
          <a href="#" class="footer__link footer__link--first">Contact</a>
          <a href="#" class="footer__link">Sales</a>
          <a href="#" class="footer__link">Support</a>
          <a href="#" class="footer__link">Live Chat</a>
        </nav>

        <nav class="footer__nav">
          <a href="#" class="footer__link footer__link--first">Others</a>
          <a href="#" class="footer__link">Careers</a>
          <a href="#" class="footer__link">Press</a>
          <a href="#" class="footer__link">Licenses</a>
        </nav>
      </div>


    </section>
  </footer>




</body>
</html>
