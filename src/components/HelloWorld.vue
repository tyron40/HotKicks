<template>
  <body>
    <section id="header">
      <a href="#"><img src="assets/logo.png" class="logo" alt=""></a>
  <div>
    <ul id="navbar">
      <li><a href="index.html">Home</a></li>
      <li><a href="shop.html">Shop</a></li>
      <li><a href="blog.html">Blog</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="contact.html">contact</a></li>
      <li><a href="cart.html"><i class="fa-regular fa-bag-shopping"></i></a></li>
    </ul>
  </div>
       </section>
      </body>
  
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
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
  color: #42b983;
}
#header{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 80px;
  background: #E3E6F3;
  box-shadow: 0 5px 15px rgba( 0, 0, 0, 0.6);
}
</style>
