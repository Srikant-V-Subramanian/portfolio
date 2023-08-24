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
  font-size: 5em;
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

.custom-shape-divider-bottom-1691758750 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.custom-shape-divider-bottom-1691758750 svg {
  position: relative;
  display: block;
  width: calc(100% + 1.3px);
  height: 186px;
}

.custom-shape-divider-bottom-1691758750 .shape-fill {
  fill: #ffffff;
}
</style>
