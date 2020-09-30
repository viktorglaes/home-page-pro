<template>
  <div class="customer-res">
    <div class="customer-container">
      <div class="columns">
        <div class="column">
          <div class="box">
            <article class="media">
              <div class="media-content">
                <img src="../assets/head-dots.png" alt="#" />
                <div class="content">
                  <h3>We Understand</h3>
                  <p>
                    <!-- <strong>Chat App</strong> <small>Vue</small> -->
                    We work with you to understand you needs for the new office.
                    We listen and we'll take into account your all of your
                    requirements.
                  </p>
                </div>
              </div>
            </article>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <article class="media">
              <div class="media-content">
                <img src="../assets/thumb.png" alt="#" />
                <div class="content">
                  <h3>We Help</h3>
                  <p>
                    <!-- <strong>Chat App</strong> <small>Vue</small> -->
                    Offering the minimum required is not part of our business
                    plan. We provide long-term guidance for designing decisions
                    as well as physical resources during an ongoing project.
                  </p>
                </div>
              </div>
            </article>
          </div>
        </div>
        <div class="column">
          <div class="box">
            <article class="media">
              <div class="media-content">
                <img src="../assets/handshake.png" alt="#" />
                <div class="content">
                  <h3>We Promise</h3>
                  <p>
                    <!-- <strong>Chat App</strong> <small>Vue</small> -->
                    We guarantee excellent execution. We will assemble the
                    perfect team to tailor to your design needs.
                  </p>
                </div>
              </div>
            </article>
          </div>
        </div>
      </div>
    </div>
    <b-button class="about-us">About Us</b-button>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.customer-res {
  height: 500px;
  text-align: center;

  .customer-container {
    justify-content: center;
    padding: 40px 100px 0px 100px;
  }

  .column {
    margin-right: 2.5rem;
    margin-left: 2.5rem;
    .box {
      min-height: 300px;
      max-height: 300px;
      width: 350px;
      box-shadow: none;
      p {
        text-align: left;
      }
    }
  }
  .about-us {
    background-color: #ec8550;
    color: white;
    border: none;
    margin-top: 25px;
  }
}
</style>
