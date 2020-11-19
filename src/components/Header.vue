<template>
<header>
        <a href="#" class="logo">Assignment Helper</a>

     <ul>
        <li><a href="#carousel_a896">Home</a></li>
        <li><a href="#carousel_b5ac">Why Us</a></li>
        <li><a href="#carousel_4e3c">Order</a></li>
        <li><a href="#carousel_c8d1">Subscription</a></li>
        <li><a href="#carousel_d8dd">Join Us</a></li>
      </ul>
    </header>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap');

header
{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: 0.6s;
    padding: 10px 50px;
    z-index: 1;
    background: rgb(25, 41, 48);
}
header.sticky
{
    padding: 5px 100px;
}
header .logo
{
    position: relative;
    font-weight: 700;
    color: #fff;
    text-decoration: none;
    font-size: 2em;
    text-transform: uppercase;
    letter-spacing: 2px;
    transition: 0.6s;
}
header ul
{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}
header ul li
{
    position: relative;
    list-style: none;
}
header ul li a
{
    position: relative;
    margin: 0 15px;
    text-decoration: none;
    color: #fff;
    letter-spacing: 2px;
    font-weight: 500px;
    transition: 0.6s;
}
.banner
{
    position: relative;
    width: 100%;
    height: 100vh;
    background: url("../assets/logo.png");
    background-size: cover;
}
header.sticky .logo,
header.sticky ul li a
{
    color: #000;
} 


</style>
