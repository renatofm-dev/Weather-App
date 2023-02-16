<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..."/>
      </div>
    </main>
  </div>
  <h1>hello</h1>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      api_key: '67a21247f5eba44b397dfba9f7978e5a'
    
    }
      
  }

}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;

};

body {
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
}
</style>
