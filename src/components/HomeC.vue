<template>
  <div id="home">
    <div class="home" data-aos="zoom-in" data-aos-duration="800">
      <div class="homepage">
        <div class="home-brief">
          <h1>Abdul-Azeez Kemp</h1>
          <h3>Aspiring Full-Stack Web Developer</h3>
          <a href="#contact">
            <button class="con-btn">Lets Connect</button>
          </a>
        </div>
        <div class="home-img ht">
          <img src="https://i.postimg.cc/wx1ZSxQz/C11-Abdul-Azeez-Kemp-1-1.jpg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style>
.home {
  min-height: 100vh;
  /* background-color: blue; */
  display: flex;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid black;
  margin-left: 5rem;
  margin-right: 5rem;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.homepage {
  display: flex;
  align-items: center;
}

.home-img {
  padding-left: 5rem;
}
.home-img img {
  border: 2px solid black;
}

/* * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.homepage {
  display: flex;
  align-items: center;
}

.home-img {
  padding-left: 5rem;
} */

.ht {
  border-radius: 50%;
}

/* .home-img img {
  border-radius: 50%;
  width: 20rem;
} */

/* .home-brief{
      font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    } */

.con-btn {
  width: 10rem;
  height: 3rem;
  margin-top: 1rem;
  background-color: rgb(133, 128, 128);
  color: whitesmoke;
}

.con-btn:hover {
  background-color: black;
  color: white;
  cursor: pointer;
}

@media screen and (max-width: 650px) {
  /* .home {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  } */
  .homepage {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
  }

  .home-img {
    display: none;
  }
}
</style>
