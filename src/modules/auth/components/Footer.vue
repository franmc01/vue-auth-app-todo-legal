<template>
  <footer class="animate__animated animate__fadeIn">
    <p class="text-footer">
      {{ msg }}
      <span class="link-footer">
        <a href="#">Todo.Legal</a>
      </span>
    </p>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
  props: {
    msg: {
      type: String,
      default: "Gestor de Procesos by",
    },
  },
};
</script>

<style scoped>
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  height: 3.5rem;
  bottom: 0;
  width: 100%;
  font-size: 0.9rem;
}

.text-footer {
  color: var(--primary-color);
}

.link-footer > a {
  color: var(--primary-color);
  font-weight: bold;
}
</style>
