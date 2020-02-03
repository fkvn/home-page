<template>
  <b-navbar toggleable="lg">
    <b-navbar-brand href="#"
      ><img fluid-grow alt="Vue logo" src="../assets/logo.png"
    /></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Home</b-nav-item>
        <b-nav-item href="#">About</b-nav-item>
        <b-nav-item href="#">Porfolio</b-nav-item>
        <b-nav-item href="#">Projects</b-nav-item>
        <b-nav-item href="#">Articles</b-nav-item>
        <b-nav-item href="#">Contact</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-input-group>
            <b-form-input
              size="sm"
              class="mr-sm-2"
              placeholder="Search"
            ></b-form-input>
            <b-input-group-append>
              <b-button size="sm" class="my-0 ml-1" type="submit"
                >Search
              </b-button>
            </b-input-group-append>
          </b-input-group>
        </b-nav-form>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: "Navbar",
  props: {}
};
</script>

<style scoped>
.navbar-light {
  background-color: #222930;
}
.navbar-light .navbar-brand img {
  width: 3em;
}

.navbar-light .navbar-nav .nav-link {
  margin-right: 3em;
  color: white;
}

.navbar-light .navbar-toggler {
  background-color: white;
  font-size: 0.6em;
}
</style>
