<template>
  <header class="page-header animate__animated animate__fadeIn">
    <img alt="logo" class="logo" src="@/assets/images/todo-legal-logo.png" />
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>

<style scoped>
.page-header {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 6rem;
  width: 100%;
}

.logo {
  height: 7rem;
  width: 16rem;
}
</style>
