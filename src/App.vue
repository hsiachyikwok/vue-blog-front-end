<template>
  <div id="app">
    <router-view v-title="$route.meta.title"/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body{
word-wrap: break-word;
}


img {
  border-style: none;
  width: 100%
}



/* .card__text{
  overflow: hidden;
text-overflow: ellipsis;
display: -webkit-box;
-webkit-line-clamp: 3;
-webkit-box-orient: vertical;
padding: 16px 16px 0;
width: 100%;
margin-bottom: 16px;
} */
</style>
