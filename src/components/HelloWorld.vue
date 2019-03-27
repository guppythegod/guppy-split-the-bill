<template>
  <div class="hello">
      <a href="https://www.guppy.im">
        <h2>A <span class="bold">Guppy</span> Project</h2>
      </a>  
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<style scoped>

h2 {
  font-weight: 400;
}

a {
  text-decoration: none;
  color: #555555;
}

.hello {
  text-align: center;
  border-bottom: #555555 solid 1px;
}

.bold {
  font-weight: 800;
}

</style>
