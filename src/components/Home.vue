<template>
  <div class="home">
	
    <h1>{{ msg }}</h1>
	<h3>My personal site</h3>
	<br />
    <a href="https://wongmt.github.io/v-app/cv.html" >CV</a> |
      <a href="https://wongmt.github.io/v-app/privacy.html" >Privacy policy</a>   
    
	<br /><br />
	
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
h2 {
  margin: 30px 0 0;
}

a {
  color: #42b983;
}
</style>
