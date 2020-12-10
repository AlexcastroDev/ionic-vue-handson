<template>
  <div id="job-lists">
    <div class="job-box">
      <img src="https://foroalfa.org/imagenes/ilustraciones/g-1.jpg" />
      <div>
        <h4>UI designer & UX designer</h4>
        <span>Google Inc.</span>
        <hr/>
      </div>
    </div>
  </div>
</template>

<script lang="ts">

export default {
  name: 'ExploreContainer',
  props: {
    name: String
  }
}
</script>

<style scoped>
.job-box {
      display: flex;
}
.job-box img{
  max-width: 40px;
  max-height: 40px;
}
</style>