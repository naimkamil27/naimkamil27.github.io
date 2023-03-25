<template>
  <div>
    <div class="container">
      <div class="text-center mainpage">
        <h1 class="intro">Hi my name is <span style="color: aqua;">Naim Kamil</span></h1>
        <div class="text">
          <h5>UI/UX Designer and Front End Developer</h5>
          <h6>Im providing front end development codes and UIUX design. <br> Also do freelance in animation. Let's get working together.</h6>
        </div>
      </div>
      <div class="text-center">
          <a target="_blank" href="https://www.linkedin.com/in/naim-kamil-b6679a237/"><i class='linkedin bx bxl-linkedin'></i></a>
          <a target="_blank" href="https://wa.me/60182084225"><i class='whatsapp bx bxl-whatsapp ml-4 mr-4'></i></a>
          <a target="_blank" href="mailto:nakikami27@gmail.com"><i class='gmail bx bxl-gmail'></i></a>
      </div>
    </div>
    <Projects class="project"/>  
  </div>
    
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
<style scoped>

.linkedin, .whatsapp, .gmail {
  color: white;
  font-size: 3rem;
}

.linkedin:hover {
    text-shadow: 0 0 50px #3e55e9; 
    color: #3e55e9;
}
.whatsapp:hover {
    text-shadow: 0 0 50px #2b9348; 
    color: #2b9348;
}

.gmail:hover {
    text-shadow: 0 0 50px #9e2a2b;
    color: #9e2a2b; 
} 
.text {
  font-family: 'Roboto Mono', monospace;
}
.intro {
  font-family: 'Lora', serif;
  font-size: 4.5rem;
}
.mainpage {
  margin-top: 20% !important;  
}

.project {
  margin-top: 300px;
  
  @media (min-width: 576px) and (max-width: 767.98px){
    margin-top: 100px;
  }
}
</style>
