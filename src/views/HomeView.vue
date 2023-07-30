<template>
  <h1>home</h1>
  <button @click="gotDayBook" class="btn btn-primary">Daybook</button>
</template>

<script>
export default {
  methods: {
    gotDayBook() {
      this.$router.push({ name: 'no-entry' })
    }
  }
}
</script>