<template>
  <div class="right-menu d-flex flex-column border-top border-secondary">
    <h2 class="ps-2 py-2"><i class="text-primary fas fa-images"></i> Images</h2>
    <ul class="list-group">
        <li class="ps-4 list-group-item list-group-item-action active"><i class="text-primary fas fa-image pe-2"></i>Image #1</li>
        <li class="ps-4 list-group-item list-group-item-action" v-for="i in images" :key="i"><i class="text-primary fas fa-image pe-2"></i>Image #{{i+2}}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'RightSideBar',
  data() {
      return {
          images: Array.from(Array(29).keys())
      }
  }
}
</script>

<style scoped>
    .right-menu {
        width: 20rem;
    }

    ul {
        height: 20rem;
        overflow-y: scroll;
    }

    li {
        font-size: 1.5rem;
    }

    li[class*="active"] i {
        color: white !important;
    }
</style>