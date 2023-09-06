<template>
  <div class="about">
    <h1>This is an about page</h1>
    <CardA></CardA>
  </div>
</template>
<script>
// @ is an alias to /src
import CardA from '@/components/CardA.vue'

export default {
  components: {
    CardA
  }
}
</script>
