<script>
import "animate.css";
</script>

<template>
  <div class="about-me-picture animate__animated animate__fadeInLeft">
    <h1 class="about-me-title hidden animate__animated animate__fadeInLeft">
      About Me
    </h1>
    <img
      class="profile hidden"
      src="https://i.pinimg.com/originals/0e/1c/10/0e1c100908962a43f711d0e2caca3a0c.gif"
      alt=""
    />
  </div>
  <div class="about-me-text animate__animated animate__fadeInLeft">
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
  background-image: url("../../public/stacked-waves-haikei.svg");
  background-size: cover;
  background-repeat: no-repeat;
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

@media only screen and (max-width: 1140px) {
  .profile {
    margin-top: 10%;
    border-radius: 50%;
    max-width: 200px;
  }

  .about-me {
    flex-direction: column;
    padding: 5rem;
    gap: 0%;
  }
  .about-me-picture {
    margin: 15%;
  }

  .about-me-title {
    font-size: 2.5rem;
  }

  .about-me-text {
    font-size: 1.2rem;
    padding: 0;
  }
}
</style>
