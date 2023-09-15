<template>
  <div id="edu">
    <div id="education" data-aos="zoom-in" data-aos-duration="800">
      <div class="education-skills">
        <h1>Education and Experience</h1>
      </div>
      <div class="hold-desc">
        <h1>My Journey</h1>
        <hr />
        <div class="desc">
          <div class="para">
            <p>
              I was once a high school student who knew little about IT, but my
              growing interest led me to take a bold step into the IT world
              after graduation, reshaping my career goals.
            </p>
            <p>
              Despite starting college for IT, financial difficulties forced me
              to leave after a year. Undaunted, I took on various jobs, learning
              valuable skills such as teamwork, discipline, and problem-solving.
            </p>
            <p>
              During this journey, I joined Life's Choice Academy, which
              reignited my passion for IT. At the Academy, I gained technical
              knowledge, personal growth, and mentorship, reminding me of the
              importance of pursuing one's passions.
            </p>
            <p>
              Now, I'm fully committed to a rewarding IT career. My journey,
              filled with challenges, has shaped me from a high school novice to
              a dedicated professional. I believe my dedication will not only
              bring personal happiness but also contribute meaningfully to the
              ever-evolving world of technology.
            </p>
          </div>
          <div class="gif">
            <!-- <img src="../assets/gif/animation_lmhljg2x_small.gif" alt="" /> -->
            <video autoplay loop muted playsinline>
              <source src="../assets/gif/animation_lmhl6skh.mp4" type="video/mp4">
            </video>
          </div>
        </div>
      </div>
      <div class="education">
        <div class="co">
          <div class="row edu" style="display: flex; justify-content: center">
            <div class="col mt-5 boo" v-for="item in resume" :key="item">
              <div class="card bo">
                <div class="card-body date">
                  <h1>{{ item.year }}</h1>
                  <h2>{{ item.place }}</h2>
                  <p>{{ item.desc }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="education-skills">
        <h1>Skills</h1>
      </div>
      <div class="education">
        <div class="co">
          <div class="row ski" style="display: flex; justify-content: center">
            <div class="col mt-5 skil" v-for="item in skill" :key="item">
              <div class="card bod">
                <div class="card-body lang">
                  <img :src="item.image" alt="..." />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="li"></div>
  </div>
</template>

<script>
export default {
  name: "Education",
  data() {
    return {
      resume: [
        {
          year: "2023",
          place: "Life's Choice Academy",
          desc: "Assigned as a Lecturer Assistant for the new Cohort",
        },
        {
          year: "2022",
          place: "Life's Choice Academy",
          desc: "Currently studying IT (Information Technology), at Life's Choice Academy.",
        },
        {
          year: "2021",
          place: "Mr.Price",
          desc: "Started working at Mr.Price Retail Store, as a retail sales assistance for 1 year 6 months.",
        },
        {
          year: "2020",
          place: "Leads Capital Group",
          desc: "Started working at Leads Capital Group, as a call center agent for 6 months.",
        },
        {
          year: "2020",
          place: "Southern Winds",
          desc: "Started working at Southern Winds, a Credit sales company, worked for 1 month.",
        },
        {
          year: "2019",
          place: "Pearson Instituition",
          desc: "Studied first year of IT (Information Technology), at Pearsons Instituition.",
        },
        {
          year: "2018",
          place: "Cedar High School",
          desc: "Graduated from Cedar High School of Arts.",
        },
      ],
      skill: [
        {
          image: "https://i.postimg.cc/tgFnNQM6/pngegg-1.png",
        },
        {
          image: "https://i.postimg.cc/4xDGBvbj/css.png",
        },
        {
          image: "https://i.postimg.cc/25nDJq0y/javascript.png",
        },
        {
          image: "https://i.postimg.cc/Hnk1V6d8/Bootstrap-logo-svg.png",
        },
        {
          image: "https://i.postimg.cc/JnmDT6f2/pngegg-2.png",
        },
        {
          image: "https://i.postimg.cc/CL68F48R/pngegg-3.png",
        },
        {
          image: "https://i.postimg.cc/qMrjXN3Q/node-js-1174925.webp",
        },
      ],
    };
  },
};
</script>

<style scoped>
.bod {
  width: 17rem;
  height: 13rem;
  text-align: center;
  background-color: wheat;
  border: 2px solid black;
  transition: transform 0.2s;
}

.hold-desc {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.para {
  /* border: 2px solid red; */
  width: 50%;
  /* justify-content: start; */
}

.desc {
  /* border: 2px solid red; */
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-left: 5rem;
  padding-right: 5rem;
  gap: 3rem;
}

.gif {
  width: 40%;
  height: 25rem;
  /* border: 2px solid black; */
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
}

.gif video {
  height: 100%;
  border-radius: 50%;
}
.desc p {
  width: 100%;
  height: 100%;
  text-align: start;
  display: flex;
  justify-content: center;
  align-items: center;
  /* border: 2px solid black; */
  /* border-right: 8px solid #66fcf232; */
  /* padding: 5rem; */
}
.bo {
  width: 20rem;
  height: 15rem;
  text-align: center;
  background-color: wheat;
  border: 2px solid black;
  transition: transform 0.2s;
}

.education-skills {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}
.skills {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 3rem;
  text-decoration: underline;
}

.card:hover {
  background: white;
  transition: 0.5s;
  box-shadow: 0 20px 30px rgba(0, 0, 0, 0.7);
  transform: scale(1.1);
  overflow: hidden;
}

.li {
  margin-top: 5rem;
  margin-left: 5rem;
  margin-right: 5rem;
  border-bottom: 1px solid black;
}

#education {
  /* margin-left: 5rem;
  margin-right: 5rem; */
  justify-content: center;
  align-items: center;
  display: inline-block;
}

.co {
  display: flex;
  justify-content: center;
  align-items: center;
}

.date{
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 5px;
}


.card-body img {
  width: 15rem;
  height: 11rem;
}

.lang{
  display: flex;
  justify-content: center;
  align-items: center;
}

.education {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2px;
  padding-bottom: 3rem;
}
.ski{
  width: 75% !important;
}

.skil {
  display: flex;
  justify-content: center;
  align-items: center;
}

.boo {
  margin: 1px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.row{
  margin-left: 0;
  margin-right: 0;
  width: 90%;
}

#edu{
  height: 100%;
}

@media screen and (max-width: 650px) {
  #education {
    margin: 0;
  }

  .co {
    display: flex;
    justify-content: center;
  }
  .boo {
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .skil {
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .bo {
    width: 20rem;
  }
  .bod {
    width: 20rem;
  }
  .hold-desc {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.hold-desc h1{
  text-align: start !important;
  width: 100%;
  padding-left: 1rem;
  text-decoration: underline;
}

.para {
  /* border: 2px solid red; */
  width: 100%;
  /* text-align: center; */
  /* justify-content: start; */
}

.desc {
  /* border: 2px solid red; */
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding-left: 0;
  padding-right: 0;
}

.gif {
  width: 100%;
  height: 15rem;
  /* border: 2px solid black; */
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
}

.gif video {
  height: 100%;
  border-radius: 50%;
}
.desc p {
  width: 100%;
  height: 100%;
  text-align: start !important;
}
}

@media screen and (max-width: 1080px) {
  .boo {
    display: flex;
    justify-content: center;
    margin: 0;
  }
  .skil {
    display: flex;
    justify-content: center;
    margin: 0;
  }
  .hold-desc {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.para {
  /* border: 2px solid red; */
  width: 100%;
  /* text-align: center; */
  /* justify-content: start; */
}

.desc {
  /* border: 2px solid red; */
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  /* padding-left: 5rem;
  padding-right: 5rem; */
}

.gif {
  width: 100%;
  height: 15rem;
  /* border: 2px solid black; */
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
}

.gif video {
  height: 100%;
  border-radius: 50%;
}
.desc p {
  width: 100%;
  height: 100%;
  text-align: center;
  /* display: flex;
  justify-content: center;
  align-items: center; */
  /* border: 2px solid black; */
  /* border-right: 8px solid #66fcf232; */
  /* padding: 5rem; */
}
}
</style>
