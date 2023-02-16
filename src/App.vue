<template>
  <div id="app">
    <main>

      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..."/>
      </div>

      <div class="weather-wrap">
        <div class="location-box">
          <div class="location">Northampton, UK</div>
          <div class="date">Monday 20 January 2020</div>
        </div>
        <div class="weather-box">
          <div class="temp">9°</div>
          <div class="weather">Rain</div>
        </div>
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

}

body {
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}

main {
  min-height: 100vh;
  padding: 25px;

  background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.25), rgba(0, 0, 0, 0.75));
}

.search-box {
  width: 100%;
  margin-bottom: 30px;

}

.search-box .search-bar {
  display: block;
  width: 100%;
  padding: 15px;

  color: #313131;
  font-size: 20px;

  box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.25);
  appearance: none;
  border: none;
  outline: none;
  background: none;
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 0px 16px 0px 16px;
  transition: 0.4s;
}

.search-box .search-bar:focus {
  box-shadow: 0px 0px 16px rgba(0, 0, 0, 0.25);
  background-color: rgba(255, 255, 255, 0.75);
  border-radius: 16px 0px 16px 0px;
}
</style>
