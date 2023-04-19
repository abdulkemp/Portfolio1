<template>
  <div id="about">
    <div class="about">
      <div class="about-me">
        <h1>About Myself</h1>
      </div>
      <div class="info">
        <img
          src="https://i.postimg.cc/P5R6CrKR/IMG-20230311-175710-1.jpg"
          style="margin-top: 2rem; margin-bottom: 2rem"
          alt=""
          srcset=""
        />
        <div class="para">
          <h1>Hi I am Abdul-Azeez Kemp</h1>
          <p>
            I am Abdul-Azeez Kemp, a 24 year old from Mitchells plain, Cape
            Town. <br />
            I graduated from an art school with no knowledge of IT or web
            development, but I have always had a passion for technology. I began
            studying IT and Web Development to pursue a career in technology.
            <br />
            In my free time I'm spending time with my friends and family,
            playing games, sports and learning knew skills other than IT
            related.
          </p>
        </div>
      </div>
    </div>
    <div class="li"></div>
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



.about-me{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 3rem;
  }

  .about-me h1{
    text-decoration: underline;
  }

.about {
  width: 100%;
  height: 100%;
  display: inline-block;
  justify-content: center;
  align-items: center;
  
}
.about .info img {
  width: 600px;
  height: auto;
  max-width: 100%;
}
.para {
  max-width: 100%;
  width: 550px;
  padding: 0 10px;
}
.info {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  width: 1280px;
  max-width: 95%;
  margin: 0 auto;
  margin-top: 3rem;
}
.para h1 {
  margin-top: 1rem;
  margin-bottom: 1rem;
  text-transform: capitalize;
  color: red;
  font-size: 42px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.para h5 {
  margin-bottom: 1rem;
  text-transform: capitalize;
  letter-spacing: 2px;
  font-size: 2rem;
  color: cyan;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
.para p {
  letter-spacing: 1px;
  font-size: 16px;
  color: black;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
@media screen and (max-width: 650px) {
  .about .info img {
    margin-bottom: 35px;
    /* display: inline-block; */
  }

  .about{
    display: inline-block;
  }

  .about-me{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 3rem;
  }

  .about-me h1{
    text-decoration: underline;
  }
  .para h1 {
    font-size: 25px;
    margin-bottom: 1rem;
  }
}
@media screen and (max-width: 1700px) {
  .every .linkings {
    margin-top: 3rem;
  }
  .every .lower {
    margin-top: 3rem;
  }
  .every .d-flex {
    width: 25rem;
    max-width: 100%;
  }
}
@media screen and (max-width: 650px) {
  .every .d-flex {
    width: 15rem;
    max-width: 100%;
  }
}

/* .about-me {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}

.about {
  height: 100vh;
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

@media screen and (max-width: 650px) {


  .aboutpage{
    width: 100%;
  }
  .brief{
    display: inline-block;
  }
  .about-img img{
    width: 10rem;
    height: 10rem;
  }
  .about-brief{
    width: 30rem;
    height: 100%;
  }
} */
</style>