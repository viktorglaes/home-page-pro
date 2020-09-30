<template>
  <div class="navbar-header">
    <div class="navbar-container">
      <div class="columns">
        <div class="column parent-column">
          <div class="columns">
            <div class="column">
              <b-dropdown :triggers="['hover']" aria-role="list">
                <a class="navbar-item" slot="trigger" role="button">
                  <span>PRODUCTS</span>
                  <b-icon icon="menu-down"></b-icon>
                </a>

                <b-dropdown-item aria-role="listitem"
                  >Office Material</b-dropdown-item
                >
                <b-dropdown-item aria-role="listitem">Desks</b-dropdown-item>
                <b-dropdown-item aria-role="listitem">Chairs</b-dropdown-item>
                <b-dropdown-item aria-role="listitem"
                  >Electronics</b-dropdown-item
                >
                <b-dropdown-item aria-role="listitem">Design</b-dropdown-item>
                <b-dropdown-item aria-role="listitem"
                  >Wallpaper</b-dropdown-item
                >
              </b-dropdown>
            </div>
            <div class="column">
              <b-dropdown :triggers="['hover']" aria-role="list">
                <a class="navbar-item" slot="trigger" role="button">
                  <span>ABOUT</span>
                  <b-icon icon="menu-down"></b-icon>
                </a>

                <b-dropdown-item aria-role="listitem">About Us</b-dropdown-item>
                <b-dropdown-item aria-role="listitem"
                  >Materials</b-dropdown-item
                >
                <b-dropdown-item aria-role="listitem">Events</b-dropdown-item>
              </b-dropdown>
            </div>
            <div class="column">
              <b-dropdown :triggers="['hover']" aria-role="list">
                <a class="navbar-item" slot="trigger" role="button">
                  <span>CAREERS</span>
                  <b-icon icon="menu-down"></b-icon>
                </a>

                <b-dropdown-item aria-role="listitem">Careers</b-dropdown-item>
                <b-dropdown-item aria-role="listitem"
                  >Open Positions</b-dropdown-item
                >
              </b-dropdown>
            </div>
          </div>
        </div>
        <div class="column is-one-fifth">
          <img src="../assets/citrusoffice2.png" alt="#" />
          <!-- <h3 class="logo-header">Citrus Office</h3> -->
        </div>
        <div class="column parent-column justify-right">
          <div class="columns">
            <div class="column">
              <b-dropdown :triggers="['hover']" aria-role="list">
                <a class="navbar-item" slot="trigger" role="button">
                  <span>INDUSTRY</span>
                  <b-icon icon="menu-down"></b-icon>
                </a>

                <b-dropdown-item aria-role="listitem">Global</b-dropdown-item>
                <b-dropdown-item aria-role="listitem">Domestic</b-dropdown-item>
                <b-dropdown-item aria-role="listitem">Local</b-dropdown-item>
              </b-dropdown>
            </div>
            <div class="column">
              <b-button type="is-dark">Contact</b-button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style lang="scss">
.navbar-header {
  height: 120px;
  .navbar-container {
    margin-left: 150px;
    margin-right: 150px;
  }
  .columns {
    background-color: white;

    .parent-column {
      padding-top: 45px;
    }
    img {
      width: 150px;
    }
  }
  .dropdown .navbar-item:hover {
    background-color: white;
    color: #4a4a4a;
  }
  .dropdown-content {
    background-color: #363636;

    a.dropdown-item {
      text-align: left;
      font-size: 16px;
      color: white;
      font-weight: bold;
    }
  }
  .dropdown-content a {
    color: white !important;
  }
  .dropdown-content a:hover {
    background: white !important;
    color: black !important;
    -webkit-transition: all 0.2s ease-in-out;
    -moz-transition: all 0.2s ease-in-out;
    transition: all 0.2s ease-in-out;
  }
}
</style>
