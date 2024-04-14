<style>
  
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;800&display=swap');
    
    #PopularPosts1,
    #footer, 
    .page header,
    #comments,
    .post-share-buttons,
    h3.post-title, 
    .bg-photo-container,
    .bg-photo-overlay,
    .centered-top-container,
    .collapsed-header .centered-top-placeholder {
        display: none;
    }
    
    
    .post-body {
        color: #000;
      margin: 0;
      font-family: "Poppins", sans-serif;
    }
    
    .post-body img { height: unset; }
    
    .post-body h3 { color: #000; }
    
    footer h3 { color: #fff; }
    
    .Blog .blog-posts .post-outer-container .post-outer {
         padding-bottom: 0; 
    }
    
    .Blog .blog-posts .post-outer-container,
    .centered-bottom { 
        padding: 0;
    }
    
    .page_body .widget {
        margin-bottom: 0;
    }
    
    .page_body .centered {
        padding: 0;
      max-width: unset;
    }
    
    @media screen and (max-width: 800px) {
      div.widget.Blog .blog-posts .post-outer-container {
          padding: 0;
      }
    }
    
    nav a:hover {
        color: #000;
    }
    
    a:visited {
        color: #000;
    }
    
    .buttons a:visited,
    footer a:visited {
        color: #fff;
    }
    
    .post-body footer h3 {color: #fff;}
    
    
    
    /* Custom Styles */
    
    * {
    box-sizing: border-box;
  }
  
  html {
    scroll-behavior: smooth;
  }
  
  body {
    margin: 0;
    font-family: "Poppins", sans-serif;
    background: #f5f4f4;
  }
  
  p {
    line-height: 180%;
    font-size: 16px;
  }
  
  a {
    text-decoration: none;
    color: #000;
  }
  
  nav {
    position: fixed;
    top: 30px;
    background: linear-gradient(
      90deg,
      rgba(255, 255, 255, 0.9) 0%,
      rgba(255, 254, 254, 0.4) 100%
    );
    backdrop-filter: blur(10px);
    width: 900px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 12px 32px;
    border-radius: 24px;
    box-shadow: 0 4px 50px -8px rgba(0, 0, 0, 0.2);
    z-index: 300;
  }
  
  nav .logo {
    font-weight: bold;
    font-size: 18px;
    color: #8300b6;
  }
  
  nav .nav-items {
    display: flex;
    gap: 50px;
  }
  
  .custom-container {
    max-width: 900px;
    margin-inline: auto;
  }
  
  /* Header */
  
  header.custom-header {
    height: 100vh;
    min-height: 600px;
    max-height: 800px;
    background: linear-gradient(90deg, #c2cefe 0%, #f7a3fe 100%);
    display: block;
  }
  
  header.custom-header .custom-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
  }
  
  header.custom-header .left {
    max-width: 500px;
  }
  
  h1 {
    font-size: 50px;
    line-height: 130%;
    margin: 0;
    background: linear-gradient(90deg, #230127 0%, #9e08fb 100%);
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
  }
  
  header.custom-header .left p {
    background: linear-gradient(90deg, #080022 0%, #8300b6 100%);
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    background-clip: text;
    line-height: 200%;
  }
  
  .buttons {
    display: flex;
    gap: 24px;
    width: 100%;
  }
  
  .download-btn {
    background: #000;
    color: #fff;
    display: flex;
    align-items: center;
    gap: 16px;
    padding: 8px 16px;
    border-radius: 10px;
    font-size: 14px;
    width: 250px;
    
  }
  
  .download-btn .btn-icon img {
    height: 36px;
    display: flex;
  }
  
  .download-btn .btn-text div:first-child {
    text-transform: uppercase;
  }
  
  .download-btn .btn-text div:last-child {
    font-weight: bold;
  }
  
  header.custom-header .right img {
    height: 460px;
    display: flex;
  }
  
  /* Featured Section */
  
  section {
    padding: 50px 32px;
  }
  
  section h2 {
    color: #8300b6;
    text-align: center;
    margin: 0;
    margin-bottom: 16px;
  }
  
  #featured {
    background: #fff;
    box-shadow: 0 5px 55px -15px rgba(0, 0, 0, 0.2);
    border-radius: 10px;
    padding-top: 30px;
    margin-top: -90px;
  }
  
  #featured .logos {
    display: flex;
    gap: 60px;
    justify-content: center;
  }
  
  /* Features */
  
  #features .feature-card {
    background: linear-gradient(90deg, #ebfefe 0%, #eafef3 100%);
    border-radius: 20px;
    padding: 24px;
  }
  
  #features h3 {
    font-size: 18px;
  }
  
  #features .icon {
    height: 60px;
    width: 60px;
    border-radius: 10px;
    background: linear-gradient(90deg, white 0%, white 100%);
    display: grid;
    place-items: center;
  }
  
  #features .content {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 24px;
  }
  
  /* Testimonials Section */
  
  #testimonials .content {
    display: flex;
    justify-content: space-between;
    gap: 80px;
  }
  
  #testimonials .left {
    width: 360px;
  }
  
  #testimonials .right {
    flex: 1;
    position: relative;
  }
  
  #testimonials .left h2 {
    text-align: left;
    color: #000;
  }
  
  #testimonials .quote-icon {
    position: absolute;
    top: -20px;
    left: -50px;
    opacity: 0.3;
  }
  
  #testimonials .quote-icon img {
    height: 60px;
  }
  
  #testimonials .reviewer-info {
    display: flex;
    align-items: center;
    gap: 16px;
  }
  
  #testimonials .reviewer-info img {
    height: 60px;
  }
  
  #testimonials .reviewer-info .name {
    font-weight: bold;
  }
  
  #testimonials .reviewer-info .designation {
    font-size: 14px;
  }
  
  #testimonials {
    position: relative;
  }
  
  .bg-element {
    position: absolute;
    height: 760px;
    left: -50px;
    right: -50px;
    bottom: 0;
    background: linear-gradient(90deg, #fdd7e8 0%, #fee5fa 100%);
    z-index: -1;
  }
  
  #testimonials .navigation-btns {
    position: absolute;
    right: 20px;
    bottom: 40px;
    display: flex;
    gap: 2px;
  }
  
  #testimonials .navigation-btns img {
    height: 26px;
  }
  
  #testimonials .prev-btn,
  #testimonials .next-btn {
    background: #fff;
    display: flex;
    cursor: pointer;
    opacity: 0.7;
  }
  
  #testimonials .prev-btn:hover,
  #testimonials .next-btn:hover {
    opacity: 1;
  }
  
  #testimonials .testimonial-card {
    opacity: 0;
    transition: all 300ms ease;
  }
  
  #testimonials .testimonial-card.active {
    opacity: 1;
  }
  
  /* Pricing Section */
  
  #pricing .content {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 20px;
  }
  
  #pricing .plan {
    background: #fff;
    border-radius: 10px;
    padding: 24px;
  }
  
  #pricing ul {
    list-style: none;
    padding: 0;
  }
  
  #pricing ul li {
    margin: 16px 0;
    line-height: 1.8;
  }
  
  #pricing .plan-name {
    font-size: 30px;
    margin: 0;
  }
  
  #pricing .plan-price {
    font-size: 20px;
    font-weight: bold;
  }
  
  #pricing .btn {
    background: #000;
    color: #fff;
    padding: 8px 32px;
    width: 100%;
    margin-top: 24px;
    display: inline-block;
    border-radius: 10px;
    transition: all 200ms ease;
  }
  
  #pricing .btn:hover {
    transform: scale(1.03);
  }
  
  #pricing ul li .icon {
    margin-right: 10px;
  }
  
  /* CTA */
  
  #cta .content {
    max-width: 600px;
    display: flex;
    align-items: center;
    flex-direction: column;
    margin: 0 auto;
    padding-bottom: 32px;
  }
  
  #cta .content p {
    text-align: center;
    margin-top: -8px;
    margin-bottom: 32px;
  }
  
  /* Footer */
  
  footer {
    background: linear-gradient(90deg, #0a1300 0%, #001e0f 100%);
    color: #fff;
    padding-top: 50px;
  }
  
  footer a {
    color: #fff;
  }
  
  footer .content {
    display: flex;
    justify-content: space-between;
  }
  
  footer .logo {
    font-size: 24px;
    font-weight: bold;
  }
  
  footer .left p {
    margin-top: 0;
  }
  
  footer .right {
    display: flex;
    gap: 40px;
  }
  
  footer h3 {
    margin-top: 0;
  }
  
  footer ul {
    list-style: none;
    padding: 0;
    margin-bottom: 40px;
  }
  
  footer ul li {
    margin: 8px 0;
  }
  
  footer .copyright {
    border-top: 1px solid rgba(255, 255, 255, 0.4);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 0;
  }
  
  footer .socials {
    display: flex;
    gap: 40px;
  }
  
  footer .socials img {
    height: 40px;
  }
  
  /* Hidden Items  */
  
  nav .menu-icon,
  .mobile-nav-menu {
    display: none;
  }
  
  @media (max-width: 600px) {
    section {
      padding-inline: 0;
    }
  
    nav .nav-items {
      display: none;
    }
  
    body {
      background: #fff;
    }
  
    nav {
      width: calc(100% - 30px);
    }
  
    nav .menu-icon {
      display: block;
      cursor: pointer;
    }
  
    nav .menu-icon img {
      height: 30px;
      display: flex;
    }
  
    header.custom-header .custom-container {
      flex-direction: column;
    }
  
    header.custom-header {
      max-height: fit-content;
      height: fit-content;
      padding-top: 160px;
    }
  
    header.custom-header .right img {
      height: 350px;
    }
  
    .custom-container {
      padding: 0 32px;
    }
  
    h1 {
      font-size: 40px;
    }
  
    .buttons {
      flex-direction: column;
    }
  
    section h2 {
      position: relative;
      margin-bottom: 40px;
    }
  
    section h2::after {
      content: "";
      position: absolute;
      background: #000;
      width: 30px;
      height: 2px;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
    }
  
    /* Featured section */
  
    #featured {
      margin-top: 40px;
    }
  
    #featured .logos {
      flex-direction: column;
      gap: 40px;
    }
  
    #featured img {
      height: 30px;
    }
  
    /* Features section */
  
    #features .content {
      grid-template-columns: 1fr;
    }
  
    /* Testimonials */
  
    #testimonials .content {
      flex-direction: column;
    }
  
    #testimonials .content .left {
      width: 100%;
    }
  
    #testimonials .left h2::after {
      left: 0;
      transform: translateX(0);
    }
  
    #testimonials .left h2 {
      margin-bottom: 0;
    }
  
    #testimonials .right .quote-icon {
      left: -10px;
    }
  
    .bg-element {
      position: absolute;
      height: 1900px;
      left: -30px;
      right: -30px;
    }
  
    /* Pricing Section */
  
    #pricing .content {
      grid-template-columns: 1fr;
    }
  
    #pricing .plan {
      padding-inline: 0;
    }
  
    /* Footer */
  
    footer .content {
      flex-direction: column;
    }
  
    footer .right {
      flex-direction: column;
      gap: 10px;
      margin-top: 20px;
    }
  
    footer .copyright {
      flex-direction: column;
    }
  
    /* Mobile nav menu */
  
    .mobile-nav-menu {
      position: fixed;
      right: 32px;
      top: 100px;
      background: #fff;
      display: flex;
      flex-direction: column;
      padding: 8px 16px;
      gap: 16px;
      font-size: 16px;
      border-radius: 10px;
      box-shadow: 0 4px 40px -8px rgba(0, 0, 0, 0.2);
      opacity: 0;
      z-index: 600;
      pointer-events: none;
      transform: translateY(-10px);
      transition: all 300ms ease;
    }
  
    .mobile-nav-menu.active {
      opacity: 1;
      pointer-events: auto;
      transform: translateY(0);
    }
    
     /* Blog section */
  
    #blog .latest-posts-list {
      flex-direction: column;
    }
  }
    
  /* Blog section */
  
  #blog .latest-posts-list {
    display: flex;
    gap: 24px;
  }
  
  #blog .post img {
    max-height: 200px;
    width: 100%;
    object-fit: cover;
    border-radius: 8px;
  }
  
  #blog .post {
    flex: 1;
    background: #fff;
    padding: 16px;
    border-radius: 8px;
    box-shadow: 4px 0 40px -8px rgba(0, 0, 0, 0.2);
    line-height: 200%;
    display: flex;
    flex-direction: column;
    transition: all 300ms ease;
  }
  
  #blog .thumbnail {
    margin: -16px;
    margin-bottom: 0;
  }
  
  #blog .post .title {
    font-size: 24px;
    line-height: 150%;
    margin: 8px 0;
  }
  
  #blog .post .summary {
    max-height: 95px;
    overflow: hidden;
    position: relative;
  }
  
  #blog .post .summary::after {
    position: absolute;
    content: "";
    bottom: 0;
    left: 0;
    width: 100%;
    height: 60px;
    background: linear-gradient(transparent 0%, #fff 85%);
  }
  
  #blog .post .read-more-btn {
    font-weight: bold;
    color: blue;
    align-self: flex-end;
  }
  
  #blog .post:hover {
    transform: scale(1.03);
  }
  
  
    
    
    
  </style>
  
  
  <nav>
        <a class="logo" href="#home">info@Chamod</a>
        <div class="nav-items">
          <a class="nav-link" href="#home">Home</a>
          <a class="nav-link" href="#features">Certificates</a>
          <a class="nav-link" href="#cta">Contact Me</a>
        </div>
  
        <div class="menu-icon">
          <img alt="" src="#" />
        </div>
      </nav>
  
      <div class="mobile-nav-menu">
        <a class="nav-link" href="#home">Home</a>
        <a class="nav-link" href="#features">Certificates</a>
        <a class="nav-link" href="#cta">Contact Me</a>        
      </div>
  
      <header class="custom-header" id="home">

        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha384-r3ncw56UE01rkZKmMKF3iVqNzIIZbC8ojzxzIirnYPFgZfdSZfF56vb9RiErLv+7" crossorigin="anonymous">

        <div class="custom-container">
          <div class="">
            <h1>Creatavity Make Creative Background </h1>
            <p>
                I am a passionate and skilled web developer with expertise in both
                 front-end and back-end technologies. With a solid foundation in HTML,
                  CSS, and JavaScript, coupled with backend proficiency in PHP, I specialize
                   in crafting seamless and functional web experiences. 
            </p>
  
            <div class="buttons" >
              <a class="download-btn" href="#">
                <div class="btn-icon">
                  <img alt="" src="m1.jpg" />
                </div>
                <div class="btn-text">
                  <div>Certified By</div>
                  <div>Google IT-Specelist <br> ( Profetional )</div>
                </div>
              </a>
  
              <a class="download-btn" href="#">
                <div class="btn-icon">
                  <img alt="" src="sk4.jpg" />
                </div>
                <div class="btn-text">
                  <div>Certified By</div>
                  <div>IBM z/OS Mainframe <br>( Specialization )</div>
                </div>
              </a>
            </div>    


          </div>
          
          <div class="right" style="margin:0%;">
            <img alt="" src="q.png" />
            
          </div>
        
          </div>
  
        
        </div>
      </header>

      <script src="https://platform.linkedin.com/badges/js/profile.js" async defer type="text/javascript"></script>

      <div class="custom-container">
        <section id="featured">
          <h2>TOP SKILLS FOR</h2>
          <div class="content">
            <div class="logos" >
              <img alt="" src="html.png" style="width: 35px;" />
              <img alt="" src="css-3.png" style="width: 35px;"/>
              <img alt="" src="js.png" style="width: 35px;"/>
              <img alt="" src="bootstrap.png"style="width: 35px;" />
              <img alt="" src="sql-server.png" style="width: 35px;"/>
              <img alt="" src="github.png" style="width: 35px;"/>
              <img alt="" src="php.png" style="width: 35px;"/>
              <img alt="" src="wordpress.png" style="width: 35px;"/>
            </div>
          </div>
        </section>
  
        <section id="features">
          <h2> Completed Certificates</h2>
          <div class="content">
            <!--<div class="feature-card">
              <div class="icon">
                <img src="images/create-task-icon.svg" alt="" />
              </div>
              <h3>Intuitive Task Creation</h3>
              <p>
                Easily create and manage tasks with a simple and user-friendly
                interface.
              </p>
            </div>-->
          </div>
        </section>
  
        <section id="testimonials">
          <div class="content">
            <div class="left">
              <h2>Why Do You Want Hire Me?</h2>
              <p style="text-align:left;"> With a diverse skill set spanning front-end and back-end development, coupled with certifications from Google and IBM, I bring a comprehensive approach to web development and digital marketing.</p>
            </div>
  
            <div class="right">
              <div class="testimonial-card">
                <span class="quote-icon">
               
                </span>
  
                <p class="review">
                    Whether it's creating dynamic websites, optimizing online presence, or 
                    driving growth through targeted advertising campaigns, I'm equipped to deliver results.
                </p>
  
                <div class="reviewer-info">
                  <div class="image">
                
                  </div>
  
                  <div class="details">
                    <div class="name"></div>
                    <div class="designation"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
  
        
  
          <span class="bg-element"></span>
        </section>
  
        <!-- <section id="pricing">
          <h2>Flexible Pricing Options</h2>
          <div class="content">
           <div class="plan">
              <h4 class="plan-name">Basic</h4>
              <ul class="plan-features">
                <li>50 Tasks</li>
                <li>Deadline Tracking</li>
                <li>Priority Settings</li>
                <li>Basic Reporting</li>
                <li>Email Notifications</li>
                <li>24/7 Customer Support</li>
              </ul>
              <div class="plan-price">Free</div>
              <a href="#" class="btn">Choose</a>
            </div>
          </div>
        </section>-->
  
        <section id="cta">
          <h2>Get Started Today</h2>
          <div class="content">
            <p>
              Take control of your tasks and boost your productivity. Get started
              today and experience the power of efficient task management
            </p>

            <div class="badge-base LI-profile-badge" data-locale="en_US" data-size="large" data-theme="light" data-type="HORIZONTAL" data-vanity="chamoddayashan" data-version="v1"><a class="badge-base__link LI-simple-link" href="https://lk.linkedin.com/in/chamoddayashan?trk=profile-badge">Chamod Dayashan</a></div>
              
  
            <i class="fa-brands fa-whatsapp"> name</i>




          </div>
        </section>
        
         <!--  
        <section id="blog">
          <h2>Latest Blog Posts</h2>
  
          <div class="latest-posts-list">
            
          </div>
        </section>
        -->
      </div>
  
      <footer>
        <div class="custom-container">
          <div class="content">
            <div class="left">
              <div class="logo">info.Chamod</div>
              <p>Best Task Management App</p>
            </div>
  
            <div class="right">
              <div class="links">
                <h3>Quick Links</h3>
                <ul>
                  <li>
                    <a href="#">About Us</a>
                  </li>
  
                  <li>
                    <a href="#">Privacy Policy</a>
                  </li>
  
                  <li>
                    <a href="#">Terms &amp; Conditions</a>
                  </li>
                </ul>
              </div>
  
              <div class="links">
                <h3>Contact Me</h3>
                <ul>
                  <li>+94 76 61 26 630</li>
                  <li>info@chamod.com</li>
                  <li>Colombo 10</li>
                </ul>
              </div>
            </div>
          </div>
  
          <div class="copyright">
            <p>Designed & Devolopmet By Chamod Dayashan © 2023</p>
            <div class="socials">
              <a href="#"><img alt="" src="#" /></a>
              <a href="#"><img alt="" src="#" /></a>
              <a href="#"><img alt="" src="#" /></a>
            </div>
          </div>
        </div>
      </footer>
  
  
  
  
  <script>
    
    
    
    const featuresList = [
    {
      icon: "sk1.png",
      title: "Google Ads App Certified",
      description:
        "Creating and optimizing Google App campaigns.<br/><br/>Completion ID: 99583840<br/><strong><a href=\"https://skillshop.credential.net/4d2ddae4-e369-465e-ba01-c001aeded833\">Credential Verification</a></strong>",
      width: "55px" 
    },
 
    {
      icon: "sk2.png",
      title: "Google Analytics Certified",
      description:
        "Creating and optimizing Google App campaigns.<br/><br/>Completion ID: 99631050<br/><strong><a href=\"https://skillshop.credential.net/f90d6340-d0df-4d7f-9c5d-61cf5fa2f976\">Credential Verification</a></strong>",
      width: "55px" 
    },
  
    {
        icon: "sk3.png",
      title: "Creative Certification Exam",
      description:
        "Creating and optimizing Google App campaigns.<br/><br/>Completion ID: 277231612<br/><strong><a href=\"https://skillshop.exceedlms.com/student/award/WiycNhTMGqVpcCfwJoc2qofX\">Credential Verification</a></strong>",
      width: "55px" 
    },
  
    {   icon: "sk4.jpg",
      title: "Front-End and Web Development",
      description:
        "Creating and optimizing Google App campaigns.<br/><br/>Completion ID: 277231612<br/><strong><a href=\"https://www.coursera.org/account/accomplishments/verify/F2C6S7TUNR96\">Credential Verification</a></strong>",
      width: "55px" 
    },

    {
        icon: "sk4.jpg",
      title: "Python for Data Science, AI & Development",
      description:
        "Creating and optimizing Google App campaigns.<br/><br/>Completion ID: 277231612<br/><strong><a href=\"https://www.coursera.org/account/accomplishments/verify/UGR2MNCZ3VGF\">Credential Verification</a></strong>",
      width: "55px" 
    },
  
    {
        icon: "sk5.jpg",
      title: "Digital Skills: Artificial Intelligence",
      description:
        "Creating and optimizing Google App campaigns.<br/><br/>Completion ID: dqub0qw<br/><strong><a href=\"https://www.futurelearn.com/certificates/dqub0qw\">Credential Verification</a></strong>",
      width: "55px" 
    },
  ];
  
  const testimonialsList = [
    {
      review:
        " Whether it's creating dynamic websites, optimizing online presence or driving growth through targeted advertising campaigns I'm equipped to deliver results.",
      image: "my1.png",
      name: "Software Eng: Chamod Dayashan",
      designation: "IBM/Google Profecinal Certified",
    },
   
  ];
  
  const plans = [
    {
      name: "Basic",
      features: [
        "50 Tasks",
        "Deadline Tracking",
        "Priority Settings",
        "Basic Reporting",
        "Email Notifications",
        "24/7 Customer Support",
      ],
      price: "Free",
      link: "#",
    },
  
    {
      name: "Pro",
      features: [
        "All from <strong>Basic</strong> plan",
        "Advanced Tasks",
        "Subtasks",
        "File Attachments",
        "Gantt Chart View",
        "Collaborations",
      ],
      price: "$29.99",
      link: "#",
    },
  
    {
      name: "Enterprise",
      features: [
        "All from <strong>Pro</strong> plan",
        "Custom Branding",
        "API Access",
        "Data Export",
        "Advanced Security",
        "Custom Integrations",
      ],
      price: "Contact for pricing",
      link: "#",
    },
  ];
  
  const featuresContent = document.querySelector("#features .content");
  const testimonialCard = document.querySelector(
    "#testimonials .testimonial-card"
  );
  const prevBtn = document.querySelector("#testimonials .prev-btn");
  const nextBtn = document.querySelector("#testimonials .next-btn");
  const pricingContent = document.querySelector("#pricing .content");
  const menuIcon = document.querySelector(".menu-icon");
  const mobileNavMenu = document.querySelector(".mobile-nav-menu");
  const navLinks = document.querySelectorAll(".nav-link");
  let currentTestimonialIndex = 0;
  
  const displayFeatures = () => {
    featuresList.forEach((f) => {
        const html = `<div class="icon">
            <img src="${f.icon}" alt="" style="width: ${f.width}" />
          </div>
          <h3>${f.title}</h3>
          <p>
            ${f.description}
          </p>`;

        const featureCard = document.createElement("div");
        featureCard.classList.add("feature-card");
        featureCard.innerHTML = html;

        featuresContent.appendChild(featureCard);
    });
};

  
  displayFeatures();
  
  const displayTestimonial = () => {
    const html = `<span class="quote-icon">
    <img src="#" alt="" />
  </span>
  
  <p class="review">
   ${testimonialsList[currentTestimonialIndex].review}
  </p>
  
  <div class="reviewer-info">
    <div class="image">
      <img src="${testimonialsList[currentTestimonialIndex].image}" alt="" />
    </div>
  
    <div class="details">
      <div class="name">${testimonialsList[currentTestimonialIndex].name}</div>
      <div class="designation">${testimonialsList[currentTestimonialIndex].designation}</div>
    </div>
  </div>`;
  
    testimonialCard.innerHTML = html;
    testimonialCard.classList.add("active");
  };
  
  displayTestimonial();
  
  nextBtn.addEventListener("click", () => {
    testimonialCard.classList.remove("active");
  
    setTimeout(() => {
      currentTestimonialIndex++;
      if (currentTestimonialIndex >= testimonialsList.length) {
        currentTestimonialIndex = 0;
      }
      displayTestimonial();
    }, 200);
  });
  
  prevBtn.addEventListener("click", () => {
    testimonialCard.classList.remove("active");
  
    setTimeout(() => {
      currentTestimonialIndex--;
      if (currentTestimonialIndex < 0) {
        currentTestimonialIndex = testimonialsList.length - 1;
      }
      displayTestimonial();
    }, 200);
  });
  
  const displayPricing = () => {
    plans.forEach((p) => {
      const featuresHTML = p.features
        .map(
          (f) =>
            `<li><span class='icon'><img src='#'/></span>${f}</li>`
        )
        .join("");
  
      const html = `<h4 class="plan-name">${p.name}</h4>
      <ul class="plan-features">
        ${featuresHTML}
      </ul>
      <div class="plan-price">${p.price}</div>
      <a href="${p.link}" class="btn">Choose</a>`;
  
      const plan = document.createElement("div");
      plan.classList.add("plan");
      plan.innerHTML = html;
  
      pricingContent.appendChild(plan);
    });
  };
  
  displayPricing();
  
  menuIcon.addEventListener("click", () => {
    mobileNavMenu.classList.toggle("active");
  });
  
  navLinks.forEach((link) => {
    link.addEventListener("click", (e) => {
      e.preventDefault();
      const targetId = link.getAttribute("href");
      const targetElement = document.querySelector(targetId);
  
      if (targetElement) {
        const offset = targetElement.offsetTop - 60;
        window.scrollTo({ top: offset });
      }
  
      mobileNavMenu.classList.remove("active");
    });
  });
    
  const latestPostsList = document.querySelector('#blog .latest-posts-list');
  
  const generateLatestPosts = (posts) => {
      posts.forEach(post => {
          const title = post.title.$t;
            const defaultThumbnail = '#';
            const thumbnailSrc = post.media$thumbnail ? post.media$thumbnail.url.replace('/s72', '/s300') : defaultThumbnail;
            const summary = post.summary.$t;
            const link = post.link[post.link.length - 1].href;
        
        const html = `<div class="thumbnail">
                <a href="${link}">
                  <img
                    src="${thumbnailSrc}"
                    alt=""
                  />
                </a>
              </div>
  
              <a href="${link}">
                <h3 class="title">${title}</h3>
              </a>
              <div class="summary">
                ${summary}
              </div>
  
              <a href="${link}" class="read-more-btn">Read more</a>`;
        
            const postDiv = document.createElement('div');
            postDiv.classList.add('post');
            
            postDiv.innerHTML = html;
            latestPostsList.appendChild(postDiv);
     }); 
  }  
  
    
  const handleLatestPosts = (posts) => {
        generateLatestPosts(posts.feed.entry);
  }
  
    
  </script>
  
  <script src='/feeds/posts/summary?alt=json-in-script&callback=handleLatestPosts&max-results=2'></script>
  
