<template>
  <div id="testimonials">
    <div class="all-testimonials">
      <h1>Testimonials</h1>
    </div>
    <div class="testimonials">
      <div class="container1">
        <div class="row bord mx-3">
          <div
            class="col-sm-5 mx-5 my-3 testos"
            v-for="test in testies"
            :key="test"
          >
            <div class="im">
              <img :src="test.image" alt="" />
            </div>
            <div class="boda">
              <h2>{{ test.name }}</h2>
              <p>{{ test.testimonial }}</p>
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
  name: "Testimonials",
  data() {
    return {
      testies: [
        {
          name: "Abdul Abrahams",
          testimonial:
            "An absolute great guy, hard worker and a goal driven personality. Always takes on the next challenge that comes to him and knows how to communicate and socialise in his surroundings.",
          image: "https://i.postimg.cc/wjyYs0yS/DSC-3491-1.jpg",
        },
        {
          name: "Aneeqa Brown",
          testimonial:
            "Abdul-Azeez is a highly thought intellectual who is hardworking and ambitious, providing a helping hand. He has great communication and leadership skills, especially his creativity, which are essential for a company.",
          image: "https://i.postimg.cc/FzTX06xQ/DSC-3548.jpg",
        },
        {
          name: "Mu-eed Brown",
          testimonial:
            "Mr. Azeez is a very ambitious person. He will do his best to create whatever he pictures in his mind. He can be very confident, so communication and working with him will be beneficial.",
          image: "https://i.postimg.cc/Nf0cQggG/DSC-3535.jpg",
        },
        {
          name: "Jake Jansen",
          testimonial:
            "Abdul is a very trustworthy individual. Someone you can definitely count on to get the job or task done effectively. He is also very creative and packing ideas. Works really well in groups, communicates well and is open to other peoples ideas.",
          image: "https://i.postimg.cc/cJt10dBt/1680520602045.jpg",
        },
        {
          name: "Nikita Ramawoothar",
          testimonial:
            "Azeez is a very creative individual and is always pleasant company to have within the workplace. He is not only helpful but also an exceptional developer that you can always count on to get some ideas and inspiration from.",
          image: "https://i.postimg.cc/nrRNXDHF/DSC-3525.jpg",
        },
        {
          name: "Karen Bruce",
          testimonial:
            "Abdul is a fast learner and dedicated worker. He always seeks more knowledge and encourages himself to gain more experience. He brings a light and motivated energy to the work environment. As an asset to your company, he will ensure that all goals are being achieved.",
          image: "https://i.postimg.cc/3xRJfXyB/karen.jpg",
        },
      ],
    };
  },
};
</script>

<style>
.testimonials {
  /* height: 100vh; */
  display: flex;
  justify-content: center;
  align-items: center;
  /* border-bottom: 1px solid black; */
  margin-left: 5rem;
  margin-right: 5rem;
}

.all-testimonials {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}

.testos {
  display: flex;
  justify-content: center;
  align-items: center;
  /* width: 15rem; */
  border: 3px solid black;
  height: 17rem;
  /* flex-wrap: wrap; */
  background-color: white;
}

.im img {
  width: 14rem;
  height: 18rem;
}

.im {
  border: 3px solid black;
}

.boda {
  padding-left: 1rem;
}

@media screen and (max-width: 650px) {
  /* #testimonials{
    display: flex;
    justify-content: center;
    align-items: center;
  } */
  .boda {
    padding-left: 0;
  }
  .bord {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 18rem;
  }
  /* .im{
    width: 7rem;
  } */
  .im img {
    width: 10rem;
    height: 10rem;
  }
  .testos {
    display: flex;
    justify-content: center;
    align-items: center;
    /* width: 15rem; */
    border: 3px solid black;
    height: 30rem;
    flex-wrap: wrap;
    background-color: white;
    text-align: center;
  }
}
</style>