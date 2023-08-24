<template>
  <h1 class="msg hidden">Hello!</h1>
  <p class="hidden">I'm Srikant! A developer cum music producer</p>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inika&family=Open+Sans&display=swap");

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  font-family: "Inika", serif;
}

.msg {
  font-size: 7em;
}

.landing-page > p {
  font-size: 2em;
}

.landing-page {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
  background-color: #d8315b;
  color: white;
  flex-direction: column;
  gap: 3em;
}

html {
  scroll-behavior: smooth;
}
</style>
