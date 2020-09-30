<template>
  <div class="customer-exp">
    <div class="customer-container">
      <div class="customer-info">
        <div class="customer-header">
          <h1 class="header-orange">WE ARE WITH YOU</h1>
          <div class="header-gray">EVERY STEP OF THE WAY</div>
          <p>...</p>
        </div>
        <div class="customer-subsection">
          <p>
            We don’t design your office and leave. We stay and guide you until
            the project is finished, from the first drawing until the last piece
            of furniture is placed. And we'll make sure it's the office you
            always wanted.
          </p>
        </div>
      </div>
      <div class="customer-photo">
        <img src="../assets/help2.jpg" alt="#" />
      </div>
    </div>
    <CustomerRes />
  </div>
</template>

<script>
import CustomerRes from "./CustomerRes.vue";
export default {
  name: "CustomerExp",
  components: {
    CustomerRes,
  },
};
</script>
<style lang="scss">
.customer-exp {
  background-color: #e1bdab4d;
  height: 500px;
  text-align: left;
  .customer-container {
    display: flex;
  }

  .customer-info {
    margin-left: 300px;
    padding-top: 100px;
    .customer-header {
      font-size: 38px;
      font-weight: bold;
      .header-orange {
        color: #ec8550;
      }
      .header-gray {
        margin-top: -10px;
        color: black;
      }
    }
    .customer-subsection {
      max-width: 500px;
      font-size: 22px;
    }
  }
  .customer-photo {
    margin-left: 150px;
    img {
      height: 500px;
    }
  }
}
</style>
