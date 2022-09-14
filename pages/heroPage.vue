<template>
  <div>
    <div class="navbar">Study Bridge</div>

    <div class="main">
      <div class="headline">
        <h1>Find the <span class="highlight">Best Learning Center</span></h1>
        <h1>to Study in 10 seconds</h1>
        <p></p>
      </div>
    </div>

    <div class="subscribe"></div>
  </div>
</template>

<script>
export default {
  name: 'HeroPage',
  layout: 'LandingPage',
}
</script>

<style scoped>
.navbar {
  height: 55px;
  border-bottom: 1px solid grey;
}

.main {
  /* background: wheat; */
  height: 80vh;
  border-bottom: 1px solid grey;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.main h1 {
  background: #fff;
  /* font-family: 'Inter', sans-serif; */
  font-family: Inter, -apple-system, "system-ui", "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  font-weight: 900;
  font-size: 76px;
  line-height: 90px;
  color: #213547;
}

.main .highlight {
    /* color: #43D392; */
    color: #618af0;
    color: linear-gradient(to right top,#43D392,#618af0);
}
</style>