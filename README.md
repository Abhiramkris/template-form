# template-formsingle page 
Template in HTML 

<!DOCTYPE html>

<html>

<head>

  <meta name="viewport" content="height=device-height, 

                      width=device-width, initial-scale=1.0, 

                                            minimum-scale=1.0, maximum-scale=1.0, 

                                                                  user-scalable=no, target-densitydpi=device-dpi">

  <meta http-equiv="X-UA-Compatible" content="ie=edge" />

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>

<style type="text/css">

  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800&display=swap");

  * {

    margin: 0;

    padding: 0;

    background-color: white;

  }

  html,

  body {}

  .box {

    position: relative;

    width: auto;

    z-index: 1;

    right: 0;

    bottom: 0;

    height: 55vh;

    overflow: scroll;

    display: flex;

    align-items: center;

    justify-content: center;

    border-radius: 30px;

    margin-left: 4.3vh;

    margin-right: 4.3vh;

    overflow-x: hidden;

    overflow-y: auto;

    box-shadow: 0 10px 10px -1px rgba(0, 0.5, 0.3, 1);

    background: rgb(230, 233, 233);

    background: linear-gradient(9deg, rgba(230, 233, 233, 0.7884615384615384) 0%, rgba(11, 170, 131, 1) 62%, rgba(155, 238, 255, 1) 100%);

  }

  .box:before {

    content: "";

    z-index: -1;

    top: 0;

    right: 0;

    bottom: 0;

    left: 0;

    background: inherit;

    transform: translateY(20px) scale(0.95);

    filter: blur(20px);

    opacity: 0.7;

    transition: opacity 0.3s;

  }

  .head {

    color: Green;

    position: relative;

    display: flex;

    align-items: center;

    font-family: Verdana, Arial, sans-serif;

    font-weight: 200;

    font-size: 2.5rem;

    height: 3rem;

    justify-content: center;

  }

  .rights {

    font-size: .5rem;

    color: black;

    cursor: pointer;

    display: table;

    margin-right: auto;

    margin-left: auto;

    transition: 0.5s;

  }

  #svg {

    position: relative;

  }

  .form {

    position: absolute;

    background-color: transparent;

    margin-top: 7rem;

    width: 100%;

    cursor: pointer;

    display: table;

    margin-right: auto;

    margin-left: auto;

  }

  .input-field {

    color: black;

    ? background-color: white;

  }

  .social-media {

    display: flex;

    background-image: white;

    justify-content: center;

    box-shadow: 0 2px 3px -1px rgba(10, 5, 0.3, 1);

  }

  .social-icon {

    height: 3rem;

    width: 3rem;

    display: block;

    margin: 0 0.5em;

    align-content: center;

    align-items: center;

    color: green;

    text-decoration: none;

    font-size: 1rem;

    transition: 0.3s;

    -webkit-animation: fadein 5s;

    /* Safari, Chrome and Opera > 12.1 */

    -moz-animation: fadein 5s;

    /* Firefox < 16 */

    -ms-animation: fadein 5s;

    /* Internet Explorer */

    -o-animation: fadein 5s;

    /* Opera < 12.1 */

    animation: fadein 3s;

  }

  @keyframes fadein {

    from {

      opacity: -3;

    }

    to {

      opacity: 3;

    }

  }

  .social-text {

    padding: 0.7rem 0;

    font-size: 0.7rem;

    text-align: center;

    width: 100%;

    height: 100%;

    color: grey;

  }

  .input-field {

    width: 100%;

    background-color: transparent;

    margin: 1.5rem 2rem;

    height: 35px;

    display: grid;

    grid-template-columns: 15% 55%;

    padding: 0 0.34rem;

    position: relative;

  }

  .input-field i {

    text-align: center;

    line-height: 2.4rem;

    background-color: transparent;

    color: black;

    transition: 0.5s;

    font-size: 1.1rem;

  }

  .input-field input {

    background: transparent;

    line-height: 1;

    font-weight: 300;

    border-radius: .4rem;

    border: 1px solid white;

    font-size: .8rem;

    color: white;

    padding: .3em;

  }

  .input-field input:hover {

    background-color: #8FC0D096;

  }

  .input-field input::placeholder {

    color: white;

    font-weight: 300;

    font-size: 0.8rem;

    margin-left: 3rem;

  }

  #sbtn {

    width: 150px;

    border: 1px solid black;

    height: 2rem;

    border-radius: 19px;

    color: green;

    text-transform: uppercase;

    font-weight: 900;

    margin-top: .1rem;

    cursor: pointer;

    display: table;

    margin-right: auto;

    margin-left: auto;

    transition: 0.5s;

    background-color: transparent;

  }

  .tp {

    width: 100;

  }

  #sbtn:hover {

    background-color: #8FC0D0D1;

  }

  .log {

    cursor: pointer;

    display: table;

    margin-left: auto;

    transition: 0.5s;

    color: white;

    text-decoration: none;

    font-size: .7rem;

    font-family: monospace;

    font-weight: 300;

    margin-right: 2.5rem;

  }

  .tr {

    font-family: monospace;

    font-size: .9vh;

    text-align: center;

    color: grey;

  }

</style>

<script src="https://kit.fontawesome.com/64d58efce2.js" crossorigin="anonymous"></script>

<body>

  <br><br><br><br><br>

  <div class="head">Any problems..</div>

  <div class="tr">We will never let you to get in trouble <br>Feel free to ask anything</div>

  <br>

  <div class="box">

    <form action="https://usebasin.com/f/328e76f18669" class="form" method="post">

      <br><br>

      <div class="input-field">

        <i class="fas fa-user"></i>

        <input type="text" placeholder="Name" important! name="name" />

      </div>

      <div class="input-field">

        <i class="fas fa-envelope"></i>

        <input type="text" placeholder="Email" name="email" />

      </div>

      <div class="input-field">

        <i class="fas fa-compass"></i>

        <input type="text" placeholder="Place your troubles here" name="subject" />

      </div>

      <p class="social-text">Or write us on social media platforms </p>

      <div class="social-media">

        <a href="#" class="social-icon">

          <i class="fab fa-facebook-f"></i>

        </a>

        <a href="#" class="social-icon">

          <i class="fab fa-twitter"></i>

        </a>

        <a href="#" class="social-icon">

          <i class="fab fa-google"></i>

        </a>

      </div>

      <br><br>

      <button id="sbtn" type="submit">Done!

        <script type="text/javascript">

          document.getElementById("myButton").onclick = function() {

            location.href = "www.yoursite.com";

          };

        </script>

      </button>

      <br><br>

  </div>

  </form>

  <br>

  <div class="rights">

    CREM all rights reserved.</div>

  <br><br><br>

</body>

</html>
