<template>
  <div id="app" class="full-width">
    <div class="home-page-container">
    <div class="home-page-home-page">

      
      <div class="image1">
        <img src="@/assets/img1.png" alt="" />
      </div>

      <div class="image2">
        <img src="@/assets/Frame 8.png" alt="" />
      </div>



      <div class="h1_buttons_Container"> 
        <div class="h1-position">
          <span class="home-page-text">
            <span class="centered-text">
              <span>Hammam’s Portfolio</span>
              <span>Website</span>
            </span>
          </span>
          <div class="home-page-frame4"></div>
          <div class="home-page-frame1"></div>
        </div>
        
        
        <!-- <div class="Buttons_Position"> -->
        <button class="Hire_me_button">
          <span class="home-page-text05"><span>Hire Me</span></span>
        </button>

        <button class="Download_cv_button">
          <span class="home-page-text07"><span>Download CV</span></span>
        </button>
      <!-- </div> -->

      </div>
      <div class="home-page-frame5">
        <span class="home-page-text09"><span>Home</span></span>
        <span class="home-page-text11">
          <span>About Me</span>
          <br />
        </span>
        <span class="home-page-text14"><span>Work</span></span>
        <span class="home-page-text16"><span>Contact</span></span>
      </div>
      <ul class="list">
        <li class="list-item"></li>
        <li class="list-item"></li>
        <li class="list-item"></li>
      </ul>
    </div>
  </div>

   <!-- About Me Page part - Second Page-->
   
   <div class="about-me-page-container">

    

    <div class="about-me-page-about-me-page">
      <div class="about-me-page-desktop5">
        <div class="about-me-page-desktop4">
          <img
            src="/guardstandingscratchinghead1066-bs0k.svg"
            alt="Guardstandingscratchinghead1066"
            class="about-me-page-guardstandingscratchinghead"
          />

            

    <div class="man_image">
    <img src="@/assets/man_image.png" alt="">
    </div>

          <span class="about-me-page-text">
            <span>
              My name is Hammam abdelmajed , Software engineering enthusiast eager
              to learn i gave experience with JS, HTML ,CSS and have cyber
              security skills
            </span>
          </span>
          <span class="about-me-page-text2"><span>About Me</span></span>
        </div>
      </div>
    </div>

    <div class="aboutme_image">
    <img src=@/assets/aboutme_image.png alt="">
    </div>

   

  </div>



  </div>
</template>

<script>

</script>

<style>

.full-width{
  width: 100%;
}

.home-page-container {
  width: 100%;
  display: flex;
  overflow: auto;
  height: 1080px;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.home-page-home-page {
  width: 100%;
  height: 1080px;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  background-color: rgba(15, 16, 63, 1);
}

/* the planet */

.image1 {
  bottom: 0px;
  right: 30px;
  width: 800px;
  height: 820px;
  display: flex;
  position: absolute;
  background-size: cover;
  background-image: url('');
  background-position: center;
}

/* the diamond */

.image2 {
  top: -50px;
  left: -250px;
  width: 500px;
  height: 500px;
  display: flex;
  position: absolute;
  background-size: cover;
  background-image: url('');
  background-position: center;
}

/* layout for the buttons and title */

.h1_buttons_Container {
  gap: 100px;
  top: 335px;
  right: 100px;
  width: 887px;
  height: 282px;
  display: flex;
  position: absolute;
  align-items: flex-end;
  justify-content: flex-start;
}

/* Moving the buttons up space */
.Hire_me_button,
.Download_cv_button {

  margin-top:100px;
}

/* changing the frame position of the header */

.h1-position {
  gap: 10px;
  top: -12px;
  left: -140px;
  width: 887px;
  display: flex;
  position: absolute;
  flex-wrap: wrap;
  align-items: center;
  flex-shrink: 0;
  justify-content: center;
}


.centered-text{

  text-align:center;
  

}


.home-page-text {
  color: rgba(255, 255, 255, 1);
  width: 887px;
  height: auto;
  font-size: 60px;
  font-style: Bold;
  text-align: left;
  font-family: Poppins;
  font-weight: 700;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
  
}
.home-page-frame4 {
  gap: 20px;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  z-index: 1;
  align-items: flex-start;
}

.home-page-frame1 {
  gap: 20px;
  display: flex;
  z-index: 2;
  align-items: flex-start;
}


.Hire_me_button {
  width: 165px;
  height: 51px;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-style: solid;
  border-width: 1px;
  border-radius: 30px;
  background-color: rgba(255, 255, 255, 0.30000001192092896);
}


.home-page-text05 {
  top: 13px;
  left: 50px;
  color: rgba(255, 255, 255, 1);
  height: auto;
  position: absolute;
  font-size: 17px;
  font-style: Bold;
  text-align: center;
  font-family: Poppins;
  font-weight: 700;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.Download_cv_button {
  width: 165px;
  height: 51px;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  border-style: solid;
  border-width: 1px;
  border-radius: 30px;
  background-image: linear-gradient(169deg, rgba(41, 84, 163, 1) 0%, rgba(201, 97, 222, 0) 100%);
}
.home-page-text07 {
  top: 12px;
  color: rgba(255, 255, 255, 1);
  right: 24px;
  height: auto;
  position: absolute;
  font-size: 17px;
  font-style: Bold;
  text-align: left;
  font-family: Poppins;
  font-weight: 700;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.home-page-frame5 {
  gap: 150px;
  top: 43px;
  left: 393px;
  width: 556px;
  display: flex;
  position: absolute;
  align-items: center;
  flex-shrink: 0;
  justify-content: center;
}
.home-page-text09 {
  color: rgba(255, 255, 255, 1);
  width: 42px;
  height: auto;
  font-size: 14px;
  font-style: Medium;
  text-align: left;
  font-family: Poppins;
  font-weight: 500;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.home-page-text11 {
  color: rgb(255, 255, 255);
  width: 75px;
  height: auto;
  font-size: 14px;
  font-style: Medium;
  text-align: left;
  font-family: "Poppins";
  font-weight: 500;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.home-page-text14 {
  color: rgba(255, 255, 255, 1);
  width: 42px;
  height: auto;
  font-size: 14px;
  font-style: Medium;
  text-align: left;
  font-family: Poppins;
  font-weight: 500;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.home-page-text16 {
  color: rgba(255, 255, 255, 1);
  width: 61px;
  height: auto;
  font-size: 14px;
  font-style: Medium;
  text-align: left;
  font-family: Poppins;
  font-weight: 500;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;




/* ---------------------------------------------------------------------- */

                             /*About me Page Desgin */



}.about-me-page-container {
  width: 100%;
  position:relative;    /*so i can position the images inside of it */  
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  
}
.about-me-page-about-me-page {
  width: 100%;
  height: 1024px;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: flex-start;
  flex-shrink: 0;
  background-color: rgba(15, 16, 63, 1);
}
.about-me-page-desktop5 {
  top: 275px;
  left: 405px;
  width: 630px;
  height: 630px;
  display: flex;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
  border-radius: 350px;
  background-image: linear-gradient(121deg, rgba(201, 97, 222, 1) 0%, rgba(255, 255, 255, 0) 76%);
}
.about-me-page-desktop4 {
  top: -190px;
  left: 0px;
  width: 620px;
  height: 820px;
  display: flex;
  overflow: hidden;
  position: absolute;
  align-items: flex-start;
  flex-shrink: 0;
  border-radius: 0 0 350px 350px;
}
.about-me-page-guardstandingscratchinghead {
  top: -225px;
  left: -143px;
  width: 779px;
  height: 1559px;
  position: absolute;

  
}
.about-me-page-text {
  top: 432px;
  left: 335px;
  color: rgba(255, 255, 255, 1);
  width: 222px;
  height: auto;
  position: absolute;
  font-size: 17px;
  font-style: Bold;
  text-align: left;
  font-family: Poppins;
  font-weight: 700;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.about-me-page-text2 {
  top: 376px;
  left: 335px;
  color: rgba(255, 255, 255, 1);
  width: 123px;
  height: auto;
  position: absolute;
  font-size: 20px;
  font-style: Bold;
  text-align: left;
  font-family: Poppins;
  font-weight: 700;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}

/* images */

.aboutme_image {
  position: absolute;
  bottom:0px;
  right:300px;
  
  

}


</style>
