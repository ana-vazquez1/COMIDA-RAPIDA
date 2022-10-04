<template>
    <header>
    <h1>El Rincón de Ana</h1>
    <button onclick="window.open('https://www.rappi.com.mx/puebla/restaurantes/category/hamburguesas')">Ordenar</button>
</header>
</template>
<script>

</script>

<style>
    @font-face {
        font-family: 'Bungee Spice', cursive;
        src: url("https://fonts.googleapis.com/css2?family=Bungee+Spice&family=Poppins:ital,wght@0,100;0,300;1,200&display=swap");
    }
header{
    background-image: url("https://i.pinimg.com/originals/d3/47/51/d34751162b851352dd7b962eeb6b5a28.jpg");
    background-size:cover;
    background-repeat: no-repeat;
    height: 60vh;
    display: block;
    text-align: center;
}
h1{
    padding-top: 30vh;
    padding-bottom: 20px;
    color: black;
    font-family: 'Bungee Spice', cursive;
    font-size: 10vh;
}
button{
    text-decoration: none;
    font-size: 25px;
    color:black;
    padding: 10px;
    border: solid black 1px;
    border-radius: 10px;
    background:transparent;
}
</style>