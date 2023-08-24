<script>
/* const observer = new IntersectionObserver((enteries) => {
  enteries.forEach((entry) => {
    console.log(entry)
    if (entry.isIntersecting) {
      entry.target.classList.add('show')
    } else {
      entry.target.classList.remove('show')
    }
  })
})

const hiddenElements = document.querySelectorAll('.hidden')

hiddenElements.forEach((el) => observer.observe(el)) */
</script>

<template>
  <div class="about-me-picture">
    <h1 class="about-me-title hidden">About Me</h1>
    <img
      class="profile hidden"
      src="https://i.pinimg.com/originals/0e/1c/10/0e1c100908962a43f711d0e2caca3a0c.gif"
      alt=""
    />
  </div>
  <div class="about-me-text hidden">
    <p>
      I am a high school student who is really passionate about computers and
      music. I am a web developer and have quite a bit of experience in building
      web applications. I have some knowledge and experience in building
      applications based on the MEN (MongoDB, Express and Node.js only) and MEVN
      stacks. I also have some experience in building apps using the Flutter
      framework. I also sometimes try to create songs.
    </p>
  </div>
</template>

<style>
.profile {
  margin-top: 10%;
  border-radius: 50%;
  max-width: 25vw;
}

.about-me-title {
  font-size: 3vw;
}

.about-me {
  color: white;
  background-color: #3e92cc;
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  gap: 30%;
  max-height: 100vh;
  min-height: 100vh;
  padding: 10em;
}

.about-me-text {
  font-size: 2vw;
}

.about-me-picture {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

img {
  pointer-events: none;
}

/* .hidden {
    opacity: 0;
    filter: blur(5px);
    transform: translateX(-100%);
    transition: all 2s;
}

.show {
    opacity: 1;
    filter: blur(0);
    transform: translateX(0);
}

@media(prefers-reduced-motion) {
    .hidden {
        transition: none;
    }
} */
</style>
