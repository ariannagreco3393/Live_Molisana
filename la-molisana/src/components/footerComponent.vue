<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col text-center">
          <img src="@/assets/img/la-molisana-logo.png" alt="" />
        </div>
        <div class="col">
          <h3>Pastificio</h3>
          <ul>
            <li>Il pastificio</li>
            <li>Grano</li>
            <li>Filiera</li>
            <li>100 anni di pasta</li>
            <li>Storia della pasta</li>
          </ul>
        </div>
        <div class="col">
          <h3>Pastificio</h3>
          <ul>
            <li>Il pastificio</li>
            <li>Grano</li>
            <li>Filiera</li>
            <li>100 anni di pasta</li>
            <li>Storia della pasta</li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "footerComponent",
};
</script>

<style lang="scss" scoped>
footer {
  background-image: url("@/assets/img/footer-montagne-bottom.jpg");
  background-position: bottom;
  background-repeat: no-repeat;
  height: 400px;
  padding-top: 3rem;
  padding-left: 2rem;
  padding-right: 2rem;

  h3 {
      margin-bottom: 1.25rem ;
  }

  ul {
    list-style: none;
    line-height: 1.5rem;
  }
}
</style>