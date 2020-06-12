<template>
  <div>
    <TheHeader />
    <main>
      <nuxt />
    </main>
    <footer></footer>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader'
export default {
  components: {
    TheHeader
  }
}
</script>
<style></style>
