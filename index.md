<html>
  
  <head>
    
    <script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

    <link href="https://fonts.googleapis.com/css2?family=Poppins&family=Roboto+Slab&display=swap" rel="stylesheet">
    
    <script src="https://kit.fontawesome.com/6ad04e0410.js" crossorigin="anonymous"></script>
    
    <style>
    
    /* Custom properties/variables  */

:root {
    --melon: #FFA69E;
    --eggshell: #FFFFFF;
    --aero-blue: #B8F2E6;
    --powder-blue: #AED9E0;
    --black-coral: #5E6472;
}
/* Base reset */

* {
    margin: 0;
    padding: 0;
}

/* Box sizing */

*,
*::before,
*::after {
   box-sizing: inherit;
}
  
html {
    box-sizing: border-box;
    scroll-behavior: smooth; 
}

/* Base styles */

body {
  font-family: 'Roboto Slab', serif;
  font-size: 1.6rem;
  font-weight: 400;
  line-height: 1.5;
  text-align: center;
  color: var(--eggshell);
}

/* Scrollbar styling */ 

/* width */
::-webkit-scrollbar {
    width: 15px;
}

/* Track */
::-webkit-scrollbar-track { 
    background-color: var(--white);
    border-radius: 5px;
}
 
/* Handle */
::-webkit-scrollbar-thumb {
    background-color: var(--black-coral); 
    border-radius: 10px;
}
   
/* Navigation bar*/

#navbar {
  display: flex;
  justify-content: flex-end;
  position: fixed;
  top: 0;
  width: 100%;
  background-color: var(--eggshell);
  box-shadow: 2px 2px 5px var(--black-coral);
}

@media (max-width: 420px) {
  #navbar {
    justify-content: center;
    flex-wrap: wrap;
    font-size: 90%; }
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

#nav-list {
  display: flex;
  margin-right: 1.2rem;
}

.nav-link {
  display: block;
  padding: 0.8rem;
  color: var(--black-coral);
}

.nav-link:hover,:focus {
  color: var(--eggshell);
  background-color: var(--black-coral);
}

@media (max-width: 420px) {
  #nav-list {
    margin: 0; }
}

#welcome-section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: var(--melon);
}

#welcome-section > h1 {
  padding: 20px;
  font-size: 2.8rem;
  font-weight: 700;
}

#welcome-section > p {
  margin: 10px;
  padding: 15px;
  font-size: 1.4rem;
  font-family: 'Poppins', sans-serif;
  font-weight: 200;
  font-style: italic;
}

.profile-icon {
  color: var(--black-coral);
  padding: 10px;
  border: 2px solid;
  border-radius: 15px;
  background-color: var(--eggshell);
}

.profile-icon:hover {
  transform: scale(1.1);
  transition: 0.5s;
}

#profile-link {
  color: var(--black-coral);
  font-size: 1.5rem;
  font-family: 'Roboto Slab', serif;
}

#projects {
  padding: 30px;
  background-color: var(--black-coral);
}

#projects > h1 {
  max-width: 600px;
  margin: 0 auto 2rem auto;
  font-size: 2.4rem;
  border-bottom: 0.2rem solid var(--eggshell);
}

#projects-container {
  width: 100%;
  display: grid;
  justify-content: center;
  grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
}

.project-tile {
  margin: 20px;
  background-color: var(--eggshell);
}
    
    </style>
    
  </head>
  
  <body>

    <!-- START Navigation bar -->
    
      <nav id="navbar">
        
        <ul id="nav-list">
          <li><a class="nav-link" href="#welcome-section">About</a></li>
          <li><a class="nav-link" href="#projects">Projects</a></li>
          <li><a class="nav-link" href="#contact">Contact</a></li>
        </ul>
        
      </nav>
    <!-- END Navigation bar -->
    
    <!-- START Welcome Section -->
    <section id="welcome-section">
      
      <h1>Hey, I'm Imene AGAL !</h1>
      
      <i class="profile-icon fab fa-free-code-camp"><a id="profile-link" href="https://www.freecodecamp.org/notice_me_kohai" target="_blank"> &#64;Notice_Me_Kohai</a></i>
      
      <p>- A weeb, self-taught web developer based in </br> Algiers, Algeria and currently learning HTML & CSS. -</p>
      
    </section>
    <!-- END Welcome Section -->

    <!-- START Projects Section-->
    <section id="projects">
  
      <h1>Here are some of my projects..</h1>
      
      <div id="projects-container">
        
        <div class="project-tile">
          <img src="" alt="">
        </div>
        <div class="project-tile"></div>
        <div class="project-tile"></div>
        <div class="project-tile"></div>
        <div class="project-tile"></div>
        <div class="project-tile"></div>
        
      </div>
      
    </section>
    <!-- END Projects Section-->

  </body>
  
</html>
