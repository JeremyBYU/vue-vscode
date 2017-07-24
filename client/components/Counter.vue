<template>
  <div class="counter-wrapper">
    <div>
      <img src="https://vuejs.org/images/logo.png" width="200" height="200" />
    </div>
  </div>
</template>

<script>
// @ts-check

export default {
  computed: {
  },
  methods: {
    hello () {
      console.log('hello')
    }
  }
}
</script>

<style lang="scss">
.counter {
  margin: 100px auto;
  border-radius: 3px;
  width: 200px;
  height: 200px;
  text-align: center;
  line-height: 200px;
  font-size: 5rem;
  background-color: #f0f0f0;
  user-select: none;
}
</style>
