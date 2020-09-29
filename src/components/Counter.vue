<template>
  <div>
    <p>The Count: {{ count }}</p>
    <p><button @click="count +=1">+</button></p>
  </div>
</template>

<script>
export default {
  data() {
    return {
     count: 0
    }
  }
}
</script>
