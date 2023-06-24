<template>
  <div class="game">
    <h1>Click Counter Game</h1>
    <p>Clicks: {{ clickCount }}</p>
    <button @click="incrementClick">Click Me!</button>
  </div>
</template>

<script>
export default {
  name: 'GameCounter',
  data() {
    return {
      clickCount: 0,
    };
  },
  methods: {
    incrementClick() {
      this.clickCount++;

      /* eslint-disable */
      debugger;
    },
  },
};
</script>

<style scoped>
.game {
  text-align: center;
  margin-top: 50px;
}
</style>