<template>
  <div id="about">
    <div class="about">
      <div class="about-me">
        <h1>About Myself</h1>
      </div>
      <div class="aboutpage">
        <div class="brief">
          <div class="about-img">
            <img src="https://i.postimg.cc/wBvZDWrt/pfp.jpg" alt="" />
          </div>
          <div class="about-brief">
            <h1>Abdul-Azeez Kemp</h1>
            <p>
              I am Abdul-Azeez Kemp, a 24 year old from Mitchells plain, Cape
              Town. <br />
              I graduated from an art school with no knowledge of IT or web
              development, but I have always had a passion for technology. I
              began studying IT and Web Development to pursue a career in
              technology. <br />
              In my free time I'm spending time with my friends and family,
              playing games, sports and learning knew skills other than IT
              related.
            </p>
          </div>
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

.about-me {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}

.about {
  height: 100vh;
  /* background-color: blue; */
  display: inline-block;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid black;
  margin-left: 5rem;
  margin-right: 5rem;
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

.brief {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-left: 10rem;
  margin-right: 10rem;
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