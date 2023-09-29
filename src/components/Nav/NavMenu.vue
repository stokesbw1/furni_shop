<script setup lang="ts">
</script>

<template>
   <header>
      <a href="" class="logo">FurniShop</a>
      <ul>
         <li><a href=""></a>Home</li>
         <li><a href=""></a>About</li>
         <li><a href=""></a>Categories</li>
         <li><a href=""></a>Contact</li>
      </ul>
   </header>
</template>

<style scoped>
header {
   width: 100%;
   display: flex;
   justify-content: space-between;
   align-items: center;
   transition: 0.6s;
   padding: 20px 60px;
   background-color: #ffffff;
}

header .logo {
position: relative;
font-weight: 700;
color: #000000;
text-decoration: none;
font-size: 1.1em;
text-transform: uppercase;
letter-spacing: 2px;
}

header ul {
   position: relative;
   display: flex;
   list-style: none;
}

header ul li {
   position: relative;
   list-style: none;
}

header ul li a {
   position: relative;
   margin: 0 15px;
   text-decoration: none;
   color: #bc4b4b;
   letter-spacing: 2px;
   font-weight: 500px;
   transition: 0.6s;
}

</style>
