<template>
  <div class="edu">
    <div id="education" data-aos="zoom-in" data-aos-duration="800">
      <div class="education-skills">
        <h1>Education and Experience</h1>
      </div>
      <div class="education" data-aos="fade-left" data-aos-duration="800">
        <div class="co">
          <div class="row edu" style="display: flex;justify-content: center;">
            <div class="col mt-5 boo" v-for="item in resume" :key="item">
              <div class="card bo">
                <div class="card-body">
                  <h1>{{ item.year }}</h1>
                  <h2>{{ item.place }}</h2>
                  <p>{{ item.desc }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    

    <div class="education-skills" data-aos="zoom-in" data-aos-duration="800">
      <h1>Skills</h1>
    </div>
    <div class="education" data-aos="fade-right" data-aos-duration="800">
      <div class="co">
        <div class="row ski" style="display: flex;justify-content: center;">
          <div class="col mt-5 skil" v-for="item in skill" :key="item">
            <div class="card bod">
              <div class="card-body">
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

.li{
  margin-top: 5rem;
  margin-left: 5rem;
  margin-right: 5rem;
  border-bottom: 1px solid black;
}

#education {
  margin-left: 5rem;
  margin-right: 5rem;
  justify-content: center;
  align-items: center;
  display: inline-block;
}
.skill {
  display: flex;
  justify-content: center;
  align-items: center;
}
.co {
  display: flex;
  justify-content: center;
  align-items: center;
}

.my-skills{
  margin-left: 5rem;
  margin-right: 5rem;
}

.card-body img {
  width: 15rem;
  height: 11rem;
}

.education {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2px;
  padding-bottom: 3rem;
}

.ski{
  width: 100%;
  height: 100%;
}

.skil{
  display: flex;
  justify-content: center;
  align-items: center;
}
.boo{
  margin: 1px;
  display: flex;
  justify-content: center;
  align-items: center;
}

@media screen and ( max-width: 650px) {
  #education{
    margin: 0;
    
  }

  .co{
    display: flex;
    justify-content: center;
  }
  .boo{
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .skil{
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .bo{
    width: 20rem;
  }
  .bod{
    width: 20rem;
  }
}

@media screen and ( max-width: 1080px) {
  .boo{
    display: flex;
    justify-content: center;
    margin: 0;
  }
  .skil{
    display: flex;
    justify-content: center;
    margin: 0;
  }
 

}
</style>