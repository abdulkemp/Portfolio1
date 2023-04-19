<template>
  <div>
    <div class="footer">
      <div class="linkings">
        <ul class="links" style="list-style: none;">
          <li class="nav-item">
            <a href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a href="#about">About Me</a>
          </li>
          <li class="nav-item">
            <a href="#projects">Projects</a>
          </li>
          <li class="nav-item">
            <a href="#education">Education and experience</a>
          </li>
        </ul>
        <ul class="links2" style="list-style: none;" >
          <li class="nav-item">
            <a href="#projects">Projects</a>
          </li>
          <li class="nav-item">
            <a href="#testimonials">Testimonials</a>
          </li>
          <li class="nav-item">
            <a href="#contact">Contact Me</a>
          </li>
        </ul>
        <div class="socials">
          <div class="nav-items">
            <a
              href="https://www.linkedin.com/search/results/all/?fetchDeterministicClustersOnly=true&heroEntityKey=urn%3Ali%3Afsd_profile%3AACoAADdFuPgB2I1G4-ah-IZhI8rEvVRGrD2fPCU&keywords=abdul%20azeez%20kemp&origin=RICH_QUERY_SUGGESTION&position=2&searchId=a6af49ed-c659-42e5-9839-eed0b3f28d1c&sid=67k"
              class="linkedin"
            >
              <ion-icon name="logo-linkedin"></ion-icon>
            </a>
          </div>
          <div class="nav-items">
            <a href="https://github.com/abdulkemp" class="github">
              <ion-icon name="logo-github"></ion-icon>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="lower">
      <div class="cop">
        <div class="copy">
          <h3>Copyright &copy Abdul-Azeez Kemp 2023</h3>
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "Footer",
};
</script>
  
  <style>
.footer {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  border-top: 2px solid black;
  margin-top: 3rem;
}
.footer .linkings .links {
  height: auto;
  max-width: 100%;
}

.nav-item li {
  text-decoration: none;
}

.links{
  margin-top: 1rem;
}

.links a {
  text-decoration: none;
  color: black;
}
.links2 a {
  text-decoration: none;
  color: black;
}
.lower .cop .cpoy {
  width: 15rem;
  height: auto;
  max-width: 100%;
}
/* .links2 {
  width: 15rem;
} */
.links2 .d-flex {
  /* max-width: 100%; */
  /* width: 15rem; */
  /* padding: 0 10px; */
}
.d-flex {
  margin-bottom: 1rem;
}
.cop {
  /* float: right; */
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  color: black;
  /* max-width: 95%; */
  /* margin: 0 auto; */
}
.copy h3 {
  font-size: 20px;
}
.linkings {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  width: 100rem;
  max-width: 95%;
  margin: 0 auto;
}
.lower {
  background-color: grey;
  /* margin-top: 2rem; */
}
.socials {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 25px;
  margin-top: 1rem;
  margin-bottom: 1rem;
}
.btn {
  color: black;
}
.socials a {
  background: transparent;
  color: black;
  border: transparent;
  font-size: 35px;
}

.nav-items {
  justify-content: center;
  align-items: center;
  width: 3rem;
}

.linkedin:hover {
  color: rgb(68, 99, 238);
}
.github:hover {
  color: rgb(185, 184, 184);
}
</style>