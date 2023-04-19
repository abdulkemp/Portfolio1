<template>
  <div id="home">
    <div class="home">
      <div class="homepage">
        <div class="home-brief">
          <h1>Abdul-Azeez Kemp</h1>
          <h3>Aspiring Full-Stack Web Developer</h3>
          <a href="#contact">
            <button class="con-btn">Lets Connect</button>
          </a>
        </div>
        <div class="home-img">
          <img src="https://i.postimg.cc/wBvZDWrt/pfp.jpg" alt="" />
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
  border-radius: 40% 60% 48% 52% / 57% 45% 55% 43%;
  width: 20rem;
}

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