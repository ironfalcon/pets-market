<template>
  <div class="home">
    <h1>Adopt a new best friend</h1>
    <button class="btn btn-primary">Add new Pet</button>
  </div>
</template>

<script>

export default {
  name: 'Home',
  data () {
    return {
      // showPetForm
    }
  },
  methods: {
    togglePetForm () {
      this.showPetForm = !this.showPetForm
    }
  }
}
</script>
