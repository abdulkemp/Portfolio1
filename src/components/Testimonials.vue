<template>
  <div id="testimonials" data-aos="fade-down" data-aos-duration="800">
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
          image: "https://i.postimg.cc/V63vzLwS/DSC-3491.jpg",
        },
        {
          name: "Aneeqa Brown",
          testimonial:
            "Abdul-Azeez is a highly thought intellectual who is hardworking and ambitious, providing a helping hand. He has great communication and leadership skills, especially his creativity, which are essential for a company.",
          image: "https://i.postimg.cc/kM0RmwMj/DSC-3549.jpg",
        },
        {
          name: "Mu-eed Brown",
          testimonial:
            "Mr. Azeez is a very ambitious person. He will do his best to create whatever he pictures in his mind. He can be very confident, so communication and working with him will be beneficial.",
          image: "https://i.postimg.cc/HxKHbSvF/DSC-3536.jpg",
        },
        {
          name: "Nikita Ramawoothar",
          testimonial:
            "Azeez is a very creative individual and is always pleasant company to have within the workplace. He is not only helpful but also an exceptional developer that you can always count on to get some ideas and inspiration from.",
          image: "https://i.ibb.co/b1jmDwx/DSC-3523.jpg",
        },
        {
          name: "Joel Mukanya",
          testimonial:
            "Abdul-Azeez Kemp is creative, well-behaved, dedicated, and a goal-getter; he enjoys working with his peers and works well on his project. He has learned a variety of skills, such as web development, backend, and more.",
          image: "https://i.ibb.co/NSq5b0x/Screenshot-2024-03-03-163329.png",
        },
        {
          name: "Candice Amon",
          testimonial:
            "Abdul, an intern, was punctual, committed, and disciplined. He successfully executed tasks and was available for assistance. Abdul's gentle personality and teamwork skills made him a pleasure to work with and would be hired again. If you have any questions, contact 0785756863.",
          image: "https://i.ibb.co/RbBdNJD/Screenshot-2024-03-03-163434.png",
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
  text-align: center;
  width: 100%;
}

@media screen and (max-width: 1400px) {
  .testos {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 25rem;
    border: 3px solid black;
    background-color: white;
    text-align: center;
  }

  .im img {
    width: 12rem;
    height: 16rem;
  }

  .boda {
    /* width: 100%;
    height: 100%; */
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .boda p {
    font-size: 12px;
  }

  .boda h2 {
    font-size: 20px;
    font-weight: bold;
  }

  .bord {
    display: flex;
    justify-content: center;
  }
}
@media screen and (max-width: 1200px) {
  .testos {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    border: 3px solid black;
    background-color: white;
    text-align: center;
  }
  .bord {
    display: flex;
    justify-content: center;
  }
}
@media screen and (max-width: 650px) {
  .boda {
    padding: 0;
  }
  .bord {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 18rem;
  }

  .im img {
    width: 10rem;
    height: 10rem;
  }
  .testos {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 15rem;
    border: 3px solid black;
    height: 30rem;
    flex-wrap: wrap;
    background-color: white;
    text-align: center;
  }
}
</style>
