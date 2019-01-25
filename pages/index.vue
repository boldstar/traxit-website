<template>
  <div 
    class="landing-page"
  >
    <header>
      <LandingNav />
    </header>
    <section 
      id="hero"
      class="hero" 
    >
      <div class="hero-background">
        <div class="hero-content">
          <h2 class="header">TRAXIT</h2>
          <h5 class="slogan">Tracking What Matters</h5>
          <button
            class="hero-btn"
          >
            Request Demo
          </button>
        </div>
      </div>
    </section>
    <section 
      id="mission"
      class="mission" 
    >
      <div class="mission-background">
        <div class="mission-content">
          <h2 class="mission-header">Our Mission</h2>
          <p class="mission-statement">
            We believe that to launch your self to the next level, as a CPA, you and your team need a tool that will give you the ability to track and manage what is happening. Traxit is here to meet that need. Built specifically for CPA's, Traxit will serve as the process manager of any engagement whether it be for tax returns or bookkeeping. We understand that finding software that does what it says can be difficult, but we hope with Traxit being only built to manage a CPA firm, you and your team will get exactly what you have been looking for.
          </p>
        </div>
      </div>
    </section>
    <section 
      id="features"
      class="features" 
    >
      <div class="features-background">
        <div class="features-content">
          <h2 class="features-header">Features</h2>
          <div class="features-body">
            <div class="card-body shadow">
              <h3>Dashboard<i class="fas fa-tachometer-alt ml-3 text-primary"></i></h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia iste tempore voluptatibus ut cum dicta ad minus, sapiente totam inventore eaque facilis itaque, explicabo ipsa voluptates facere quo natus! Est.</p>
              <nuxt-link to="/features/dashboard">Learn More</nuxt-link>
            </div>
            <div class="card-body shadow">
              <h3>Workflows<i class="fas fa-route ml-3 text-primary"></i></h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia iste tempore voluptatibus ut cum dicta ad minus, sapiente totam inventore eaque facilis itaque, explicabo ipsa voluptates facere quo natus! Est.</p>
              <nuxt-link to="/features/workflows">Learn More</nuxt-link>
            </div>
            <div class="card-body shadow">
              <h3>Reports<i class="fas fa-database ml-3 text-primary"></i></h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia iste tempore voluptatibus ut cum dicta ad minus, sapiente totam inventore eaque facilis itaque, explicabo ipsa voluptates facere quo natus! Est.</p>
              <nuxt-link to="/features/reports">Learn More</nuxt-link>
            </div>
            <div class="card-body shadow">
              <h3>Manage<i class="fas fa-clipboard ml-3 text-primary"></i></h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia iste tempore voluptatibus ut cum dicta ad minus, sapiente totam inventore eaque facilis itaque, explicabo ipsa voluptates facere quo natus! Est.</p>
              <nuxt-link to="/features/manage">Learn More</nuxt-link>
            </div>
            <div class="card-body shadow">
              <h3>Tasks<i class="fas fa-tasks ml-3 text-primary"></i></h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia iste tempore voluptatibus ut cum dicta ad minus, sapiente totam inventore eaque facilis itaque, explicabo ipsa voluptates facere quo natus! Est.</p>
              <nuxt-link to="/features/tasks">Learn More</nuxt-link>
            </div>
            <div class="card-body shadow">
              <h3>Engagements<i class="far fa-folder-open ml-1 text-primary"></i></h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia iste tempore voluptatibus ut cum dicta ad minus, sapiente totam inventore eaque facilis itaque, explicabo ipsa voluptates facere quo natus! Est.</p>
              <nuxt-link to="/features/engagements">Learn More</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section 
      id="pricing"
      class="pricing" 
    >
      <h2 class="pricing-header">Pricing</h2>
      <div class="pricing-body">
        <div class="card shadow">
          <div class="card-header bg-white">
            <span>Hobby</span>
          </div>
          <div class="card-body">
            <ul class="subscription-features"> 
              <li class="d-flex justify-content-between"><span>Workflows</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Reports</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Tasks</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Team Members</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Engagements</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Support</span><i class="fas fa-check align-self-center"></i></li>   
            </ul>
          </div>
          <div class="card-footer bg-white">
            <div>
              <button class="btn btn-outline-secondary btn-sm text-primary">Demo</button>
            </div>
            <span>Price: $250</span>
          </div>
        </div>
        <div class="card shadow">
          <div class="card-header bg-white">
            <span>Professional</span>
          </div>
          <div class="card-body">
            <ul class="subscription-features"> 
              <li class="d-flex justify-content-between"><span>Workflows</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Reports</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Tasks</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Team Members</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Engagements</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Support</span><i class="fas fa-check align-self-center"></i></li> 
            </ul>
          </div>
          <div class="card-footer bg-white">
            <div>
              <button class="btn btn-outline-secondary btn-sm text-primary">Demo</button>
            </div>
            <span>Price: $500</span>
          </div>
        </div>
        <div class="card shadow">
          <div class="card-header bg-white">
            <span>Firm</span>
          </div>
          <div class="card-body">
            <ul class="subscription-features"> 
              <li class="d-flex justify-content-between"><span>Workflows</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Reports</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Tasks</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Team Members</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Engagements</span><i class="fas fa-check align-self-center"></i></li>
              <li class="d-flex justify-content-between"><span>Support</span><i class="fas fa-check align-self-center"></i></li> 
            </ul>
          </div>
          <div class="card-footer bg-white">
            <div>
              <button class="btn btn-outline-secondary btn-sm text-primary">Demo</button>
            </div>
            <span>Price: $750</span>
          </div>
        </div>
      </div>
    </section>
    <section 
      id="contact"
      class="contact" 
    >
      <div class="contact-background">
        <div class="contact-content">
          <h2 class="contact-header">Contact</h2>
          <div class="contact-form card-body shadow">
            <img 
              src="~/assets/TraxitHeroLogo.png"
              class="form-logo"
            >
            <form data-netlify="true">
              <input 
                type="text" 
                class="form-control" 
                placeholder="Business Name"
                name="Business Name"
              >
              <input 
                type="text" 
                class="form-control" 
                placeholder="Name"
                name="Individuals Name"
              >
              <input 
                type="text" 
                class="form-control" 
                placeholder="Email"
                name="Email"
              >
              <input 
                type="text" 
                class="form-control" 
                placeholder="Phone"
                name="Phone Number"
              >
              <textarea 
                type="text" 
                class="form-control mb-3" 
                placeholder="Message"
                name="Message"
                col="8"
              >
              </textarea>
              <button 
                class="contact-btn"
                type="submit">
                Request Demo
              </button>
            </form>
          </div>
          <footer>
            &copy;2019 All Rights Reserved Alytix Ventures LLC
          </footer>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import LandingNav from '~/components/LandingNav'

export default {
  name: 'Index',
  components: {
    LandingNav
  },
  data() {
    return {
      
    }
  },
  computed: {

  },
  mounted() {
    
  },
  beforeDestroy() {

  },
  methods: {

  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Raleway');

:root {
  --blue-color: #0077ff;
  --pink-color: #e2115a;
  --gray-color: #7a7a7a;
}

html {
  overflow-x: hidden;
  scroll-behavior: smooth;
}

* {
  font-family: 'Raleway', sans-serif;
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

header {
  position: absolute;
  z-index: 1;
  width: 100%;
}

.hero-logo {
  height: 50px;
  width: 50px;
}

.hero {
  position: relative;
  min-height: 100vh;
  min-width: 100vw; 
}

.hero-background {
  position: absolute;
  width: 100vw;
  height: 100vh;
  background-image: url('~assets/TraxitHero.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  display: flex;
  justify-content: center;
}

.hero-content {
  align-self: center;
  text-align: center;
  margin-bottom: 100px;
}

.header {
  color: #0077ff;
  font-size: 7rem;
  font-weight: 600;
  letter-spacing: 1.5px;
}

.slogan {
  font-size: 2rem;
  margin-bottom: 35px;
  color: var(--gray-color);
}

.hero-btn {
  cursor: pointer;
  border: 3px solid #0077ff;
  border-radius: 10px;
  padding: 5px 90px;
  background: transparent;
  font-size: 1.5rem;
  font-weight: 600;
  color: var(--pink-color);
}

.hero-btn:hover {
  background-color: var(--blue-color);
  color: white;
}

/* Hero Media Query */
    
@media only screen and (max-width: 1000px){
    li a {
    text-decoration: none;
    margin-left: 25px;
    letter-spacing: 1px;
    color: var(--gray-color);
    font-weight: 400;
    font-size: 12px;
  }

  .hero-logo {
    height: 35px;
    width: 35px;
  }

  .hero {
    min-height: 100vh;
    min-width: 100vw;
    background-image: linear-gradient(white 50%, var(--blue-color) 100%) 
  }

  .hero-background {
    width: 100vw;
    height: 100vh;
    background-image: none;
    display: flex;
    justify-content: center;
  }

  .hero-content {
    align-self: center;
    text-align: center;
    margin-bottom: 100px;
  }

  .header {
    color: #0077ff;
    font-size: 5rem;
    font-weight: 600;
    letter-spacing: 1.5px;
  }

  .slogan {
    font-size: 1.5rem;
    margin-bottom: 35px;
    color: var(--gray-color);
  }

  .hero-btn {
    cursor: pointer;
    border: 3px solid #0077ff;
    border-radius: 10px;
    background: transparent;
    padding: 5px 50px;
    font-size: 1.5rem;
    font-weight: 600;
    color: var(--gray-color);
  }
}
/*End of Hero Media Query*/

.mission {
  position: relative;
  height: 100vh;
  display: flex;
  justify-content: center;
  background-image: linear-gradient(var(--blue-color) 100%, white 50%);
  color: white;
}

.mission-background {
  width: 100vw;
  height: 100vh;
  background-image: url('~assets/RocketLaunchingMissionBackground.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  display: flex;
  justify-content: center;
}

.mission-content {
  width: 36%;
  text-align: center;
  margin-bottom: 200px;
}

.mission-header {
  margin: 50px 0;
  font-size: 3rem;
}

.mission-statement {
  font-size: 1.5rem; 
}

/* Mission media query*/
@media only screen and (max-width: 1000px){
  .mission-content {
    width: 80%;
    text-align: center;
    margin-bottom: 200px;
  }

  .mission-header {
    margin: 50px 0;
    font-size: 2rem;
  }

  .mission-statement {
    font-size: 1.0rem; 
  }

}
/*end of mission mediq query*/

.features {
  position: relative;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-image: linear-gradient(var(--blue-color) 100%, white 50%);
}

.features-background {
  width: 100vw;
  min-height: 100vh;
  background-image: url('~assets/TraxitFeaturesBackground.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

.features-header {
  margin: 50px 0;
  font-size: 3rem;
  color: var(--gray-color);
}

.features-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0 100px;
}

.features-body {
  display: flex;
  margin-top: 100px;
}

.features-content .card-body {
  border-radius: 10px;
  background-color: white;
}

.features-content .card-body:nth-child(odd) {
  margin-bottom: 75px;
}
.features-content .card-body:nth-child(even) {
  margin-top: 75px;
  margin-left: 25px;
  margin-right: 25px;
}

.features-content a {
  margin-left: auto;
}

.features-content a:hover {
  text-decoration: none;
}

/* Hero Media Query */
    
@media only screen and (max-width: 1000px){
  .features-header {
    margin-top: 15px;
    margin-bottom: 0;
    font-size: 1.5rem;
    color: var(--gray-color);
  }

  .features-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 0 10px;
  }

  .features-body {
    display: flex;
    flex-direction: column;
    margin-top: 0;
  }

  .card-body {
    background-color: white;
  }

  .card-body h3 {
    font-size: 1.5rem;
  }

  .features-content .card-body:nth-child(odd) {
    margin: 20px 0;
  }
  .features-content .card-body:nth-child(even) {
    margin: 0;
  }

}
/* End of features media query */

.pricing {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: var(--blue-color);
}

.pricing-header {
  margin: 50px 0;
  font-size: 3rem;
  color: white;
}

.pricing-body {
  margin-top: 50px;
  width: 100%;
  display: flex;
  justify-content: center;
}

.pricing .card {
  width: 20%;
}

.pricing .card:nth-child(even) {
  margin: 0 40px;
}

.card-header {
  font-size: 1.5rem;
  text-align: center;
  font-weight: 600;
  color: var(--blue-color);
}

ul {
  list-style: none;
}

.pricing ul li {
  font-size: 1.2rem;
  margin: 25px 0;
}

.pricing .card-footer {
  display: flex;
  justify-content: space-between;
  font-size: 1.5rem;
}


@media only screen and (max-width: 1000px){
  .pricing {
  position: relative; 
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: var(--blue-color);
  padding: 15px;
}

  .pricing-header {
    margin: 20px 0;
    font-size: 1.5rem;
    color: white;
  }

  .pricing-body {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
  }

  .pricing .card {
    width: 100%;
  }

  .card-header {
    font-size: 1.0rem;
    text-align: center;
    font-weight: 600;
    color: var(--blue-color);
  }

  .card-body {
    padding: 5px;
  }

  .pricing ul {
    font-size: .75rem;
    margin-bottom: 0;
  }

  .pricing ul li {
    font-size: .75rem;
    margin: 10px 0;
  }

  .pricing .card-footer {
    display: flex;
    justify-content: space-between;
    font-size: 1.0rem;
  }

  .pricing .card:nth-child(even) {
    margin: 10px 0;
  }

}
/* end of pricing media query */

.contact {
  position: relative;
  height: 100vh;
  display: flex;
  justify-content: center;
}

.contact-background {
  width: 100vw;
  height: 100vh;
  background-image: url('~assets/TraxitContactBackground.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

.contact-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.contact-header {
  margin: 35px 0;
  font-size: 3rem;
  color: white;
}

.contact-form {
  width: 30%;
  margin-top: 150px;
  border-radius: 10px;
}

.contact-form input {
  margin-bottom: 20px;
}

.form-logo {
  border-radius: 50%;
  height: 50px;
  width: 50px;
  margin-bottom: 20px;
  box-shadow: 0 2px 2px 2px  rgb(0,0,0,.15);
}

.contact-btn {
  cursor: pointer;
  width: 100%;
  padding: 10px 20px;
  background: transparent;
  border: 3px solid var(--blue-color);
  border-radius: 10px;
  color: var(--blue-color);
  font-weight: 600;
}

.contact-btn:hover {
  cursor: pointer;
  background: #0077ff59;
  color: var(--pink-color);
}

footer {
  margin-top: 125px;
  font-weight: 600;
}

@media only screen and (max-width: 1000px){
  .contact-header {
    margin: 35px 0;
    font-size: 1.5rem;
    color: white;
  }
  .contact-form {
    width: 100%;
    margin-top: 50px;
    border-radius: 0;
  }

  footer {
    margin: 30px;
    font-size: .75rem;
    font-weight: 400;
  }
}


</style>
