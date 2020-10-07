<template>
  <div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">KoolKeeper</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="">Document</b-nav-item>
        <b-nav-item href="#">Search</b-nav-item>
        <b-nav-item href="#">Search Type</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
          <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
          <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
        </b-nav-form>
        <b-nav-item href="">Preferences</b-nav-item>
        <b-nav-item href="">Sign Out</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
  name: 'KoolKeeper',
  props: {
    aaa: String
  },
   
}
</script>
<style>
.bg-info {
    background-color: #17a2b8 !important;
    line-height: 2.5;
    font-size: 1.2rem;
    font-weight: 500;
}
</style>