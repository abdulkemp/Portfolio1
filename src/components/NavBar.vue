<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-danger">
    <div class="container-fluid">
      <a class="navbar-brand" href="#"><img src="https://i.postimg.cc/P5MBYm8V/oie-1216310-DR3-MTLHW.jpg" alt=""></a>
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
          <li class="nav-item">
            <router-link class="nav-link active" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link active" to="/">About Me</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link active" to="/"
              >Education And Experience</router-link
            >
          </li>
          <li class="nav-item">
            <router-link class="nav-link active" to="/">Projects</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link active" to="/"
              >Testimonials</router-link
            >
          </li>
          <li class="nav-item">
            <router-link class="nav-link active" to="/">Contact Me</router-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
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

.nav-item{
    padding-inline: 1rem;
}

.nav-item:hover{
    background-color: rgba(0, 0, 0, 0.086);
    color: white;
}
.navbar-brand img{
    width: 150px;
    height: 30px;
    border-radius: 5px;
}
</style>