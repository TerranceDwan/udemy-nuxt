<template>
  <div>
    <form @submit.prevent="onLoadUser">
      <input v-model="userId" />
      <button>Load User</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: ''
    }
  },
  methods: {
    onLoadUser() {
      this.$router.push('/users/' + this.userId)
    }
  }
}
</script>

<style scoped></style>
type="text"
