<template>
  <div id="info-panel" class="panel">
    <router-view></router-view>
  </div>
</template>

<style scoped>
#info-panel {
  order: 2;
  padding: 1rem;
}

@media (min-width: 992px) {
  #info-panel {
    order: 1 !important;
  }
}
</style>
