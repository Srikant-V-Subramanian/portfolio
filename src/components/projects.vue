<template>
  <meta name="view-transition" content="same-origin" />
  <h1>My Projects</h1>
  <div class="cards">
    <div class="card-1 animate__animated animate__fadeInLeft">
      <img src="../../public/project1.png" alt="" />

      <button class="button">
        <a href="https://music-player-mu-weld.vercel.app" target="_blank"
          >Music Player 🎧</a
        >
      </button>
    </div>
    <div class="card-2 animate__animated animate__fadeInLeft">
      <img src="../../public/project2.png" alt="" />
      <button class="button">
        <a href="#">TheBlog™️ App </a>
      </button>
    </div>
  </div>
</template>

<style>
.my-projects {
  color: white;
  background-color: #0a2463;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.my-projects > h1 {
  font-size: 3rem;
  margin-bottom: 10%;
  margin-top: 5%;
}

.cards {
  display: flex;
  flex-direction: row;
}

.card-1 > img {
  pointer-events: none;
  height: 45vh;
  width: 80vh;
}

.card-2 > img {
  pointer-events: none;
  height: 45vh;
  width: 80vh;
}

.card-1,
.card-2 {
  display: flex;
  flex-direction: column;
  border: white;
  margin: 0rem 3rem;
}

.card-1 > img {
  filter: drop-shadow(0 0 0.75rem white);
}

.card-2 > img {
  filter: drop-shadow(0 0 0.75rem white);
}

.card-1 > button {
  margin: 4rem;
  padding: 0.5rem;
  margin-bottom: 7rem;
  background-color: #0a2463;
}
.card-2 > button {
  margin: 4rem;
  padding: 0.5rem;
  margin-bottom: 7rem;
  background-color: #0a2463;
}

.card-1 > button:hover {
  border-color: #0a2463;
}
.card-2 > button:hover {
  border-color: #0a2463;
}

@media only screen and (max-width: 1140px) {
  .cards {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .card-1 {
    margin: 0;
  }

  .card-2 {
    margin: 0;
  }

  .card-1 > img {
    pointer-events: none;
    height: 31.5vh;
    width: 56vh;
  }

  .card-2 > img {
    pointer-events: none;
    height: 31.5vh;
    width: 56vh;
  }

  .card-1 > button {
    margin: 4rem;
    padding: 0.5rem;
    margin-bottom: 7rem;
    font-size: 1.5rem;
    background-color: #0a2463;
  }
  .card-2 > button {
    margin: 4rem;
    padding: 0.5rem;
    margin-bottom: 7rem;
    font-size: 1.5rem;
    background-color: #0a2463;
  }
}
</style>
