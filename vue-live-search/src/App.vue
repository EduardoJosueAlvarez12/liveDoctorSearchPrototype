<template>
  <Header />
  <DoctorSearch />
</template>

<script>
import Header from './components/Header.vue';
import DoctorSearch from './components/DoctorSearch.vue';

export default {
  name: 'App',
  components: {
    Header,
    DoctorSearch
  }
}
</script>

<style>

</style>
