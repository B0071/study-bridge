<template>
  <div>
    <div class="navbar">
      <div class="logo" cols="12" md="3"><span style="color: #43D392;">STUDY</span><span style="color: #34495E">BRIDGE</span></div>
      <div class="menu-items" cols="12" md="6">
        <a href="#">About</a>
        <a href="#">Use Cases</a>
        <a href="#">Developers</a>
        <a href="#">About</a>
        <a href="#">FAQs</a>
      </div>
      <div class="register" cols="12" md="3">
        <div class="cta-btns">
          <a href="#" class="btn">Register</a>
          <a href="#" class="btn">Sign In</a>
        </div>
      </div>
    </div>

    <div class="main">
      <div class="headline">
        <h1>Find the Best</h1>
        <h1><span class="highlight">Learning Center</span> to <span style="text-decoration: underline ">study</span></h1>
        <h1>Right Now . . .</h1>
        <p class="content">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos illo quaerat in est veniam cupiditate.</p>
        <div class="cta-btns">
          <a href="#" class="active"><span class="play-btn">▶</span> Why us?</a>
          <a href="#">Get Started →</a>
          <a href="#">Install</a>
        </div>
      </div>
    </div>

    <div class="benefits">
      <div class="card" v-for="card in 6" :key="card">
        <h2>Easy to Find</h2>
        <p>Lorem ipsum dolor sit amet consecteturnt, consequuntur explicabo minus asperiores ea perspiciatis amet?</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroPage',
  layout: 'LandingPage',
}
</script>

<style scoped>
* {
  font-family: Inter, -apple-system, "system-ui", "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  color: #34495E;
}

.navbar {
  height: 55px;
  border-bottom: 1px solid rgb(215, 213, 213);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5px 30px;
}

.logo {
  font-weight: 900;
  font-size: 35px;
  font-family: Inter, -apple-system, "system-ui", "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
}

.menu-items {
  display: inline-block;
}

.menu-items a {
  text-decoration: none;
  font-family: Inter, -apple-system, "system-ui", "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
  padding: 8px;
  font-weight: 500;
}

.menu-items a:hover{
  color: #43D392;
  transition: ease-in-out .6s;
}

.btn {
  margin-left: 10px;
}

.main {
  /* background: wheat; */
  height: 80vh;
  border-bottom: 1px solid rgb(215, 213, 213);
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

.content {
  color: grey;
  padding: 30px 0;
  text-align: center;
  font-size: 20px;
}

.main .highlight {
    /* color: #43D392; */
    color: #618af0;
    /* color: linear-gradient(to right top,#43D392,#618af0); */
    background: -webkit-linear-gradient(0deg,#43D392,#618af0);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.cta-btns {
  display: flex;
  align-items: center;
  justify-content: center;
}

.cta-btns a {
  padding: 10px 20px;
  margin: 10px;
  background: rgb(244, 242, 242);
  text-decoration: none;
  border-radius: 8px;
  font-weight: 600;
}

.cta-btns .active {
  background: #30ca85;
  color: #fff;
}

.cta-btns .play-btn {
  background-color: #fff;
  color: #30ca85;
  padding: 3px 6px;
  border-radius: 50%;
}

.card {
  width: 350px;
  border-radius: 12px;
  padding: 30px;
  margin: 10px;
  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;
}

.benefits {
  /* background: grey; */
  width: 80%;
  margin: 20px auto;

}

.card h2 {
  margin-bottom: 8px;
}
</style>