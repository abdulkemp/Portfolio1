<template>
  <div id="projects" data-aos="fade-down" data-aos-duration="800">
    <div class="proj">
      <div class="my-projects">
        <h1>Projects</h1>
      </div>
      <div class="projects someth">
        <div class="container1 row">
          <div class="col mt-5 boo" v-for="pro in work" :key="pro" :pro="pro">
            <div class="card bo">
              <div class="hover">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke-width="1.5"
                  stroke="currentColor"
                  class="w-6 h-6"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M19.5 5.25l-7.5 7.5-7.5-7.5m15 6l-7.5 7.5-7.5-7.5"
                  />
                </svg>
                <div class="pulse">Click Here</div>
              </div>
              <div class="imageProj">
                <img :src="pro.image" alt="" />
              </div>
              <div class="card-body date">
                <h1>{{ pro.name }}</h1>
                <p>{{ pro.desc }}</p>
                <div class="buttons">
                  <a :href="pro.github" target="_blank">Github</a>
                  <a :href="pro.netlify" target="_blank">Live Link</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="line"></div>
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
          name: "Lagom E-Comm",
          github: "https://github.com/abdulkemp/Lagom-Project",
          netlify: "https://lagom-ecom.netlify.app",
          desc: "An e-commerce clothing website selling clean, quality, trending clothing",
          image:
            "https://i.postimg.cc/d3Q7cY0M/Screenshot-2023-05-02-120637.png",
        },
        {
          name: "Trailblitz",
          github: "https://github.com/abdulkemp/Trailblitz.git",
          netlify: "https://trailblitz.netlify.app",
          desc: `Trailblitz: Your premier online destination for bicycles and sportsbikes, offering quality and adventure in every ride. "Project still in the making."`,
          image:
            "https://i.ibb.co/bQkJJ3B/Screenshot-2024-03-03-175100.png",
        },
        {
          name: "Calculator",
          github: "https://github.com/abdulkemp/calculatorJs.git",
          netlify: "https://calculatorjsnew1.netlify.app/",
          desc: "A basic calculator as a project to test out javascript",
          image:
            "https://i.postimg.cc/9M6Kvm2v/Screenshot-2024-02-07-194956.png",
        },
        {
          name: "My Desktop",
          github: "https://github.com/abdulkemp/desktop1.git",
          netlify: "https://desktop-rep.netlify.app",
          desc: "This a replica of a desktop, that I thought of designing.",
          image:
            "https://i.ibb.co/QJNx9RT/Screenshot-2024-02-08-181937.png",
        },
        {
          name: "Hangman",
          github: "https://github.com/abdulkemp/Hangman.git",
          netlify: "https://hangman-kemp.netlify.app",
          desc: "This is a hangman game with four different levels starting from easy to extreme",
          image:
            "https://i.ibb.co/FYLyC6X/Screenshot-2024-02-08-191231.png",
        },
        {
          name: "Piano",
          github: "https://github.com/abdulkemp/piano",
          netlify: "https://the-piano-site.netlify.app/",
          desc: "This is an online piano, so you can play some tunes",
          image:
            "https://i.ibb.co/sv2RNb7/Screenshot-2024-02-08-182836.png",
        },
        {
          name: "Password Generator",
          github: "https://github.com/abdulkemp/Password",
          netlify: "https://password-gener.netlify.app/",
          desc: "This is an online password generator, with random characters mixed up for a strong password",
          image:
            "https://i.ibb.co/QCK1TW7/Screenshot-2024-02-08-183012.png",
        },
        {
          name: "Elemental Challenge",
          github: "https://github.com/abdulkemp/ElementalChallenge.git",
          netlify: "https://elementalchallenge.netlify.app",
          desc: "An Elemental Challenge in create a website, fully responsive to every size from a photo reference.",
          image:
            "https://i.ibb.co/LQB6YYg/Screenshot-2024-02-08-192039.png",
        },
        {
          name: "Elemental Challenge",
          github: "https://github.com/abdulkemp/ElementalChallenge.git",
          netlify: "https://elementalchallenge.netlify.app/",
          desc: "Elemental Challenge, single page responsive for all sizes. HTML, CSS and JQuery",
          image:
            "https://i.postimg.cc/x11xtCHJ/2023-10-16.png",
        },
      ],
    };
  },
};
</script>

<style scoped>
.my-projects {
  width: 100%;
  text-align: center;
  margin-top: 2rem;
}

.projects {
  padding-bottom: 3rem;
  padding-left: 5rem;
  padding-right: 5rem;
}

.row {
  margin-left: 0;
  margin-right: 0;
  width: 90%;
}

.bo {
  width: 20rem;
  height: 15rem;
  text-align: center;
  background-color: wheat;
  border: 2px solid black;
  transition: transform 0.2s;
}

.card:hover {
  background: white;
  transition: 0.5s;
  box-shadow: 0 20px 30px rgba(0, 0, 0, 0.7);
  transform: scale(1.1);
  overflow: hidden;
}

.date {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 5px;
}

.boo {
  margin: 1px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.hover {
  position: relative;
  padding-top: 4rem;
  bottom: 0;
  right: 37%;
  display: flex;
  z-index: 1;
  color: black;
}

.card:hover .hover {
  display: none;
}

svg {
  transform: translateX(0px);
  animation: float 5s ease-in-out infinite;
  transition: 0.5s;
  width: 100px;
  min-height: 7rem;
}

@keyframes float {
  0% {
    transform: translateY(0px);
  }
  25% {
    transform: translateY(-30px);
  }
  50% {
    transform: translateY(30px);
  }
}

.card {
  width: 400px;
  height: 250px;
  background: #fff;
  position: relative;
  display: flex;
  align-items: flex-end;
  box-shadow: 0px 7px 10px rgba(0, 0, 0, 0.5);
  transition: 0.5s ease-in-out;
  border-radius: 0;
}

.card::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  display: block;
  width: 100%;
  height: 100%;
  background: linear-gradient(to bottom, #45a29dee, #45a29e);
  z-index: 2;
  transition: 0.5s all;
  opacity: 0;
  border-radius: 0;
}

.card:hover::before {
  opacity: 1;
}
.card .date {
  position: relative;
  z-index: 3;
  color: #1f2833;
  opacity: 0;
  transform: translateX(30px);
  transition: 0.5s all;
  z-index: 3;
}

.card:hover .date {
  opacity: 1;
  transform: translateX(0px);
}
.buttons {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.buttons a {
  width: 5rem;
  height: 2rem;
  height: 2.5rem;
  background-color: transparent;
  color: white;
  border: #66fcf1 solid 3px;
  text-decoration: none;
  color: #1f2833;
  display: flex;
  justify-content: center;
  align-items: center;
}
.buttons a:hover {
  transition: 0.5s;
  box-shadow: 0 7px 15px rgba(0, 0, 0, 1.5);
  transform: scale(1.1);
  overflow: hidden;
  backdrop-filter: blur(12px);
}

.buttons button a {
  width: 5rem;
  height: 2rem;
}

.imageProj {
  opacity: 0.7;
}

.card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  top: 0;
  left: 0;
  border-radius: 0;
}

.pulse {
  display: none;
}

.container1 {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}

.proj {
  width: 100%;
}

@media screen and (max-width: 1080px) {
  .projects {
    min-width: 100%;
  }

  .row {
    margin-left: 0;
    margin-right: 0;
  }

  .card {
    width: 300px;
    height: 190px;
    background: #fff;
    position: relative;
    display: flex;
    align-items: flex-end;
    box-shadow: 0px 7px 10px rgba(0, 0, 0, 0.5);
    transition: 0.5s ease-in-out;
    border-radius: 0;
  }

  .hover {
    position: relative;
    padding-top: 2rem;
    top: 0;
    right: 32%;
    display: flex;
    z-index: 1;
    color: black;
  }
  .card:hover {
    transform: none;
  }

  .card img{
  border-radius: 0;
  }

  .card .date {
    position: relative;
    z-index: 3;
    color: #1f2833;
    opacity: 0;
    transform: translateY(30px);
    transition: 0.5s all;
    z-index: 3;
    text-align: center;
    width: 100%;
  }
  .date p {
    font-size: 10px;
  }
  .date h1 {
    font-size: 25px;
    font-weight: bold;
  }

  .hover {
    top: 12%;
    display: flex;
    z-index: 1;
    color: black;
    width: 35%;
  }
}
@media screen and (max-width: 650px) {
  .proj {
    height: 100%;
  }

  .boo {
    display: flex;
    justify-content: center;
    margin: 0;
  }
  .card {
    width: 350px;
    height: 200px;
    background: #fff;
    position: relative;
    display: flex;
    align-items: flex-end;
    box-shadow: 0px 7px 10px rgba(0, 0, 0, 0.5);
    transition: 0.5s ease-in-out;
    border-radius: 0;
  }

  .card:hover {
    transform: none;
  }

  .card img{
    border-radius: 0;
  }

  .card .date {
    position: relative;
    z-index: 3;
    color: #1f2833;
    opacity: 0;
    transform: translateY(30px);
    transition: 0.5s all;
    z-index: 3;
    text-align: center;
    width: 100%;
  }
  .date p {
    font-size: 12px;
  }

  .hover {
    top: 12%;
    display: flex;
    z-index: 1;
    color: black;
    width: 35%;
  }

  svg {
    display: none;
  }

  .pulse {
    visibility: visible;
    height: 130px;
    width: 130px;
    background: linear-gradient(#00000077, #0000007a);
    position: absolute;
    left: -5px !important;
    /* right: 224px !important; */
    /* right: 224px !important; */
    top: 40%;
    bottom: 0;
    border-radius: 50%;
    display: grid;
    place-items: center;
    font-size: 30px;
    color: white;
  }

  .pulse:before,
  .pulse:after {
    content: "";
    position: absolute;
    height: 100%;
    width: 100%;
    background-color: #00000081;
    border-radius: 50%;
    z-index: -1;
    opacity: 0.7;
  }

  .pulse:before {
    animation: pulse 2s eas-out infinite;
  }

  .pulse:after {
    animation: pulse 1s 1s ease-out infinite;
  }

  @keyframes pulse {
    100% {
      transform: scale(1.5);
      opacity: 0;
    }
  }

  .projects {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
</style>
