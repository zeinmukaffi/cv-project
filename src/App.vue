<script setup>
  import {
    RouterLink,
    RouterView
  } from 'vue-router'
  import ViewPersonal from './views/viewPersonal.vue';
  import Header from './components/Header.vue';
import ViewSkill from './views/viewSkill.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <!-- header -->
  <header class="ds-header" id="site-header">
    <Header/>
  </header>
  <!-- header -->
  <!-- banner -->
  <div class="ds-banner">
    <div class="container">
      <div class="row">
        <div class="col-12 col-sm-12 col-md-5 col-lg-5 col-xl-5 col-xxl-5">
          <figure>
            <img src="@/assets/images/foto-square.jpg">
          </figure>
        </div>
        <div class="col-12 col-sm-12 col-md-7 col-lg-7 col-xl-7 col-xxl-7">
          <section>
            <ViewPersonal />
          </section>
        </div>
      </div>
    </div>
  </div>
  <!-- banner -->

  <!--  skill -->
  <div class="ds-work-section">
    <ViewSkill />
    <RouterView />
  </div>
  <!--  Work -->

  <!--  footer -->
  <footer class="ds-footer text-center">
    <Footer/>
  </footer>

  <!-- <RouterView /> -->
</template>

<style scoped>
  figure img {
    margin-top: 7rem;
    border-radius: 50%;
    border: 10px solid #576F72;
    width: 400px;
    aspect-ratio: 1/1;
  }
</style>