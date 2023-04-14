<template>
  <div id="education">
    <div class="education">
       <div class="education-skills">
        <h1>Education and Experience</h1>
       </div>
       <div >
        <div class="edu" v-for="item in resume" :key='item'>
            <div class="text">
                <h1>{{ item.year }}</h1>
                <h2>{{ item.place}}</h2>
                <p>{{ item.desc }}</p>
            </div>
        </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Education',
    data(){
        return{
            resume:[
                {
                    year: "2022",
                    place: "Life's Choice Academy",
                    desc: "Currently studying IT (Information Technology), at Life's Choice Academy."
                },
                {
                    year: "2021",
                    place: "Mr.Price",
                    desc: "Started working at Mr.Price Retail Store, as a retail sales assistance for 1 year 6 months."
                },
                {
                    year: "2020",
                    place: "Leads Capital Group",
                    desc: "Started working at Leads Capital Group, as a call center agent for 6 months."
                },
                {
                    year: "2020",
                    place: "Southern Winds",
                    desc: "Started working at Southern Winds, a Credit sales company, worked for 1 month."
                },
                {
                    year: "2019",
                    place: "Pearson Instituition",
                    desc: "Studied first year of IT (Information Technology), at Pearsons Instituition."
                },
                {
                    year: "2018",
                    place: "Cedar High School",
                    desc: "Graduated from Cedar High School of Arts."
                },

            ]
        }
    }
};
</script>

<style>
.education {
  /* height: 100vh; */
  
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid black;
  margin-left: 5rem;
  margin-right: 5rem;
}

.education-skills {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}

.edu{
    display: flex;
    justify-content: center;
    text-align: center;
}

</style>