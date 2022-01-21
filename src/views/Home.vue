<template>
  <Banner />
  <div class="main-container">
    <h1>Monte seu Hamburguer</h1>
    <BurguerForm />
  </div>
</template>

<script>
// @ is an alias to /src
import Banner from '../components/Banner.vue'
import BurguerForm from '../components/BurgerForm.vue'

export default {

  name: 'Home',
  components: {
    Banner,
    BurguerForm
  }
}
</script>
