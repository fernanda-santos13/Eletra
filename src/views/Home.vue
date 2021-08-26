<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Monte o seu Burger:</h1>
      <burguer-form />
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner'
import BurguerForm from '../components/BurguerForm'
export default {
  name: 'Home',
  components: {
    Banner,
    BurguerForm
  }
}
</script>