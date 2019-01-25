<template>
  <div class="form-container">
    <form class="form card shadow">
      <div class="d-flex justify-content-between">
        <nuxt-link 
          to="/"
          class="pb-3 ml-1 go-home-link"
        >
          <i class="fas fa-arrow-left"></i>
          Go Back Home
        </nuxt-link>
        <div class="align-self-center mr-3">
          <img 
            src="~assets/TraxitHeroLogo.png" 
            class="login-logo"
          >
        </div>
      </div>
      <div class="form-body">
        <div class="card-header">
          <span class="font-weight-bold">Company Domain Form</span>
        </div>
        <div class="card-body d-flex flex-column">
          <div class="input-group py-3">  
            <input 
              v-model="domain"
              type="text"
              class="form-control p-4"
              placeholder="company domain"
              aria-describedby="domain"
            >
            <div class="input-group-append">
              <span 
                id="domain"
                class="input-group-text p-2" 
              >
                .traxit.io
              </span>  
            </div>
          </div>
          <a 
            :href="'https://' + domain + '.traxit.io/login'"
            class="btn login-form-btn btn-block font-weight-bold"
          >
            Go
          </a>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'Login',
    data() {
        return {
            domain: ''
        }
    },
    methods: {

    }
}
</script>


<style>
.form-container {
    background-image: url('~assets/TraxitLoginBackground.png');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
}

.form { 
    width: 40%;
    align-self: center;
    padding: 30px;
    border: none;
    border-radius: 10px;
}

.form-body {
    background-color: white;
    border: 1px solid #707070;
    border-radius: 10px;
}

.login-logo {
  display: none;
}

.card-body {
  padding: 10px;
}

.login-form-btn {
    border: 1px solid black;
}

@media screen and (max-width: 1000px){
  .form { 
    width: 95%;
    align-self: center;
    padding: 0;
    border: none;
    border-radius: 10px;
  }

  .form-body {
    border: none;
  }

  .go-home-link {
    margin-left: 10px !important;
    padding-top: 15px;
  }

  .login-logo {
    display: block;
    height: 30px;
    width: 30px;
  }
}
</style>

