<template>
  <div id="about">
    <div class="about">
      <div class="aboutpage">
        <div class="about-img">
          <img src="https://i.postimg.cc/wBvZDWrt/pfp.jpg" alt="" />
        </div>
        <div class="about-brief">
          <h1>Abdul-Azeez Kemp</h1>
          <h3>Aspiring Full-Stack Web Developer</h3>
          <button class="con-btn">Lets Connect</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.about {
  height: 100vh;
  /* background-color: blue; */
  display: flex;
  justify-content: center;
  align-items: center;
}
.aboutpage {
  display: flex;
  align-items: center;
}

.about-img {
  padding-right: 5rem;
}

.about-img img {
  /* border-radius: 40% 60% 48% 52% / 57% 45% 55% 43%; */
  width: 30rem;
  height: 30rem;
}

.about-brief {
  font-family: "Trebuchet MS", "Lucida Sans Unicode", "Lucida Grande",
    "Lucida Sans", Arial, sans-serif;
}

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
</style>