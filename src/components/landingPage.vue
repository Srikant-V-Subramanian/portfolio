<template>
  <h1 class="msg hidden">Hello!</h1>
  <p class="hidden">I'm Srikant! A developer cum music producer</p>
  <div class="bottom-curve">
    <svg
      data-name="Layer 1"
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 1200 120"
      preserveAspectRatio="none"
    >
      <path
        d="M321.39,56.44c58-10.79,114.16-30.13,172-41.86,82.39-16.72,168.19-17.73,250.45-.39C823.78,31,906.67,72,985.66,92.83c70.05,18.48,146.53,26.09,214.34,3V0H0V27.35A600.21,600.21,0,0,0,321.39,56.44Z"
        class="shape-fill"
      ></path>
    </svg>
  </div>
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
  background-color: black;
  color: white;
  flex-direction: column;
  gap: 3em;
}

.bottom-curve {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  overflow: hidden;
  line-height: 0;
  transform: rotate(180deg);
}

.bottom-curve svg {
  position: relative;
  display: block;
  width: calc(156% + 1.3px);
  height: 204px;
}

.bottom-curve .shape-fill {
  fill: #ffffff;
}
</style>
