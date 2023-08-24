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
  color: white;
  background-color: #1e1b18;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  flex-direction: column;
  gap: 25%;
}

.site-under-dev {
  font-family: sans-serif;
  font-size: 4rem;
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
  background-color: #1e1b18;
  color: white;
  border: 5px solid;
  border-color: white;
  font-size: 3em;
  transition: 0.7s ease-in-out;
  padding: 0.5em;
}

.btn:hover {
  background-color: white;
  color: #1e1b18;
  border-color: #1e1b18;
  border: 5px solid;
  cursor: pointer;
  transition: 0.7s ease-in-out;
  filter: drop-shadow(0 0 0.75rem #ffffff);
}

.btn:hover > a {
  color: #1e1b18;
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
