<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light nav-color fixed-top" data-aos="zoom-in" data-aos-duration="800">
      <div class="container-fluid">
        <a class="navbar-brand" href="#"
          ><img
            src="https://i.postimg.cc/B6cB3M2K/aak-high-resolution-logo-black-transparent.png"
            alt=""
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mb-2 mb-lg-0">
            <li class="nav-item" aria-expanded="false">
              <a href="#home" class="nav-link active">Home</a>
            </li>
            <li class="nav-item" aria-expanded="false">
              <a href="#about" class="nav-link active">About Me</a>
            </li>
            <li class="nav-item" aria-expanded="false">
              <a href="#education" class="nav-link active">Education and experience</a>
            </li>
            <li class="nav-item" aria-expanded="false">
              <a href="#projects" class="nav-link active">Projects</a>
            </li>
            <li class="nav-item" aria-expanded="false">
              <a href="#testimonials" class="nav-link active">Testimonials</a>
            </li>
            <li class="nav-item" aria-expanded="false">
              <a href="#contact" class="nav-link active">Contact Me</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
  
  <script>
export default {
  name: "NavBar",
};
</script>
<style>
.collapse {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}



.nav-item {
  padding-inline: 1rem;
}

.nav-item:hover {
  background-color: rgba(0, 0, 0, 0.086);
  color: white;
}
.navbar-brand img {
  width: 8rem;
  height: 1.2rem;
  margin-left: 1rem;
  border-radius: 5px;
}

.nav-color {
  background-color: rgba(255, 255, 255, 0.071);
  backdrop-filter: blur(12px);
  /* box-shadow: 0 20px 30px rgba(0, 0, 0, 0.15); */
}
nav {
  font-family: Georgia, "Times New Roman", Times, serif;
}
</style>