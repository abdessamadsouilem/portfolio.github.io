<template>
  <div>
      <br>
      <div class="id" data-aos="fade-down">
      <h1>ABOUT ME</h1>
      <p>HOPE TO KNOW YOU AFTER</p>
      </div>
      
      <img data-aos="fade-left" src="../assets/WhatsApp Image 2021-04-19 at 11.53.51 PM.jpeg" alt="" >
      <br>
      <br>
      <div class="container-fluid d-flex flex-row justify-content-center text-left">
          <div class="row">
              <div class="col-lg-1">

  </div>
  <div data-aos="fade-right" class="col-xs-12 col-lg-6" >
<h3>WHO AM I ?</h3>
<br>
<p>I'm a Full-Stack Developer student. Actually, I have a Licence BAC+3 in Law and I  started learning development web
I always liked to get into projects using the skills that I did not have or were even spare pure programming like web design, 3D modeling ect... This allowed me to learn to be autonomous and to learn on my own, certainly not without difficulties far from it, but I always managed to overcome the obstacles and solve the problems I encountered !</p>
  </div>
  <div class="col-lg-1">

  </div>
  <div data-aos="fade-right" class="col-xs-12 col-lg-4" >
   <h3>ABDESSAMAD SOUILEM</h3>
   <br>
   <p><strong>E-mail:</strong> abdessamadsouilem1@gmail.com</p>
   <p><strong>Phone:</strong> +212 694175174</p>
   <p><strong>City:</strong> Marrakech</p>
   <p><strong>Languages:</strong> Arabic, French, English</p>

<ul class="social">
  <li ><a href=""><i class="fab fa-facebook-square"></i></a></li>
  <li ><a href=""><i class="fab fa-instagram-square"></i></a></li>
  <li><a href=""><i class="fab fa-linkedin"></i></a></li>
  <li ><a href=""><i class="fab fa-github-square"></i></a></li>
</ul>
   
   
   
   
  </div>
      </div>
  </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500&display=swap');
div{
        font-family: 'Montserrat', sans-serif;
        
}
.id:after {
      content: "";
      width: 170px;
      display: block;
      margin: 20px auto;
      border-bottom: 2px solid black;
}
img{
    width: 200px;
    height: 200px;
    border-radius: 50%;
}
.container-fluid{
    width: 100%;
}
ul{
    list-style: none;
    
}
li{
display: inline-block;
margin-right: 10px;
}
.fab{
    font-size: 40px;
    color: black;
}
@media (max-width: 500px) {
  
    h1 {
      font-size: 16px;
    }
    p{
    font-size:13px;
}
}
</style>