<template>
  <div class="card">
    <h3>{{ title }}</h3>
    <button class="btn" @click="isOpen = !isOpen">Open</button>
    <p v-if="isOpen">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt, voluptates?
    </p>
  </div>
</template>
<script>
export default {
  props: ['title'],
  data () {
    return {
      isOpen: false
    }
  }
}
</script>
