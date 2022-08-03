<template>
  <div class="container">
    <MyPersonelComp v-for="index in 5" :key="index"></MyPersonelComp>
  </div>
</template>

<script>
import MainContainerVue from './components/MainContainer.vue'
import PersonelVue from './components/Personel.vue'

export default {
  components: {
    MyComp: MainContainerVue,
    MyPersonelComp: PersonelVue
  }
}
</script>
<style>
.container {
  display: inline;
  justify-content: center;
  align-items: center;
}
</style>
