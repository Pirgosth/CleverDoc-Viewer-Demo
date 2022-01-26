<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light gx-0 py-0">
  <div class="container-fluid">
    <a class="text-primary text-center back-arrow" href="#"><i class="fas fa-arrow-left"></i></a>
    <div class="d-flex flex-grow-1 justify-content-between">
        <div>
            <select class="select1 py-2 text-light bg-primary form-select">
                <option>EMERGENCY-PELVIC</option>
            </select>
        </div>
        <div class="d-flex">
            <select class="text-light bg-primary form-select">
                <option>TODO</option>
            </select>
            <button class="btn btn-primary"><i class="fas fa-check-double"></i></button>
        </div>
    </div>
    <div class="remaining-options"></div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {}
}
</script>

<style scoped>

    .navbar {
        height: 3.5rem;
    }

    .select1 {
        width: 35rem;
    }

    .back-arrow {
        width: 3.5rem;
    }

    .remaining-options {
        width: 20rem;
    }
</style>