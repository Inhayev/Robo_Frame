<template>
  <div id="app">
    <header>
      <nav>
        <ul>
          <li class="nav-item">
             <img class="logo" src="./assets/build-a-bot-logo.png">
             Build_Roboo
          </li>
        </ul>
      </nav>
    </header>
    <main>
      <RobotBuilder/>
    </main>
  </div>
</template>

<script>
//import HomePage from './home/HomePage.vue';
import RobotBuilder from './build/RobotBuilder.vue';

export default {
  name: 'app',
  components: {
    RobotBuilder,
  },
};
</script>
<style>
body {
  background: linear-gradient(to bottom, #303030, #999);
  background-attachment: fixed;
}
</style>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
main {
  position: relative;
  left: 10%; 
  margin: 0, auto;
  padding: 50px;
  background-color: beige;
  width: 1024px;
  min-height: 300px;
}
header {
  background-color: rgb(185, 180, 178);
  width: 1080px;
  margin-left: 158px;
  
  
}
ul {
  padding: 3px;
  display: flex;
}
.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}
.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
