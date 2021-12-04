<template>
<div id="app">
  <div class="header">

    <div class="title">
      <h1>A Collection of Ideas That are Weird but are Commmon</h1>
    </div>
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/">Home</router-link>
    <p>
      <router-link to="/admin">Upload Ideas</router-link>
    <p>
      <hr>

      <a href="https://github.com/benjamingiles/CreativeProject4">Github</a>
    <p>Made by Ben Giles and Alec Davis</p>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  border-radius: 5px;
  margin-left: auto;
  margin-right: auto;
  max-width: 1000px;
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #5BDEFF;
  color: #2c2c2c;
}

.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  justify-content: center;
  text-align: center;

  margin-left: auto;
  margin-right: auto;
  border-radius: 5px;
  max-width: 1000px;
  min-height: 50px;
  padding: 20px 100px 1px 100px;
  background: #e3e3e3;
  font-size: 12px;
}

.footer a {
  color: #000;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
