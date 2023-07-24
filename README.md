<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">

    <link rel="stylesheet" href="styles.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <title>PortFolio</title>

</head>
<body>
<header class="header">
    <nav class="nav bd-grid">
        <div>
            <a href="p.html" class="nav__logo">
                <span>P</span>arvez
            </a>
        </div>

        <div class="nav__menu" id="nav-menu"> 
            <ul class="nav__list">
                        <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                        <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                        <li class="nav__item"><a href="#experience" class="nav__link">Experience</a></li>
                        <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                        <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                        <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
            </ul>
        </div>

        <div class="nav__toggle" id="nav-toggle">
            <i class='bx bx-menu'></i>
        </div>
    </nav>
</header>
<main class="main">
    <section class="home bd-grid1" id="home">
        <div class="data">
             <h1 class="title"> <span class="a1">Hey! I am</span> <br>Parvez Khan<br> 
                <a href="" class="typewrite a2" data-period="2000" data-type='["I am Web Developer.", "I Love Design.", "I Love to Develop." ]'>
                 <span class="wrap"></span></a>
        </h1>
        </div>
 </section>
                                                     <!-- About -->
    <section id="about" class="about section" >
        <h2 class="section-title">About</h2>
        <div class="bd-grid about1">
            <div class="About_img">
                 <img src="parvezedit1.png" style="border-radius: 50%;">
            </div>
            <div>
                <h2 class="subtitle">Hello...</h2>
                <p class="text" style="font-family: Segoe UI; text-align: justify;line-height: 29px; font-size:medium;"><span class="text hover-underline-animation">I'm <b>Parvez Khan</b>, an experienced developer with a focus on web development. With over one year of professional experience, I have honed my skills in front-end technologies like HTML, CSS, and JavaScript,etc. as well as back-end languages such as Node.js and Java.</span><br><br><span class="text hover-underline-animation">I have a strong interest in data structures and algorithms, as they are essential for developing efficient software solutions. I continually seek opportunities to learn and stay updated with the latest trends.</span><br><br> <span class="text hover-underline-animation">Collaboration, effective communication, and problem-solving are central to my work, and I am passionate about taking on meaningful projects and contributing to the development community. Feel free to reach out to me for any potential opportunities or to learn more about my work.</span></p>

               <!--  <ul class="ul-flex">
                        <li class="li-flex">
                            <span>name:</span>
                            <span>Parvez Khan</span>
                        </li>
                        <li class="li-flex">
                            <span>name:</span>
                            <span>Parvez Khan</span>
                        </li>
                        <li class="li-flex">
                            <span>name:</span>
                            <span>Parvez Khan</span>
                        </li>
                        <li class="li-flex">
                            <span>name:</span>
                            <span>Parvez Khan</span>
                        </li>
                        
                    </ul> -->
            </div>
        </div>
    </section>


        <center>
            <section class="skills section" id="experience">
                <h2 class="section-title">Experience</h2>
                <div class="skills1 bd-gridd">
                    <div>
                        <h2 class="skills_subtitle">Professional Experience</h2>
                        <p class="skills_text" style="font-family: Segoe UI; text-align: justify; ">Over the past year, I have been actively involved in web development projects, gaining valuable hands-on experience in both front-end and back-end development. I have successfully contributed to the development and deployment of robust and scalable web applications, working collaboratively with cross-functional teams to deliver high-quality solutions.</p>
        
                 <div class="skills_data hov">
                    <div class="skills_names" style="height: 80px; font-size: 20px;">
                       <img src="https://yt3.googleusercontent.com/YbaRi4yKK88z0U9E_vY5K-YVQVozeJKk58N1AAJn4icwA-Zaj3rYw6V9_ZSosT81DSvYeQWEk0w=s900-c-k-c0x00ffffff-no-rj"  style="width: 50px; height: 50px;" />
                        <div>
                            <p><span class="skills_name">Cognizant Technology Solutions </span></p>
                            <p style="font-size: 16px; margin-top: 5px; margin-left:5px">Programmer</p> 
                        </div>
                        
                        
                    </div>
                    <div>
                        <span class="skills_percentage">Jan 2022 - Present</span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names" style="height: 80px; font-size: 20px;">
                        <img src="revise.jpg"  style="width: 50px; height: 50px;"/>
                        
                        <div>
                            <span class="skills_name" style=" margin-left:5px">Revisewise Education Solutions Pvt. Ltd. </span>
                            <p style="font-size: 16px; margin-top: 5px; margin-left:5px">Intern</p> 
                        </div>
                        
                    </div>
                    <div>
                        <span class="skills_percentage">June 2021 - Sep 2021</span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
                </div>
                </div>
            </section>
        </center>
                       

            
            <section class="work section" id="work" >
                <h2 class="section-title">Project Work</h2>
                <div >
                      <!-- jjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjj -->
                    <div class="skills1 bd-grid" >
                        <div >
                            <!-- <i class='bx bx-building skills__icon'></i> -->
                            <h2 class="skills_subtitle" >Hostel Leave Management Application</h2>
                            <p class="skills_text" >
                                <li class="image" >Developed a full stack hostel leave management application to streamline
                                    the process of applying for holiday and working day leaves for students.</li>
                                
                                <li class="image" >Utilized HTML, CSS, JavaScript, Node.js, Express.js, and MongoDB forthe
                                    development of the application.</li>
                                
                                <li class="image">Implemented features such as a user authentication system, leave request
                                    forms, and an admin panel for staff approval.</li>
                                
                                <li class="image">Created and maintained a MongoDB database to store student information
                                    and leave requests</li>
                                
                                <li class="image">Improved efficiency and transparency in the hostel leave management
                                    process, benefiting both students and staff.</li>
                            </p>
            
                    </div>
                    <div>
                        <iframe width="400" height="300px" src="https://www.youtube.com/embed/XrbYIy2GFHk?autoplay=1&mute=1" >
                        </iframe>
                    </div>
                    </div>
                      <!-- jjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjj -->

                       <!-- jjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjj -->
                    <div class="skills1 bd-grid" style="margin-top: 50px;">
                        <div >
                            <h2 class="skills_subtitle" >CodeWave Coding/Learning Platform</h2>
                            <p class="skills_text">
                                <li class="image">Developed a full stack web application to assist users in solving programming
                                    questions.</li>
                                
                                <li class="image">Utilized technologies such as HTML, CSS, JavaScript, Node.js, Express.js,
                                    and MongoDB.</li>
                                
                                <li class="image">Implemented a functionality that displays a list of programming questions
                                    and courses for users and added a solution button for each question,
                                    allowing users to view the answerin a pop-up.</li>
                                
                                <li class="image">Created a user authentication system, progress tracking, and question
                                    solving .
                                    </li>
                                
                                <li class="image">Managed a MongoDB database for storing userinformation and progress.</li>
                            </p>
            
                    </div>
                    <div>
                        <iframe width="400" height="300px" src="https://www.youtube.com/embed/adb4pmjte40?autoplay=1&mute=1" >
                        </iframe>
                    </div>
                    </div>
                      <!-- jjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjjj -->

                       
                <div class="work__container " style="margin-top: 20px;">
                    <div class="section-title">
                        <p>Mini Projects</p>
                    </div>
                    <div class="work__container bd-grid"> 
                       <div class="skills_data hov">
                    <div class="skills_names">
                        <i class='bx bx-list-ul skills__icon'></i>
                        <span class="skills_name"><a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/New%20folder%20(12)/tolist.html " class="anchor">To-DO List</a></span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                        <i class='bx bx-calculator skills__icon'></i>
                        <span class="skills_name "><a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/New%20folder%20(12)/JS%20Cal.html" class="anchor">JavaScript Calculator</a>   </span>
                    </div>
                    <div class="skills_bar skills_css1">
                        
                    </div>
                </div>
        
                   <div class="skills_data hov">
                       <div class="skills_names">
                        <i class='bx bxs-card skills__icon'></i>
                           <span class="skills_name "><a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/Memory-Game.html" class="anchor">Memory Card Game</a>  </span>
                       </div>
                       <div class="skills_bar skills_javascript1">
        
                       </div>
                   </div>
                      <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bx-sun skills__icon' ></i>
                        <span class="skills_name "> <a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/Weather%20App/Weather.html" class="anchor">Weather App</a> </span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
            </div>
        </div>
    </div>
            </section>



            <section class="work section" id="skills">
                <h2 class="section-title">Skills</h2>
        
                <div class="work__container bd-grid ">
                       <div class="skills_data hov" >
                    <div class="skills_names">
                        <i class='bx bxl-html5 skills__icon'></i>
                        <span class="skills_name">HTML 5</span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                        <i class='bx bxl-css3 skills__icon'></i>
                        <span class="skills_name ">CSS 3   </span>
                    </div>
                    <div class="skills_bar skills_css1">
                        
                    </div>
                </div>
        
                   <div class="skills_data hov">
                       <div class="skills_names">
                        <i class='bx bxl-javascript skills__icon'></i>
                           <span class="skills_name ">JavaScript  </span>
                       </div>
                       <div class="skills_bar skills_javascript1">
        
                       </div>
                   </div>
                      <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bxl-react skills__icon' ></i>
                        <span class="skills_name ">React </span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bxl-redux skills__icon' ></i>
                        <span class="skills_name ">Redux</span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bxl-nodejs skills__icon' ></i>
                        <span class="skills_name ">Node JS </span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bxl-nodejs skills__icon' ></i>
                        <span class="skills_name ">Express JS </span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bxl-nodejs skills__icon' ></i>
                        <span class="skills_name ">Next JS </span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
                <div class="skills_data hov">
                    <div class="skills_names">
                       <i class='bx bxl-java skills__icon' ></i>
                        <span class="skills_name ">Java </span>
                    </div>
                    <div class="skills_bar skills_html1">
                        
                    </div>
                </div>
        
               
        
        </div>
            </section>


    <!-- SKILLS -->
    <center>
    <section class="skills section" id="skills">
        <h2 class="section-title">Education</h2>
        <div class="skills1 bd-gridd">
            <div>
                <p class="skills_text1" style="opacity: 0; border: 1px solid red;">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptate cum expedita quo culpa tempora, assumenda, quis fugiat ut voluptates soluta</p>
                
         <div class="skills_data hov">
            <div class="skills_names" style="height: 80px; font-size: 20px;">
                <i class='bx bxs-graduation skills__icon'></i>
                <div>
                    <p><span class="skills_name">Chandigarh University (2022 - 2024)</span></p>
                    <p style="font-size: 16px; margin-top: 5px;margin-left:5px">Master Of Computer Application</p>
                </div>    
            </div>
            
            <div>
                <span class="skills_percentage">8.8 <i>CGPA</i></span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

        <div class="skills_data hov">
            <div class="skills_names" style="height: 80px; font-size: 20px;">
                <i class='bx bxs-graduation skills__icon'></i>
                <div>
                    <span class="skills_name">Amrapali Group Of Institute (2018 - 2021) </span>
                    <p style="font-size: 16px; margin-top: 5px;margin-left:5px">Bachelor Of Computer Application</p>
                </div>
                
            </div>
            <div>
                <span class="skills_percentage">7.4 <i>CGPA</i></span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

        <!-- <div>
            <img src="skills.webp" alt="" class="skills_img">
        </div> -->
        </div>
    </section>
    </center>

    <section class="work section2" id="work" style="font-size: medium;">
        <h2 class="section-title">Certification</h2>

        <div class="work__container bd-grid ">
               <div class="skills_data hov" >
            <div class="skills_names">
                <i class='bx bxs-certification skills__icon' ></i>
                <span class="skills_name">Full Stack Web Development Certification, Udemy</span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

        <div class="skills_data hov">
            <div class="skills_names">
                <i class='bx bxs-certification skills__icon' ></i>
                <span class="skills_name ">Java Certificate, Udemy</span>
            </div>
            <div class="skills_bar skills_css1">
                
            </div>
        </div>

           <div class="skills_data hov">
               <div class="skills_names">
                <i class='bx bxs-certification skills__icon' ></i>
                   <span class="skills_name ">React JS Certification ,Udemy </span>
               </div>
               <div class="skills_bar skills_javascript1">

               </div>
           </div>
</div>
    </section>

    
    <section class="work section3" id="work" >
        <h2 class="section-title">Achievement</h2>
        <div >
             
            <div class="skills2 bd-grid" >
                <div >
                    <p class="skills_text" >
                        <li class="image" style="font-size: 18px; ">Earned a Java Oracle learning Explorer Badge.<b><i>Oracle</i></b> </li>
                        
                        <li class="image" style="font-size: 18px; ">Achieved below 30k rank in the Leetcode coding platform and solved 700+ problems. <b><i>Leetcode</i></b> </li>
                        
            </div>
            
            </div>

    </div>
</div>
</div>
    </section>

    <section class="work section2" id="work" style="font-size: medium;">
        <h2 class="section-title">Links</h2>

        <div class="work__container bd-grid ">
               <div class="skills_data hov" >
            <div class="skills_names">
                <i class='bx bxl-linkedin-square skills__icon'></i>
                <span class="skills_name">LinkedIn</span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

        <div class="skills_data hov">
            <div class="skills_names">
                <i class='bx bx-code-alt skills__icon'></i>
                <span class="skills_name ">Leetcode</span>
            </div>
            <div class="skills_bar skills_css1">
                
            </div>
        </div>

           <div class="skills_data hov">
               <div class="skills_names">
                <i class='bx bxl-github skills__icon' ></i>
                   <span class="skills_name ">Github</span>
               </div>
               <div class="skills_bar skills_javascript1">

               </div>
           </div>
</div>
    </section>


    <!-- <section class="skills section" id="skills">
        <h2 class="section-title">Skills</h2>
        <div class="skills1 bd-grid" style="border: 1px solid red;">
            <div >
                <h2 class="skills_subtitle"> Professional Skills </h2>
                <p class="skills_text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptate cum expedita quo culpa tempora, assumenda, quis fugiat ut voluptates soluta, aut earum nemo recusandae cumque perferendis! Recusandae alias accusamus atque.</p>

         <div class="skills_data" >
            <div class="skills_names">
                <i class='bx bxl-html5 skills__icon'></i>
                <span class="skills_name">HTML5</span>
            </div>
            <div>
                <span class="skills_percentage">95%</span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

        <div class="skills_data">
            <div class="skills_names">
                <i class='bx bxl-css3 skills__icon'></i>
                <span class="skills_name">CSS3</span>
            </div>
            <div>
                <span class="skills_percentage">85%</span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

           <div class="skills_data">
               <div class="skills_names">
                <i class='bx bxl-javascript skills__icon' ></i>
                   <span class="skills_name">JavaScript</span>
               </div>
               <div>
                   
                   <span class="skills_percentage">75%</span>
               </div>
               <div class="skills_bar skills_javascript">

               </div>
           </div>

        <div class="skills_data">
            <div class="skills_names">
                <i class='bx bxl-java skills__icon'></i>
                <span class="skills_name">Java</span>
            </div>
            <div>
                <span class="skills_percentage">75%</span>
            </div>
            <div class="skills_bar skills_java">
                
            </div>
        </div>

        <div class="skills_data">
            <div class="skills_names">
                <i class='bx bxl-postgresql skills__icon' ></i>
                <span class="skills_name">SQL</span>
            </div>
            <div>
                <span class="skills_percentage">50%</span>
            </div>
            <div class="skills_bar skills_sql">
                
            </div>
        </div>

        <div class="skills_data">
            <div class="skills_names">
                <i class='bx bxl-postgresql skills__icon' ></i>
                <span class="skills_name">SQL</span>
            </div>
            <div>
                <span class="skills_percentage">50%</span>
            </div>
            <div class="skills_bar skills_sql">
                
            </div>
        </div>

      

       
        
        </div>
        <div>
            <img src="development-cycle.webp" alt="" class="skills_img">
        </div>
        </div>
    </section> -->


    <!-- <section class="work section" id="work">
        <h2 class="section-title">Project Work88888888888888888888888888888888</h2>

        <div class="work__container bd-grid">
               <div class="skills_data">
            <div class="skills_names">
                <i class='bx bx-list-ul skills__icon'></i>
                <span class="skills_name"><a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/New%20folder%20(12)/tolist.html " class="anchor">To-DO List</a></span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

        <div class="skills_data">
            <div class="skills_names">
                <i class='bx bx-calculator skills__icon'></i>
                <span class="skills_name "><a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/New%20folder%20(12)/JS%20Cal.html" class="anchor">JavaScript Calculator</a>   </span>
            </div>
            <div class="skills_bar skills_css1">
                
            </div>
        </div>

           <div class="skills_data">
               <div class="skills_names">
                <i class='bx bxs-card skills__icon'></i>
                   <span class="skills_name "><a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/Memory-Game.html" class="anchor">Memory Card Game</a>  </span>
               </div>
               <div class="skills_bar skills_javascript1">

               </div>
           </div>
              <div class="skills_data">
            <div class="skills_names">
               <i class='bx bx-sun skills__icon' ></i>
                <span class="skills_name "> <a href="file:///C:/Users/Parvez%20Khan/Desktop/html2/Weather%20App/Weather.html" class="anchor">Weather App</a> </span>
            </div>
            <div class="skills_bar skills_html1">
                
            </div>
        </div>

</div>
    </section> -->






   


    <section class="contact section" id="contact">
        <h2 class="section-title">Contact</h2>

        <div class="contact__container bd-grid">
            <form action="" class="contact__form">
                <input type="text" placeholder="Name" class="contact__input">
                <input type="mail" placeholder="Email" class="contact__input">
                <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                <input type="button" value="Enter" class="contact__button button">
            </form>
        </div>
    </section>


    <footer class="footer">
        <p class="footer__title">Parvez</p>
        <div class="footer__social">
            <a href="#" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
            <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
            <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
        </div>
        <p class="footer__copy">&#169; All rigths reserved</p>
    </footer>
</main>

<script src="https://unpkg.com/scrollreveal"></script>
<script src="j2.js">

</script>
</body>
</html>
