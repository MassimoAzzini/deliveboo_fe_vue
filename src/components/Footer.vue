<script>

export default{
  name: 'Footer',
  components: {
  },

  data() {
    return {
    }
  },

}
</script>

<template>

  <div class="wave-footer"></div>

  <footer>

    <div class="container py-5">

      <h3 class="logo-text text-center">Deliveboo</h3>

      <div class="row text-center">

        <div class="col-6 col-md-4 col-lg-3 mb-5">
          <h5 class="mb-3">Uniamo le forze</h5>
          <ul class="d-flex flex-column gap-3">
            <li><a href="#">Lavora con noi</a></li>
            <li><a href="#">Deliveboo per i Partner</a></li>
            <li><a href="#">Corrieri</a></li>
            <li><a href="#">Deliveboo Business</a></li>
          </ul>
        </div>

        <div class="col-6 col-md-4 col-lg-3 mb-5">
          <h5 class="mb-3">Link di Interesse</h5>
          <ul class="d-flex flex-column gap-3">
            <li><a href="#">Chi siamo</a></li>
            <li><a href="#">FAQ</a></li>
            <li><a href="#">Deliveboo Prime</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contattaci</a></li>
            <li><a href="#">Sicurezza</a></li>
          </ul>
        </div>
        
        <div class="col-6 col-md-4 col-lg-3 mb-5">
          <h5 class="mb-3">Modulistica</h5>
          <ul class="d-flex flex-column gap-3">
            <li><a href="#">Termini e condizioni</a></li>
            <li><a href="#">Politica sulla privacy</a></li>
            <li><a href="#">Politica sui cookie</a></li>
            <li><a href="#">Conformità</a></li>
          </ul>
        </div>

        <div class="col-6 col-md-4 col-lg-3 offset-md-4 offset-lg-0 mb-5">
          <h5 class="mb-3 text-md-center">Seguici</h5>
          <ul class="d-flex gap-3 fs-4 justify-content-center">
            <li><a href="#"><i class="fa-brands fa-square-facebook"></i></a></li>
            <li><a href="#"><i class="fa-brands fa-square-instagram"></i></a></li>
            <li><a href="#"><i class="fa-brands fa-twitter"></i></a></li>
            <li><a href="#"><i class="fa-brands fa-youtube"></i></a></li>
          </ul>
        </div>

      </div>

      <p class="our-group text-center my-2 fs-6">By Group 5</p>

    </div>
  </footer>
  
</template>


<style lang="scss" scoped>
.wave-footer{
  height: 100px;
  background-color: #F2F0E4;
  background-image: url(./wavefooter.svg);
  background-size: cover;
  transform: scaleX(-1);
  position: relative;
  top: 100px;
  border: none;
}

footer{
  background-color: #260D07;
  color: #F2F0E4;

  .logo-text{
    font-family: "Lobster", sans-serif;
    color: #F2F0E4;
    font-size: 3rem;
    margin-bottom: 30px;
  }

  a {
    color: rgb(162, 161, 161);
    text-decoration: none;
    &:hover {
      color: #F2F0E4;
    }
  }

  .our-group {
    color: rgb(162, 161, 161);
    font-size: 14px;
  }
}

@media screen and (max-width: 576px) {
footer{

  .logo-text{
    font-size: 2.4rem;
    margin-bottom: 30px;
  }
}

}
</style>