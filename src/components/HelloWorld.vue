<template>
  <div class="hello">
    <h1 class="message">{{msg}}</h1>
    <img
      src="../assets/face-image.png"
      alt="Facebook Logo"
      class="icon"
    />
    <a
      href="https://www.facebook.com/dedicationrajada"
      target="_blank"
      rel="noopener"
      >Facebook</a
    >
    <ul>
      <li>
        <img
          src="../assets/instagram-image.png"
          alt="Instagram Logo"
          class="icon"
        />
        <a
          href="https://www.instagram.com/goodedication/"
          target="_blank"
          rel="noopener"
          >Instagram</a
        >
      </li>
    </ul>
		<ul>
			<img 
				src="../assets/galera.jpg" 
				alt="Foto da galera" 
				style="height: 500px; width: 700px" 
			/>
		</ul>
  </div>
</template>

<script>

export default {
	name: "HelloWorld",
	props: ['msg']
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #4252fd;
}
.message {
	color: #FFF;
}
.icon {
	height: 30px; 
	width: 30px
}
</style>
