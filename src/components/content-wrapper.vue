<template>
  <!-- Content Wrapper. Contains page content -->
  <div class="content-wrapper">
    <!-- Content Header (Page header) -->
   <content-header></content-header>

    <!-- Main content -->
    <container></container>
    <!-- /.content -->
  </div>
  <!-- /.content-wrapper -->
</template>

<script>
import ContentHeader from "./content-header.vue";
import Container from "./container.vue";

export default {
  components: {
    Container,
    ContentHeader},
  name: 'contentWrapper',
  data () {
    return {
      msg: 'Welcome to Your Vue.js Appaaa'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
