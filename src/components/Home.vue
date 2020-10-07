<template>
  <div class="home">
	
    <h1>{{ msg }}</h1>
	<h3>My personal site</h3>
	<br />
	<ul>
      <li><a href="https://wongmt.github.io/v-app/cv.html" >CV</a></li>
      <li><a href="https://wongmt.github.io/v-app/privacy.html" >Privacy policy</a></li>    
    </ul>
	<br>
	
    <p> This site is under construction. For an updated version of my personal
	site, please visit https://wongmt.github.io </p>
		<p>
		Welcome to my personal website. I am a researcher in 
		computer vision and machine learning with Ph.D in 
		Computing, M.Sc & B.Sc(Hons.) in Electronic Engineering. 
		I have experience in Python, Java, C++, PHP, Javascript and Kotlin.
		I also have strong interest in web app development using Python 
		and Javascript, and mobile app development using Java and Kotlin.
		This site is built by using the Vue Javascript framework, Javascript, 
		HTML and CSS. This site is hosted by GitHub Pages.</p>
	
	<h3>Education</h3>
	<ul>
	<li>PhD in Computer Science</li>
	<li>M.Sc in Electronic Engineering</li>
	<li>B.Sc (Hons.) in Electrical & Electronic Engineering</li>
	</ul>
	
	<h3>Experience and skills</h3>
	
	<p>Programming languages: Python, Javascript, C++, Java, Kotlin, PHP</p>
	<p>Web frameworks: Django, Flask, ReactJS, VueJS and CodeIgniter</p>
	<p>Computer vision software libraries: OpenCV, scikit-image</p>
	<p>Machine learning software libraries: Tensorflow, Weka</p>
	<p>Mobile app development: Kotlin, Java, Android Studio</p>
    
	<p> This website might use cookies to improve your experience of 
		using the site. If you continue to use this site, it will be 
		assumed that you agree to the use of cookies.</p>
    
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 20px 0 0;
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
  color: #42b983;
}
</style>
