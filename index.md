<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/css/bootstrap.min.css"
      integrity="sha384-zCbKRCUGaJDkqS1kPbPd7TveP5iyJE0EjAuZQTgFLD2ylzuqKfdKlfG/eSrtxUkn"
      crossorigin="anonymous"
    />
    <title>Marian Schlinger</title>
    <link rel="stylesheet" href="css/style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@300;400;500;600;700&family=Red+Hat+Mono:wght@300&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <section id="showcase" class="d-flex">
      <div class="" id="overlay"></div>
      <div class="header"></div>
    </section>

    <header class="sticky-top">
      <nav
        class="navbar navbar-expand-md navbar-dark"
        style="background-color: rgb(31, 31, 31)"
      >
        <a href="#" class="navbar-brand d-flex align-items-end">
          <img class="miniatura"
            src="images/icons8-programmer-64wh.png"
            class="my-0"
            alt="prog"
          /><span class="jmeno" style="color:#00DFC7 ">Marian Schlinger</span
          ><span class="hodnost" style="color:#00DFC7 ">_programmer</span>
        </a>
        <button
          class="navbar-toggler"
          data-toggle="collapse"
          data-target="#mainNav"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="mainNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a href="#showcase" class="nav-link hvr-underline-from-left" style="color:#00DFC7 "
                >Home</a
              >
            </li>
            <li class="nav-item">
              <a href="#page1" class="nav-link hvr-underline-from-left" style="color:#00DFC7 "
                >About</a
              >
            </li>
            <li class="nav-item">
              <a href="#projects" class="nav-link hvr-underline-from-left" style="color:#00DFC7 ">
                Projects</a>
            </li>
            <li class="nav-item">
              <a href="#skills" class="nav-link hvr-underline-from-left" style="color:#00DFC7 "
                >Skills</a
              >
            </li>
            <li class="nav-item">
              <a href="#formular" class="nav-link hvr-underline-from-left"style="color:#00DFC7 "
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </nav>
    </header>

    <span id="page1"></span>
    <section id="karusel">
        <div class="container text-center mt-5 p-3" style="border:solid silver 1px">
          <h2><span class="barva_nadpisb">{</span>About me<span class="barva_nadpisb">}</span></span></h2>
          <div class="row mt-4 p-3">
            <div class="col">
                <img src="images/1632144920928.jpg" class="obrazok" alt="FOTO">
            </div>
            <div class="col-lg-6 d-flex justify-content-center flex-column" style="font-size: 15pt;">
              <p class="text-justify" >
                Now there is an opportunity in my life to do what I really enjoy.
                At the moment, I am participating in the well-known programming
                bootcamp in Langueages(C #, Java) at VŠB-TUO. I am a lifelong
                technology enthusiast and I like to self-educate myself about
                programing and IT in general. I can also speak English fluently
                and I have no problem with writen form of english too. I am able
                to maintaining and understanding the conversation in English. My
                strenghts are responsibility, reliability and I can work both
                independently and in a team.
              </p>
            <div class="col">
                <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                      <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
                      <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
                      <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
                    </ol>
                    <div class="carousel-inner">
                      <div class="carousel-item active">
                        <img src="images/mushroom.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <div class="rounded bg-dark text-white" style="opacity: .8;">
                          <p>Mushroom-picking</p>
                            </div>
                        </div>
                      </div>
                      <div class="carousel-item">
                        <img src="images/camping1.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <div class="rounded bg-dark text-white" style="opacity: .8;">
                                <p>Camping</p>
                                  </div>
                        </div>
                      </div>
                      <div class="carousel-item">
                        <img src="images/walk.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                            <div class="rounded bg-dark text-white" style="opacity: .8;">
                                <p>night walk</p>
                                  </div>
                        </div>
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-target="#carouselExampleCaptions" data-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="sr-only">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-target="#carouselExampleCaptions" data-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="sr-only">Next</span>
                    </button>
                  </div>
            </div>
            </div>
          </div>
        </div>
      </section>

      <section id="projects">
          <div class="container text-center mt-5 p-3" style="border:solid silver 1px">
            <h2><span class="barva_nadpisb">{</span>Projects<span class="barva_nadpisb">}</span></h2>
              <div class="row">
                  <div class="col-md-6">
                    <div class="card" style="border:solid silver 1px">
                      <a href="projekty/skolni/index.html" target="_blank"><img src="images/skolni.PNG" class="card-img-top" alt="skol"></a>
                        <div class="card-body" style="background-color: #f7f7f7;">
                          <p class="card-text" style="font-weight: bolder;">project from bootcmap, it cost about four hours.</p>
                        </div>
                      </div>
                  </div>
                  <div class="col-md-6">
                    <div class="card" style="border:solid silver 1px">
                        <img src="images/work.jpg" class="card-img-top" alt="grove">
                        <div class="card-body" style="background-color: #f7f7f7 ;">
                          <p class="card-text" style="font-weight: bolder;">work in progress</p>
                        </div>
                      </div>
                  </div>
              </div>
          </div>
      </section>

    <section id="skills">
      <div class="container text-center mt-5 p-3">
        <h2><span class="barva_nadpisb">{</span>SKILLS<span class="barva_nadpisb">}</span></h2>
        <div style="border:solid silver 1px">
          <br />
          <div class="row justify-content-center">
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-java-100.png" alt="JavaScript"
              /></a>
              <p>Java</p>
            </div>
            <div class="col col-md-3">
              <a class="hvr-buzz-out">
                <img
                  src="images/icons/icons8-c-sharp-logo-100.png"
                  alt="JavaScript"
              /></a>
              <p>C#</p>
            </div>
          </div>
          <h3><span class="barva_nadpis">[</span>Programming Langueages<span class="barva_nadpis">]</span></h3>
        </div>
        <br />

        <div style="border:solid silver 1px">
          <br />
          <div class="row justify-content-center">
            <div class="col col-lg-2">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-jquery-100.png" alt="jquery"
              /></a>
              <p>jQuery</p>
            </div>
            <div class="col col-lg-2">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-html-5-100.png" alt="HTML5"
              /></a>
              <p>HTML5</p>
            </div>
            <div class="col col-lg-2">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-css3-100.png" alt="CSS3"
              /></a>
              <p>CSS3</p>
            </div>
            <div class="col col-lg-2">
              <a class="hvr-buzz-out"
                ><img
                  src="images/icons/icons8-bootstrap-96.png"
                  alt="Bootstrap"
              /></a>
              <p>Bootstrap</p>
            </div>
            <div class="col col-lg-2">
              <a class="hvr-buzz-out"
                ><img
                  src="images/icons/icons8-javascript-100.png"
                  alt="JavaScript"
              /></a>
              <p>Java Script</p>
            </div>
            <div class="col col-lg-2">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-php-100.png" alt="PHP"
              /></a>
              <p>PHP</p>
            </div>
          </div>
          <h3><span class="barva_nadpis">[</span>WWW<span class="barva_nadpis">]</span></h3>
        </div>
        <br />

        <div style="border:solid silver 1px">
          <br />
          <div class="row justify-content-center">
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-access-96.png" alt="JavaScript"
              /></a>
              <p>Access</p>
            </div>
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img
                  src="images/icons/icons8-oracle-logo-100.png"
                  alt="JavaScript"
              /></a>
              <p>Oracle</p>
            </div>
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-server-100.png" alt="JavaScript"
              /></a>
              <p>MS SQL Server</p>
            </div>
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-sql-100.png" alt="JavaScript"
              /></a>
              <p>PL/SQL</p>
            </div>
          </div>
          <h3><span class="barva_nadpis">[</span>Database<span class="barva_nadpis">]</span></h3>
        </div>
        <br />

        <div style="border:solid silver 1px">
          <br />
          <div class="row justify-content-center">
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img
                  src="images/icons/icons8-xamarin-100.png"
                  alt="JavaScript"
              /></a>
              <p>Xamarin</p>
            </div>
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img
                  src="images/icons/icons8-android-studio-96.png"
                  alt="JavaScript"
              /></a>
              <p>Android Studio</p>
            </div>
          </div>
          <h3><span class="barva_nadpis">[</span>Mobile Application<span class="barva_nadpis">]</span></h3>
        </div>
        <br />

        <div style="border:solid silver 1px">
          <br />
          <div class="row justify-content-center">
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img
                  src="images/icons/icons8-server-windows-100.png"
                  alt="JavaScript"
              /></a>
              <p>Windows</p>
            </div>
            <div class="col col-md-3">
              <a class="hvr-buzz-out"
                ><img src="images/icons/icons8-linux-100.png" alt="JavaScript"
              /></a>
              <p>Linux</p>
            </div>
          </div>
          <h3><span class="barva_nadpis">[</span>OS<span class="barva_nadpis">]</span></h3>
        </div>
        <br />
      </div>
    </section>

    <section id="formular">
      <div class="container text-center mt-5" style="border:solid silver 1px">
        <h2><span class="barva_nadpisb">{</span>Contact me<span class="barva_nadpisb">}</span></h2>
        <div class="row m-3 p-3">
          <div class="col col-md-12 text text-center">
            <form>
              <div class="form-group">
                <input
                  type="email"
                  class="form-control"
                  id="exampleFormControlInput1"
                  placeholder="full name"
                />
              </div>
              <div class="form-group">
                <input
                  type="email"
                  class="form-control"
                  id="exampleFormControlInput1"
                  placeholder="e-mail"
                />
              </div>
              <div class="form-group">
                <input
                  type="email"
                  class="form-control"
                  id="exampleFormControlInput1"
                  placeholder="subject"
                />
              </div>
              <div class="form-group">
                <textarea
                  class="form-control"
                  id="exampleFormControlTextarea1"
                  placeholder="message for me"
                  rows="3"
                ></textarea>
              </div>
            </form>
            <div class="row">
                <div class="col">
                    <button type="button" class="btn btn-dark" style="background-color: rgb(31, 31, 31); color:#00DFC7 ; font-weight: bold" >SUBMIT</button>
                </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="footer" style="background-color: rgb(34, 34, 34)">
      <div class="container text-center">
        <div class="row">
          <div class="col col-lg-3">
            <a
              href="https://cz.linkedin.com/in/marian-schlinger-9a71a721a"
              class="nav-link text-white"
              target=”_blank”
            >
              <img src="images/icons/icons8-linkedin-24.png" alt="." />
            </a>
          </div>
          <div class="col col-lg-3">
            <a
              href="https://cs-cz.facebook.com/marian.schlinger"
              class="nav-link text-white"
              target=”_blank”
            >
              <img src="images/icons/icons8-facebook-24.png" alt="." />
            </a>
          </div>
          <div class="col col-lg-3">
            <a href="https://github.com/Excorte" class="nav-link text-white" target=”_blank” >
              <img src="images/icons/icons8-github-24.png" alt="." />
            </a>
          </div>
          <div class="col col-lg-3">
            <a
              href="mailto:majaschlinger@gmail.com"
              class="nav-link text-white"
            >
              <img src="images/icons/icons8-mail-24.png" alt="." />
            </a>
          </div>
        </div>
      </div>
    </section>

    <script
      src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
