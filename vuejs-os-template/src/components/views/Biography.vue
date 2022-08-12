<template>

<div>
    <h1 class="header">Sebastian Metellus</h1>
    
    <h4 class="sub-header" style ="padding-bottom: 8px;">Full Stack Developer | Graphic Designer | Ultimate Frisbee Player</h4>
    
    <h4 class="location">Pembroke Pines 📍</h4>

    <div class = "badges">
        <img class="badge" alt="Python" src="https://img.shields.io/badge/-Python-blue" />
        <img class="badge" alt="JavaScript" src="https://img.shields.io/badge/-Javascript-yellow" /> 
        <img class="badge" alt="HTML/CSS" src="https://img.shields.io/badge/-HTML%2FCSS-yellowgreen" />
        <img class="badge" alt="C++" src="https://img.shields.io/badge/-C++-orange" />
        <img class="badge" alt="Git" src="https://img.shields.io/badge/-Git-critical" />
        <img class="badge" alt="Figma" src="https://img.shields.io/badge/-Figma-8c5aee" />
</div>

<div class="body-content">
    <h2 class="heading"><b>About</b></h2>
    
    <p class="paragraph">Hello! I am Sebastian from Pembroke Pines and I am an 20 year old student who's passionate in both
        programming and graphic design. I am currently a Computer Science student at Florida State University.</p><br>
    
    <p class="paragraph">The main technology I have been using is C++. However recently, I fell in love with HTML / CSS and I
        use it to fuel my passion for design. Morever, I also have interests in Cloud Technology and Big Data.</p><br>
    
    <p class="paragraph">When I am not in front of the computer, I usually draw, cook, and play ultimate frisbee on the weekends with friends
        (my favorite throw is the forehand).
    </p>
    </div>

<div class="body-content">
    <h2 class="heading"><b>Work Experience</b></h2>
    
    <p class="paragraph">I have completed two internship opportunities so far. My first internship was at Takeoff Institute, a fellowship research program for Black undergraduate
        students. The second internship was at KPMG US LLP where I rotated through various Engineeering / IT teams in the firm.</p><br>
    
    <p class="paragraph">Throughout these experiences, I worked with Python, Alteryx, and KPMG Clara. For my first internship, I created a case analysis on the importance of financial literacy in underrepresented communities. 
        In my second internship, I created python scripts to assist with data visualization and updated project 
        databases through streamlining Alteryx and KPMG Clara. 
    </p><br>
    </div>

    <div class="body-content">
        <h3 class="heading"><b>Resume</b></h3>
        <a style="color: #FF5733;" href="/files/Metellus, Sebastian - Resume.pdf" target="_blank" class="paragraph">Check out my resume.</a>
    </div>

</div>

</template>

<style scoped>

/*-------------------------------------------*\
    CSS Normalisation 
\*-------------------------------------------*/

.sub-header{
    color: grey;
    font-family: "MS Sans Serif";
    font-size: 12px;
}

.paragraph
{
    font-weight: 200;
}

.body-content {
    padding-top: 30px;
}

.location{
    color: grey;
    font-size: 12px;
}

.header{
    padding-top: 20px;
    padding-bottom: 10px;
}
.heading {
    padding-bottom: 5px;
}

.badges{
    display: table;
    align-items: center;
    margin-top: 20px;
}
.badge {
    width: auto;
    height: 20px;
    border-radius: 0px;
    font-size: 12px;
    padding-right: 10px;
    /* box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.12), 0 6px 20px 0 rgba(0, 0, 0, 0.1); */
}

p {
    margin: 0;
    padding: 0;
}
</style>
