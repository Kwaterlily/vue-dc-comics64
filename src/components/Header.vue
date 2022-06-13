<template>
  <div class="hello">
    <header>
        <nav>
            <ul>
                <li><a href="#"></a>Characters</li>
                <li><a href="#"></a>Comics</li>
                <li><a href="#"></a>Movies</li>
                <li><a href="#"></a>Tv</li>
                <li><a href="#"></a>Games</li>
                <li><a href="#"></a>Collectibles</li>
                <li><a href="#"></a>Videos</li>
                <li><a href="#"></a>Fans</li>
                <li><a href="#"></a>News</li>
                <li><a href="#"></a>Shop</li>
            </ul>
        </nav>
    </header>
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
h1 {
  margin: 40px 0 0;
  color: red;
  
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
