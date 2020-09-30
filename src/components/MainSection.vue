<template>
  <div class="main-section">
    <div class="main-container">
      <div class="main-img">
        <img style="width: 60px" src="../assets/pencil-ruler.png" alt="#" />
      </div>
      <div class="main-info">
        <h3 class="main-header">
          We are experts in design and cultivating design changes
        </h3>
        <p class="main-subsection">
          Our main priority is the customer, and more specifically to help you
          create your dream office. We are at the forefront of design research,
          and we have the knowledge and expertise to design the office of the
          future.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainSection",
};
</script>

<style lang="scss">
.main-section {
  margin-top: 50px;
  height: 250px;
  background-color: #363636;
  color: white;
  text-align: left;
  .main-container {
    display: flex;
    padding-top: 80px;
    .main-img {
      margin-left: 400px;
      padding-top: 10px;
    }

    .main-info {
      margin-left: 80px;
    }

    .main-header {
      color: #ec8550;
      font-weight: bold;
      font-size: 18px;
    }

    .main-subsection {
      padding-top: 10px;
      max-width: 800px;
    }
  }
}
</style>
