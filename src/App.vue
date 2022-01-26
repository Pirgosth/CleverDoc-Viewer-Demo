<template>
  <div id="app">
    <NavBar></NavBar>
    <div class="container-fluid">
      <div class="row gs-0">
        <div class="col gx-0 d-flex">
          <LeftSideBar></LeftSideBar>
          <div class="flex-grow-1">
            <ImageView></ImageView>
          </div>
          <RightSideBar></RightSideBar>
        </div>
      </div>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>

import LeftSideBar from "./components/LeftSideBar";
import RightSideBar from "./components/RightSideBar";
import ImageView from "./components/ImageView";
import NavBar from "./components/NavBar";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    NavBar,
    LeftSideBar,
    ImageView,
    RightSideBar,
    Footer
  },
};
</script>

<style scoped>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
  }
  @import url("~bootstrap/dist/css/bootstrap.min.css");
</style>