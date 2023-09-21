<template>
  <img src="avatar.jpg" alt="My Avatar" />
  <h2>name {{ nickname }}</h2>
  <p>ID {{ studentId }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nickname: '杨怡晴',
      studentId: '2310275014',
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
