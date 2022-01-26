<template>
  <div class="d-flex flex-column leftsidebar border-top border-secondary">
    <ul class="pt-5 nav nav-pills nav-flush flex-column mb-auto text-center">
      <li class="nav-item">
        <a href="#" class="nav-link active py-3 border-bottom" aria-current="page" title="" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-original-title="Home" >
          <i class="fas fa-hand-pointer"></i>
        </a>
      </li>
      <li>
        <a href="#" class="nav-link py-3 border-bottom" title="">
          <i class="fas fa-hand-paper"></i>
        </a>
      </li>
      <li>
        <a href="#" class="nav-link py-3 border-bottom" title="">
          <i class="fas fa-adjust"></i>
        </a>
      </li>
      <li>
        <a href="#" class="nav-link py-3 border-bottom" title="">
          <i class="fas fa-image"></i>
        </a>
      </li>
      <li>
        <a href="#" class="nav-link py-3 border-bottom" title="">
          <i class="fas fa-home"></i>
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'LeftSideBar',
  props: {}
}
</script>

<style scoped>
    .leftsidebar {
        width: 3.5rem;
    }
</style>
