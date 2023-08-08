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
    <h1 class="abt-me-text hidden">About Me</h1>
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
  max-width: 200%;
}

.about-me {
  display: flex;
  text-align: center;
  gap: 30%;
  height: 100%;
  margin: 12.5%;
  font-size: 2.5em;
}

.about-me-picture {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
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
