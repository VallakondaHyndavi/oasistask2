<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <link rel="stylesheet" href="styles.css">

        <!-- =====BOX ICONS===== -->
        <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'>
        <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.0/css/line.css">

        <title>Portfolio | vallakonda Hyndavi</title>
        <style>
            body {
               background-image: url("data:image/jpeg;base64,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");
            }
         </style>
    </head>
    <body>
        <!--===== HEADER =====-->
        <header class="l-header">
            <nav class="nav bd-grid">
                <div>
                    <a href="#" class="nav__logo">Personal Portfolio</a>
                </div>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active"><i class="uil uil-estate"></i> Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link"><i class="uil uil-user"></i> About</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link"><i class="uil uil-file-copy-alt"></i> Skills</a></li>
                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class='bx bx-menu'></i>
                </div>
            </nav>
        </header>

        <main class="l-main">
            <!--===== HOME =====-->
            <section class="home bd-grid" id="home">
                <div class="home__data">
                    <h1 class="home__title">Hey..!<br>I'am <span class="home__title-color">Vallakonda Hyndavi</span><br>Cyber Security Student</h1>

                    <a href="https://docs.google.com/document/d/1NgO96-dIh9O2sTjniT7Mcix154FuXizlnzPtpYUDg-M/edit?usp=sharing" target="_blank" class="button">Resume</a>
                </div>

                <div class="home__social">
                    <a href="https://www.linkedin.com/in/hyndavi-vallakonda-564734258/" target="_blank" class="home__social-icon"><i class='bx bxl-linkedin'></i></a>
                    
                    <a href="https://github.com/VallakondaHyndavi" target="_blank" class="home__social-icon"><i class='bx bxl-github' ></i></a>
                    
                </div>
                
            
                
                   
                    
                

              
              
            </section>

            <!--===== ABOUT =====-->
            <section class="about section " id="about">
                <h2 class="section-title"><i class="uil uil-user"></i> About</h2>

                <div class="about__container bd-grid">
                    <div class="about__img">
                        <img src="assets/img/about.png" alt="">
                    </div>
                    
                    <div>
                        <h2 class="about__subtitle">I'am Vallakonda Hyndavi</h2>
                        <p><b>Passionate Learner </b></p>
                        <p class="about__text"> Student at Sri Indu College of Engineering and Technology        -3rd year CYBER SECURITY.</p>  
                     
                            
                              <p><b><i class="uil uil-university"></i> Affiliated With</b> : Jawaharlal Nehru Technological University,Hyderabad</p>
                              <p><b><i class="uil uil-envelope-edit"></i> Email</b> : vallakondahyndavi@gmail.com</p>
                              <p><b><i class="uil uil-map-marker-shield"></i> Place</b> : Telangana, India-502278 </p>
                              <p><b><i class="uil uil-phone-pause"></i> Call Me</b> : +91-7702289011</p>
                            </div>
                        </div>      
                    </div>    
                  </div>                               
                </div>
            </section>

            <!--===== SKILLS =====-->
            <section class="skills section" id="skills">
                <h2 class="section-title"><i class="uil uil-file-copy-alt"></i> Skills</h2>

                <div class="skills__container bd-grid">          
                    <div>
                        <h2 class="skills__subtitle">Technical Skills</h2>
                        <p class="skills__text">I have learned HTML5 ,Python,C ,Java .</p>
                            <p><b>Known Languages</b> : c,python,java,html5</p>                    
                    </div>
                
                        
                </div>
            </section>

<!--===== FOOTER =====-->
        <footer class="footer">
            
            <p class="footer__title">Vallakonda Hyndavi's Portfolio</p>
            <div class="footer__social">
               
                
                <a href="https://github.com/VallakondaHyndavi" target="_blank" class="footer__icon"><i class='bx bxl-github' ></i></a>
                <a href="https://www.linkedin.com/in/hyndavi-vallakonda-564734258/" target="_blank" class="footer__icon"><i class='bx bxl-linkedin' ></i></a>
            </div>
            <p>Thank you for visiting my Personal Portfolio website. </p>

            <p class="footer__copy">&#169;Vallakonda Hyndavi. All rigths reserved</p>
        </footer>
        <!--===== SCROLL REVEAL =====-->
        <script src="https://unpkg.com/scrollreveal"></script>

        <!--===== MAIN JS =====-->
        <script src="assets/js/main.js"></script>
    </body>
</html>
