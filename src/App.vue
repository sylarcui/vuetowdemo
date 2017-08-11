<template>
  <div  class="wrapper">

      <my-header></my-header>
      <sidebar></sidebar>
      <content-wrapper></content-Wrapper>
      <footers></footers>
      <control-sidebar></control-sidebar>

    <!-- Add the sidebar's background. This div must be placed
      immediately after the control sidebar -->
    <div class="control-sidebar-bg"></div>
  </div>

</template>

<script>
import Hello from './components/Hello'
import myHeader from './components/header'
import Sidebar from "./components/mainsidebar.vue";
import ContentWrapper from "./components/content-wrapper.vue";
import Footers from "./components/footer.vue";
import ControlSidebar from "./components/control-sidebar.vue";


export default {
  name: 'app',
  components: {
    ControlSidebar,
    Footers,
    ContentWrapper,
    Sidebar,
    Hello,
    myHeader,

  }
}
</script>

<style>

</style>
