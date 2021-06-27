<template>
<!-- Page Wrapper -->
  <div id="wrapper">
    <side-bar/>
    <!-- Content Wrapper -->
    <div id="content-wrapper" class="d-flex flex-column">
        <!-- Main Content -->
        <div id="content">
            <nav-bar/>
            <content-area/>
        </div>
        <Footer/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import ContentArea from '@/components/ContentArea.vue'
import SideBar from '@/components/SideBar.vue'
import NavBar from '@/components/NavBar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'dashboard',
  components: {
    ContentArea,
    SideBar,
    NavBar,
    Footer
  }
}
</script>
