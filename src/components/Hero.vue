<template>
<div class="hero">
    <div class="d-none d-md-block">
  <div class="row mt-4">
      <div class="col">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
            <h2><strong>Good Food Menu, </strong><br> in Your Gadget</h2>
            <p>Pilih dan pesan makanan favorite anda</p>
            <router-link to="/foods" class="btn btn-lg btn-success">Pesan</router-link>
            </div>
            </div>
      </div>
      <div class="col-md-6">
          <img src="../assets/images/hero.png" width="80%">
      </div>
  </div>
  </div>

 <div class="d-sm-block d-md-none">
    <div class="row mt-4">
    <div class="col-md-6 mb-2">
          <img src="../assets/images/hero.png" width="80%">
      </div>
      <div class="col">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
            <h2><strong>Good Food Menu, </strong><br> in Your Gadget</h2>
            <p>Pilih dan pesan makanan favorite anda</p>
            <router-link to="/" class="btn btn-lg btn-success">Pesan</router-link>
            </div>
            </div>
      </div>
  </div>
 </div>
  </div>
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style>

</style>