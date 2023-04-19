<template>
  <div id="contact">
    <div class="contact">
      <div class="contact-me">
        <h1>Contact Me</h1>
      </div>
      <div class="di">
        <div class="container com">
          <form
            action="https://formspree.io/f/xrgvgwee"
            method="POST"
            class="row row-md-4 g-3"
          >
            <div class="col-md-6">
              <label for="validationDefault01" class="form-label"
                >First name</label
              >
              <input
                type="name"
                class="form-control"
                id="validationDefault01"
                placeholder="First Name"
                name="name"
                required
              />
            </div>
            <div class="col-md-6">
              <label for="validationDefault02" class="form-label"
                >Last name</label
              >
              <input
                type="name"
                class="form-control"
                id="validationDefault02"
                placeholder="Last Name"
                name="name"
                required
              />
            </div>
            <div class="col-md-6">
              <label for="validationDefault05" class="form-label"
                >Cellphone Number</label
              >
              <input
                type="name"
                class="form-control"
                id="validationDefault05"
                name="number"
                required
              />
            </div>
            <div class="col-md-6">
              <label for="validationDefault03" class="form-label">City</label>
              <input
                type="name"
                class="form-control"
                id="validationDefault03"
                name="name"
                required
              />
            </div>
            <div class="col-md-56">
              <label for="validationDefault04" class="form-label"
                >Province</label
              >
              <select
                class="form-select"
                id="validationDefault04"
                name="name"
                optional
              >
                <option selected disabled value="">Choose...</option>
                <option>Eastern Cape</option>
                <option>Free State</option>
                <option>Gauteng</option>
                <option>KwaZulu-Natal</option>
                <option>Limpopo</option>
                <option>Mpumalanga</option>
                <option>Northern Cape</option>
                <option>North West</option>
                <option>Western Cape</option>
              </select>
            </div>
            <div class="col-md-56">
              <label for="validationDefault04" class="form-label"
                >Provide Feedback Below</label
              >
              <textarea
                class="form-select"
                id="validationDefault04"
                name="text"
                required
              >
              </textarea>
            </div>
            <div class="col-12">
              <button class="btn btn-primary" type="submit">Submit form</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.contact {
  /* height: 100vh; */
  display: inline-block;
  justify-content: center;
  align-items: center;
  /* border-bottom: 1px solid black; */
  margin-left: 5rem;
  margin-right: 5rem;
}

.contact-me {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}

.heading {
  font-size: 8vw;
  color: white;
  text-shadow: 0 0 5px, 0 0 25px, 0 0 50px;
}
label {
  color: black;
}

.form-control{
  border: 1px solid black;
}
.form-select{
  border: 1px solid black;
}
@media screen and (max-width: 650px) {
  .com{
    width: 15rem;
  }
  #contact{
    display: flex;
    justify-content: center;
  }
}

/* .container{
    width: 76%;
} */
</style>