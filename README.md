# Personal-Website
This is the website where my portfolio can be found online once it is completed.


<html lang="en">

<head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  <link rel="stylesheet" href="styles.css">
  <script src="index.js"></script>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <link rel="shortcut icon" type="img/jpg" href="images/facivconC.ico"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Caleb's Website</title>

</head>
<body>
<header>

  <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">caleb.</a>
      <button
        class="navbar-toggler"
        type="button"
        data-mdb-toggle="collapse"
        data-mdb-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <i class="fas fa-bars"></i>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" href="">projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">about</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">contact</a>
          </li>

          </li>
        </ul>
      </div>
    </div>
  </nav>

<div class="headerbox">
<div class="headerin">

  <img class="headerimage" src="images/redheader.jpeg" alt="">

 <p class="title">
   Hi, I'm Caleb.
   <br>
  </p>
   <p class="title2">
   A Front End
   <br>
   Web Developer.
   <table>
    <tr>
        <td class="animated zoomIn" style="animation-delay:2.4s;"><a class="social" href="" target="_blank"><i class="fa fa-codepen"></i></a>
        </td>
        <td class="animated zoomIn" style="animation-delay:2.6s;"><a class="social" href="https://www.instagram.com/calebdavidson/" target="_blank"><i class="fa fa-instagram"></i></a></td>
        <td class="animated zoomIn" style="animation-delay:2.8s;"><a class="social" href="https://www.linkedin.com/in/calebgdavidson/" target="_blank"><i class="fa fa-linkedin"></i></a></td>
        <td class="animated zoomIn" style="animation-delay:2.8s;"><a class="social" href="https://github.com/calebgdavidson" target="_blank"><i class="fa fa-github"></i></a>
        </td>
    </tr>
</table>
  </p>


  
</div>
  </div>
</header>

<div inputmode="projects">
 
  <h2>projects</h2>

  <div id="photos">
      <a href="https://www.instagram.com/calebdavidson/" target="_blank"><img src="images/redheader.jpeg" title="I made this!"></a>

      <a href="https://www.instagram.com/calebdavidson/" target="_blank"><img src="images/redheader.jpeg" title="I made this!"></a>

      <a href="https://www.instagram.com/calebdavidson/" target="_blank"><img src="images/redheader.jpeg" title="I made this!"></a>

      <a href="https://www.instagram.com/calebdavidson/" target="_blank"><img src="images/redheader.jpeg" title="I made this!"></a>

      <a href="https://www.instagram.com/calebdavidson/" target="_blank"><img src="images/redheader.jpeg" title="I made this!"></a>

      <a href="https://www.instagram.com/calebdavidson/" target="_blank"><img src="images/redheader.jpeg" title="I made this!"></a>

  </div>
</div>

<div class="aboutme">
<h1>about</h1>
<p class="aboutp">Hello! I'm Caleb. I love video games, musical instruments, world history, programming, and the outdoors. A common theme throughout my life is my predisposition to be self taught. Whether it be the 4 different instruments that I play, learning a programming langauage, memorizing a U.S. Navy funeral honors handbook from front to back to become certified while Active Duty, or a number of other hobbies and interests. 
  </p>
  <br>
  <br>
  <p class = "aboutp2">
After serving 6 years in the U.S. Navy I decided to dedicate myself to learning Web Design and throughout the process have discovering a new favorite interest and hope to be able to bring my current skills to a team to grow, be challenged, and build upon what I currently know.</p>
</div>

<h2 class="contacth2">contact</h2>
<div id="contact">
  <table>
      <tr>
          <td>
              <div id="inner_div">
                  <table id="inner_table">
                      <tr>
                          <td class="contact-info"><i class="fa fa-phone"></i> &nbsp; (423)646-0910</td>
                      </tr>
                      <tr>
                          <td class="contact-info"><i class="fa fa-at"></i> &nbsp; calebgdavidsonn@gmail.com</td>
                      </tr>
                      <tr>
                          <td class="contact-info"><i class="fa fa-map-marker"></i>
                            &nbsp;Murfreesboro, Tennessee
                                </td>
                              </tr> 
                              </div>                                           
                  </table>
              </div>
          </td>
          <td>
              <form action="https://formspree.io/xyyelvqa" method="POST">
                  <input type="text" placeholder="name" name="name" required>
                  <input type="email" placeholder="email" name="_replyto" required><br>
                  <textarea placeholder="your message" name="message" required rows="5"></textarea><br>
                  <button type="submit" class="btn_one">send</button>
              </form>
          </td>
      </tr>
  </table>
</div>

</body>
</html>
