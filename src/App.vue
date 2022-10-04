
<script>
  import Card from "./components/Card.vue"
  import headercard from "./components/headercard.vue"
  import footerc from "./components/footerc.vue"

  export default {
    components:{Card,
      headercard,
      footerc
    },
  };
</script>

<template>
    <headercard>
    </headercard>
<body>
  <div class="card p-3 bg-transparent">
  </div>
  <nav>Menú</nav>
  <div class="contenedor">
  <card url="https://th.bing.com/th/id/R.f7741f95fb7e40f3db34b1e19b667754?rik=BOrdjtT4qYd8iA&riu=http%3a%2f%2fwww.latrochadigital.com.ar%2fwp-content%2fuploads%2f2020%2f11%2fhamburguesas.jpg&ehk=aansa0UhkWIq%2fHX1OZuD2DzB2tuu5x7hsWneA5Wy5tY%3d&risl=&pid=ImgRaw&r=0" 
  nombre ="Hamburguesa"
  detalles="Esto no es una hamburguesa sino felicidad."
  Ingredientes="Carne, Cebolla, Tomate, Lechuga y Papas fritas"
  precio="120.00"
  ></card>

  <card url="https://club.elnuevodia.com/wp-content/uploads/2019/11/Abbys-Pizza.jpg" 
  nombre ="Pizza de Peperoni"
  detalles="Siempre estoy de humor para comer pizza."
  Ingredientes="Peperoni, queso, salsa de tomate y pan"
  precio="110.00"
  >
  </card>

  <card url="https://www.rebanando.com/uploads/tag/15-09-25-11-13-am-screen-shot_crop.png?1443172446" 
  nombre ="Helado de Café"
  detalles="Un helado compartido sabe siempre mejor, si cada uno tiene el suyo."
  Ingredientes="Café, leche"
  precio="20.00"
  >
  </card>

  <card url="https://th.bing.com/th/id/R.6cdd406e0a126d8a1440e02093a2ad3f?rik=CmizAEijwX3c0Q&pid=ImgRaw&r=0" 
  nombre ="Hot dog"
  detalles="Come uno todos los días"
  Ingredientes="Jalapeño, queso mozzarella,cebolla, salchicha"
  precio="80.50"
  >
  </card>


  <card url="https://th.bing.com/th/id/R.a01b8c22ea36eeaad243ab4238ae2dfb?rik=1Oh%2fnW3JIlp7Aw&riu=http%3a%2f%2fwww.viajejet.com%2fwp-content%2fviajes%2fBurritos1.jpg&ehk=N4PTmQyqXO8got6kPwyBlt%2ffGMGHAVe47W1XWQwofMQ%3d&risl=&pid=ImgRaw&r=0" 
  nombre ="Burritos Mexicanos"
  detalles="Comer o no comer, esa es la cuestión. ¡No me cuestione y coma aquí!"
  Ingredientes="Tortilla de harina, arroz, carne, salsa, picadillo, aguacate"
  precio="50.00"
  >
  </card>

  <card url="https://th.bing.com/th/id/R.1dbae2af5eb73acb296ff5c367e7aaec?rik=YyISjtSh%2bnfw0Q&riu=http%3a%2f%2fmilrecetas.net%2fwp-content%2fuploads%2f2016%2f09%2fTacos-al-pastor-2.jpg&ehk=sRtbVsiF0q8t6JMafwSlm0eFC%2bPju8rqRCKo38kLkuU%3d&risl=&pid=ImgRaw&r=0" 
  nombre ="Tacos al Pastor"
  detalles="La combinación perfecta entre Piña y Carne,con un gran sabor."
  Ingredientes="Carne, piña, salsas, lechuga, limón"
  precio="30.00 la Orden"
  >
  </card>
</div>
  <footerc>
  </footerc>
</body>
</template>

<style scoped>
nav{
  background-color: rgba(118, 118, 180, 0.915);
  color: white;
  font-size: 5vh;
  text-align: center;
  padding: 5px;
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

</style>
