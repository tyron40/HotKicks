<template>
  <body>
    <section id="header">
       <a href="#"><img src="assets/logo.png" class="logo" alt=""></a>
       <div>
           <ul id="navbar">
              <li><a class="active" href="index.html">Home</a></li>
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
body{
  width: 100%;
}
#header{
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 80px;
  background: #E3E6F3;
  box-shadow: 0 5px 15px rgba( 0, 0, 0, 0.6);
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
#navbar {
  display: flex;
  align-items: center;
  justify-content: center;
}
#navbar li {
list-style: none;
padding: 0 20px;
position: relative;
}
#navbar li a {
  text-decoration: none;
  font-size: 16px;
  font-weight: 600;
  color: #1a1a1a;
  transition: 0.3s ease;
}
#navbar li a:hover,
#navbar li a.active {
  color: #088178;
}
#navbar li a.active::after,
#navbar li a:hover::after {
  content: "";
  width: 30%;
  height: 2px;
  background: #088178;
  position: absolute;
  bottom: -4px;
  left: 20px;
}
</style>
