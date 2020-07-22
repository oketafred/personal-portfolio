<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand href="#">Oketa Fred</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>        
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-nav-item href="https://www.facebook.com/oketa.fred" target="_blank">
              <vue-fontawesome class="facebook-icon" icon="facebook" size="1" color="lightgray"></vue-fontawesome>
            </b-nav-item>
            <b-nav-item href="https://twitter.com/oketafred" target="_blank">
              <vue-fontawesome class="twitter-icon" icon="twitter" size="1" color="lightgray"></vue-fontawesome>
            </b-nav-item>
            <b-nav-item href="https://www.linkedin.com/in/oketafred" target="_blank">
              <vue-fontawesome class="linkedin-icon" icon="linkedin" size="1" color="lightgray"></vue-fontawesome>
            </b-nav-item>
            <b-nav-item href="https://github.com/oketafred" target="_blank">
              <vue-fontawesome class="github-icon" icon="github" size="1" color="lightgray"></vue-fontawesome>
            </b-nav-item>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.facebook-icon {
  background-color: #4267b2;
  padding: 10px 13px;
  border: #4267b2;
  border-radius: 50%;
}
.twitter-icon {
  background-color: #1a91da;
  padding: 10px 12px;
  border: #1a91da;
  border-radius: 50%;
}
.linkedin-icon {
  background-color: #1f73b1;
  padding: 10px 12px;
  border: #1f73b1;
  border-radius: 50%;
}
.github-icon {
  background-color: #718096;
  padding: 10px 12px;
  border: #959da5;
  border-radius: 50%;
}
</style>
