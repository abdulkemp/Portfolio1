<template>
  <div id="projects">
    <div class="my-projects">
      <h1>Projects</h1>
    </div>
    <div class="projects">
      <div class="container1">
        <div
          class="row content"
          style="
            display: flex;
            justify-content: center;
            margin-left: 1px;
          "
        >
          <div
            class="col-me-3 me-4 my-2 proj animate__animated animate__backInUp"
            v-for="pro in work"
            :key="pro"
            :pro="pro"
          >
            <img :src="pro.image" class="imagesByKemp" alt="..." />
            <h5 class="card-title">{{ pro.name }}</h5>
            <div class="but">
              <a :href="pro.github" target="_blank">
                <button class="butt">GitHub</button></a
              >
              <a :href="pro.netlify" target="_blank">
                <button class="butt">Go Live</button></a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Projects",
  data() {
    return {
      work: [
        {
          name: "Game Box",
          github: "https://github.com/abdulkemp/project.git",
          netlify: "https://project1-e-commerce.netlify.app/",
          image: "https://i.postimg.cc/cLydgrb4/Screenshot-20230112-162515.png",
        },
        {
          name: "Calculator",
          github: "https://github.com/abdulkemp/calculatorJs.git",
          netlify: "https://calculatorjsnew1.netlify.app/",
          image: "https://i.postimg.cc/3RkBjJRL/Screenshot-20230112-162452.png",
        },
        {
          name: "First Portfolio",
          github: "https://github.com/abdulkemp/MyPortfolio.git",
          netlify: "https://abdul-azeez-kemp.netlify.app/",
          image: "https://i.postimg.cc/W4CrvmNn/Screenshot-20230112-162424.png",
        },
        {
          name: "Jujutsu Kaisen",
          github: "https://github.com/abdulkemp/testimonial.git",
          netlify: "https://jujutsu.netlify.app/",
          image: "https://i.postimg.cc/6QyRgbXq/Screenshot-20230112-162356.png",
        },
        {
          name: "Sneaker-cartel",
          github: "https://github.com/abdulkemp/Sneaker_Cartel.git",
          netlify: "https://sneaker-cartel.netlify.app/",
          image: "https://i.postimg.cc/jjF6j0Xy/Screenshot-20230112-162322.png",
        },
        {
          name: "First Landpage",
          github: "https://github.com/abdulkemp/new-landpage.git",
          netlify: "https://newlandpage.netlify.app/",
          image: "https://i.postimg.cc/cH334K6N/Screenshot-20230112-161353.png",
        },
      ],
    };
  },
};
</script>

<style>
.projects {
  /* height: 100vh; */
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 5rem;
  /* border-bottom: 1px solid black;
  margin-left: 5rem;
  margin-right: 5rem; */
}

.my-projects {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}


.container1{
  width: 100%;
  display: flex;
  justify-content: center;
}
.card-title {
  padding: 18px;
  font-size: 25px;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
.proj {
  height: 23rem;
  max-width: 18rem;
  /* margin-left: 1rem; */
  border: 3px solid;
  background-color: rgba(128, 128, 128, 0.686);
  background-size: 100% 100%;
  border-radius: 10px;
  /* justify-content: center;
  align-items: center; */
  text-align: center;
  color: black;
}

.proj img {
  max-width: 95%;
  height: 220px;
  margin-top: 6%;
  border-top-left-radius: 7px;
  border-top-right-radius: 7px;
  border: 3px solid;
}
.but {
  display: flex;
  justify-content: space-between;
  align-items: center;
  /* margin-left: 1rem;
  margin-right: 1rem; */
}
.butt {
  border-radius: 7px;
  border: 0px solid transparent;
  color: white;
  background-color: rgb(30, 0, 255);
  width: 8rem;
  border: 2px solid black;
}

.head {
  font-size: 8vw;
  color: white;
  text-shadow: 0 0 5px, 0 0 25px, 0 0 50px;
}

.proj:hover {
  background: black;
  color: white;
  transition: 0.5s;
  box-shadow: 0 20px 30px rgba(0, 0, 0, 0.7);
  transform: scale(1.1);
  overflow: hidden;
  transition-duration: 0.9s;
}

#projects {
  border-bottom: 1px solid black;
  margin-left: 5rem;
  margin-right: 5rem;
}
</style>