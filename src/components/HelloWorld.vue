<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <img
      src="../assets/face-image.png"
      alt="Facebook Logo"
      style="height: 30px; width: 30px"
    />
    <a
      href="https://www.facebook.com/dedicationrajada"
      target="_blank"
      rel="noopener"
      >Facebook Dedication</a
    >
    <ul>
      <li>
        <img
          src="../assets/instagram-image.png"
          alt="Instagram Logo"
          style="height: 30px; width: 30px"
        />
        <a
          href="https://www.instagram.com/goodedication/"
          target="_blank"
          rel="noopener"
          >Instagram Dedication</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
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
</style>
