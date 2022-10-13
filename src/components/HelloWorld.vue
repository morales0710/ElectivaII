<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    
    <table style="width: 100%">
      <tr>
        <td>
          Razas
        </td>
        <td>
          Mascotas
        </td>
        <td>
          Dietas
        </td>
        <td>
          Productos
        </td>
      </tr>
      
      <tr>
        <td>id</td>
        <td>id</td>
        <td>mascotas</td>
        <td>id</td>
      </tr>

      <tr>
        <td>descripcion</td>
        <td>nombre</td>
        <td>productos</td>
        <td>descripcion</td>
      </tr>

      <tr>
        <td></td>
        <td>fecha nacimiento</td>
        <td></td>
        <td>estado</td>
      </tr>

      <tr>
        <td></td>
        <td>color</td>
        <td></td>
        <td></td>
      </tr>

      <tr>
        <td></td>
        <td>apodo</td>
        <td></td>
        <td></td>
      </tr>

      <tr>
        <td></td>
        <td>razas</td>
        <td></td>
        <td></td>
      </tr>
      
    </table>
    
    
    
  </div>
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
</style>
