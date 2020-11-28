<template>
  <div class="home">
	
    <h1>M Wong</h1>
	<h3>My personal site</h3>
	<br />
    <a href="https://wongmt.github.io/v-app/cv.html" >CV</a> |
    <a href="https://wongmt.github.io/v-app/privacy.html" >Privacy policy</a>   
    
	<br /><br />
		<p>
		Welcome to my personal website. I am a researcher in 
		computer vision and machine learning with Ph.D in 
		Computer Science, M.Sc & B.Sc(Hons.) in Electronic Engineering. 
		I have experience in Python, Java, C++, PHP, Javascript and Kotlin.
		I also have strong interest in web app development using Python 
		and Javascript, and mobile app development using Java and Kotlin.
		This site is built by using the Vue Javascript framework, Javascript, 
		HTML and CSS. This site is hosted by GitHub Pages.</p>
	
	<h2>Education</h2>
	<ul>
	<li>PhD in Computer Science</li>
	<li>M.Sc in Electronic Engineering</li>
	<li>B.Sc (Hons.) in Electrical & Electronic Engineering</li>
	</ul>
	
	<h2>Experience and skills</h2>
	<ul>
	<li>Programming languages: Python, Javascript, C++, Java, Kotlin, PHP</li>
	<li>Web frameworks: Django, Flask, ReactJS, VueJS and CodeIgniter</li>
	<li>Computer vision software libraries: OpenCV, scikit-image</li>
	<li>Machine learning software libraries: Tensorflow, Weka</li>
	<li>Mobile app development: Kotlin, Java, Android Studio</li>
    </ul>
	
	<div id="notice">
	<!--<p> <span v-if="seen">{{msg}}</span>-->
		<!--<button v-on:click="agree">Agree</button></p>-->
	</div>
		
  </div>
</template>

<script>
//let check=document.cookie.indexOf('myagreebutton1');
//if (check != -1) {
  //document.getElementById('notice').style.display="none"; 
  //seen= false;
//} 
export default {
  name: 'Home',

methods: {
    agree() {
      document.getElementById('notice').style.visibility="hidden";
      document.cookie = "myagreebutton1=agree";
    },
    check() {
	var check=document.cookie.indexOf('myagreebutton1');
    if (check != -1) {
     document.getElementById('notice').style.visibility="hidden";  
    } 
	}
  },
  
  data() {
  return {
    msg: "cookie is used",
    seen: true,
  }
}
	
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: 30px 0 0;
}

a {
  color: #42b983;
}

#notice {
	visibility: "";
}	
</style>
