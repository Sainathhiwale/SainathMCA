<template>
  <div class="home">
    <img src="/static/images/sainath.jpg"/>
    <h1 class="inline">Sainath Hiwale</h1>
    <h3 class="inline">Coder | Singer | Explorer</h3>
    <p v-html ="about"></p>
    <p v-html = "more"></p>
    <p v-html ="possinate"></p>
   <v-divider></v-divider>
    <h3 class="inline">Accomplishments</h3>
    <p>
      <ul>
        <li>March 2018 | <strong>Google Play Store</strong> Examen App</li><br>
        <li>May 2018 | <strong>Firebase</strong> ExamenProgramming Site</li><br>
      </ul>
    </p>
   <v-divider></v-divider>
    <h3 class="inline">Recommendations</h3>
    <carousel></carousel>
    <v-divider></v-divider>
    <h3 class="inline">Skill Set</h3>
    <expertise></expertise>
    <h1>{{ msg }}</h1>
    <h2>Sainath Hiwale</h2>
    
  </div>
</template>

<script>
import Expertise from './Expertise'  
import Carousel from './Carousel'
export default {
  name: 'home',
  data () {
    return {
      msg: 'Sainath Hiwale',
      about: 'Sainath is a passionate and pragmatic programmer,I love to learn new technology <a href="/writes" style="color: #EA8E28 !important;" target="_blank">blogger</a> and also <a href="/engagements" style="color: #EA8E28 !important;" target="_blank">speaker</a> Programming tutorial coding <a href="/projects" style="color: #EA8E28 !important;" target="_blank"> samples</a>, provides to you.',
      more: 'Sainath has 1 year Experience in Android development.I have just Published my own app Google Play Store <a href="https://play.google.com/store/apps/details?id=com.dorvis.quizapp" style="color: #EA8E28 !important;" target="_blank">Examen App</a> <br>Examen is an site where you can learn new Programming language as well as some tutorial and code sample.<a href="https://examenprogramming.firebaseapp.com/" style="color: #EA8E28 !important;" target="_blank">ExamenProgramming</a><br>I have done an MCA from Sinhgad Institute of Business Administration & Computer Application at Savitribai Phule Pune University.'

    }
  }
}
</script>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');
@import url('https://fonts.googleapis.com/css?family=Quattrocento+Sans:400,700');
@import url('https://fonts.googleapis.com/css?family=Open+Sans');
@import url('https://fonts.googleapis.com/css?family=Poppins');
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #F0FFFF;
 font-weight: bold;
 -webkit-transition: color 0.2s ease-in-out;
-moz-transition: color 0.2s ease-in-out;
-o-transition: color 0.2s ease-in-out;
transition: color 0.2s
}
p{
font-family: 'Poppins', sans-serif;
  position: relative;
  padding-left: 0.9375rem;
  padding-right: 0.9375rem;
  font-size: 18px;
  line-height: 2;
  color: #F0F8FF;
  text-rendering: optimizeLegibility;

}
.home img{
padding: 1rem 0;
margin: 3rem 0;
width: 300px;
border-radius: 50%;
margin: 0 auto;
display: table
}
h4{
font-size:18px;
font-weight: bold;
}
.inline{
color:#66c0ec !important;
}
.background{
  background-color: #fff;
}
</style>
