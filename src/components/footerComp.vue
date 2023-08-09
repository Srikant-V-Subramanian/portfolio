<template>
  <div class="footer">
    <h1 class="site-under-dev">THIS SITE IS UNDER DEVELOPMENT</h1>
    <button class="btn">
      <span><svg-icon type="mdi" :path="path" class="git-ico"></svg-icon></span
      ><a href="https://github.com/Srikant-V-Subramanian/" target="_blank"
        >My GitHub Profile</a
      >
    </button>
  </div>
</template>

<style>
.footer {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  flex-direction: column;
  gap: 25%;
}

.site-under-dev {
  font-family: sans-serif;
}

a:link,
a:visited {
  color: white;
  text-decoration: none;
}

.btn {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 5%;
  background-color: black;
  color: white;
  border: 5px solid;
  border-color: rgb(255, 255, 255);
  font-size: 2em;
  transition: 0.7s ease-in-out;
}

.btn:hover {
  background-color: white;
  color: black;
  border-color: black;
  border: 5px solid;
  cursor: pointer;
  transition: 0.7s ease-in-out;
}

.btn:hover > a {
  color: black;
  transition: 0.7s ease-in-out;
}

.git-ico {
  margin: 10px;
  height: 2em;
  width: 2em;
}
</style>

<script>
import SvgIcon from "@jamescoyle/vue-icon";
import { mdiGithub } from "@mdi/js";

export default {
  name: "footerComp",
  components: {
    SvgIcon,
  },
  data() {
    return {
      path: mdiGithub,
    };
  },
};
</script>
