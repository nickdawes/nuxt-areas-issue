<template>
  <Nuxt/>
</template>

<script>
export default {
  name: "default",
  head() {
    console.log(this.$store)
  }
}
</script>
