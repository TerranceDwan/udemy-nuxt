<template>
  <div>
    <h1>This is {{ $route.params.id }}'s page</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  validate(data) {
    console.log(data)
    return true
  }
}
</script>

<style scoped></style>
type="text"
