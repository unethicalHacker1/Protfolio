<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfoli</title>

    <script src="jquery3.7.1.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
    <style>
      .texts{
        font-family:'Roboto',sans-serif;
        text-align: center;
    }
    .p-texts{
        font-family:'Roboto',sans-serif;
        text-align: center;
        font-size: large;
        margin-top: 15px;
    }
    .man-pic {
        margin-top: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .computer-pic{
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .intro{
        background-color: #6E07F3;
        color: white;
        padding: 20px;
    }
    #greeting-text{
        text-align:center;
        padding-left: 50px;
        padding-right: 50px;
        padding-top: 50px;
    }
    #intro-text{
    padding: 50px;
    font-size: large;
    }
    .card-title{
        padding-top: 50px;
        padding-bottom: 20px;
    }
    ul.no-bullets {
        list-style-type: none;
        margin: 0;
        padding: 0;
      }
    .card-block{
        padding-bottom: 50px;
    }
    </style>
</head>
<body>
    <nav class="navbar navbar-light ">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src="logo.png" alt="pic" width="100px" height="100px"></a>
          <button class="btn border-0 btn-xs" type="button" >
            <div class="navbar-toggler-icon"></div>
          </button>
        </div>
      </nav>

    <div class="starting-text" style="display: flex;flex-direction:column">
        <h1 class="texts">
           <b>Designer, Frontend Developer & Mentor</b>
        </h1>
        <p class="p-texts">I design and code beautifully simple things, and I love what I do.
        </p>
        <div class="man-pic">
            <img src="https://mattfarley.ca/img/mf-avatar.svg" alt="manpicture" height="160px" width="160px">
        </div>
        <div class="computer-pic">
            <img src="https://mattfarley.ca/img/hero-devices.svg" alt="computer" height="750px" width="750px">
        </div>
    </div>

    <div class="intro">
        <h3 id="greeting-text">
            Hi. I'm Soban. Nice to meet you.
        </h3>
        <p id="intro-text">
            I'm a passionate professional with a strong focus on Flutter and web development, where I've made significant contributions. Previously, I worked with Optimumtech as a Junior Flutter Developer. My journey includes hands-on experience in web development projects, which has allowed me to refine my skills in this field.
        </p>
        <div class="row">
            <div class="col-md-6">
            <div class="card">
              <div class="card-block">
                <h4 class="card-title text-dark text-center" >Designer</h4>
                <p class="card-text text-dark text-center fs-5">I value simple content structure, clean design patterns, and thoughtful interactions.</p>
                <p class="card-text text-primary text-center fs-5">Things I enjoy designing:</p>
                <p class="card-text text-dark text-center fs-5">UX, UI, Web, Apps, Logos</p>
                <p class="card-text text-primary text-center fs-5">Design Tools:</p>
                <ul class=" no-bullets card-text text-dark text-center fs-5">
                    <li>Affinity Designer</li>
                    <li>Figma</li>
                    <li>Pen & Paper</li>
                    <li>Sketch</li>
                    <li>Webflow</li>
                </ul>
            </div>
            </div>
        </div>
        
        <div class="col-md-6">
            <div class="card card-inverse card-primary text-center">

              <div class="card-block ">
                <h4 class="card-title text-dark text-center" >Frontend Developer</h4>
                <p class="card-text text-dark text-center fs-5">I like to code things from scratch, and enjoy bringing ideas to life in the <br>browser.</p>
                <p class="card-text text-primary text-center fs-5">Languages I speak:</p>
                <p class="card-text text-dark text-center fs-5">HTML, C++, Python, CSS, Dart, C#</p>
                <p class="card-text text-primary text-center fs-5">Dev Tools:</p>
                <ul class=" no-bullets card-text text-dark text-center fs-5">
                    <li>VSCode</li>
                    <li>Bootstrap</li>
                    <li>Android Studio</li>
                    <li>Canva</li>
                    <li>Github</li>
                </ul>
            </div>
            </div>
        </div>
        </div>
    </div>

    <div style="padding-top: 70px;text-align: center;">
        <h4>
            Thanks for Visiting.
        </h4>
    </div>
        
    <div class="container my-5">


        <footer
                class="text-center text-lg-start text-white"
                style="background-color: #1c2331"
                >

          <section
                   class="d-flex justify-content-between p-4"
                   style="background-color: #6351ce"
                   >

            <div class="me-5">
              <span>Get connected with us on social networks:</span>
            </div>

            <div>
              <a href="https://twitter.com/SobanSaeed10" class="text-white me-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
                  <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334q.002-.211-.006-.422A6.7 6.7 0 0 0 16 3.542a6.7 6.7 0 0 1-1.889.518 3.3 3.3 0 0 0 1.447-1.817 6.5 6.5 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.32 9.32 0 0 1-6.767-3.429 3.29 3.29 0 0 0 1.018 4.382A3.3 3.3 0 0 1 .64 6.575v.045a3.29 3.29 0 0 0 2.632 3.218 3.2 3.2 0 0 1-.865.115 3 3 0 0 1-.614-.057 3.28 3.28 0 0 0 3.067 2.277A6.6 6.6 0 0 1 .78 13.58a6 6 0 0 1-.78-.045A9.34 9.34 0 0 0 5.026 15"/>
                </svg>
              </a>
              <a href="https://mail.google.com/mail/u/0/#inbox" class="text-white me-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-google" viewBox="0 0 16 16">
                  <path d="M15.545 6.558a9.4 9.4 0 0 1 .139 1.626c0 2.434-.87 4.492-2.384 5.885h.002C11.978 15.292 10.158 16 8 16A8 8 0 1 1 8 0a7.7 7.7 0 0 1 5.352 2.082l-2.284 2.284A4.35 4.35 0 0 0 8 3.166c-2.087 0-3.86 1.408-4.492 3.304a4.8 4.8 0 0 0 0 3.063h.003c.635 1.893 2.405 3.301 4.492 3.301 1.078 0 2.004-.276 2.722-.764h-.003a3.7 3.7 0 0 0 1.599-2.431H8v-3.08z"/>
                </svg>
              </a>
              <a href="https://www.instagram.com/soban_saeed1/" class="text-white me-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
                  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334"/>
                </svg>
              </a>

              <a href="https://www.facebook.com/waheeda.aziz.50/" class="text-white me-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
                  <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951"/>
                </svg>
              </a>
            </div>

          </section>

      

          <section class="">
            <div class="container text-center text-md-start mt-5">

              <div class="row mt-3">

                <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">

                  <h6 class="text-uppercase fw-bold">Useful links</h6>
                  <hr
                      class="mb-4 mt-0 d-inline-block mx-auto"
                      style="width: 60px; background-color: #7c4dff; height: 2px"
                      />
                  <p>
                    <a href="" class="text-white">Your Account</a>
                  </p>
                  <p>
                    <a href="#!" class="text-white">Become an Affiliate</a>
                  </p>

                  <p>
                    <a href="#!" class="text-white">Help</a>
                  </p>
                </div>

                <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">

                  <h6 class="text-uppercase fw-bold">Contact</h6>
                  <hr
                      class="mb-4 mt-0 d-inline-block mx-auto"
                      style="width: 60px; background-color: #7c4dff; height: 2px"
                      />
                  <p><i class="fas fa-home mr-3"></i> New York, NY 10012, US</p>
                  <p><i class="fas fa-envelope mr-3"></i> sobansaeed21@gmail.com</p>
                  <p><i class="fas fa-phone mr-3"></i> + 01 234 567 88</p>
                </div>
              </div>

            </div>
          </section>

      

          <div
               class="text-center p-3"
               style="background-color: rgba(0, 0, 0, 0.2)"
               >
            © 2020 Copyright
          </div>
        </footer>
      
      </div>
        
</body>
</html>
