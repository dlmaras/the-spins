<template>
  <div class="app-container">
    <div class="game-box">
      <div class="game-title game-box-row">
        Welcome To The Spins!
      </div>
      <div class="game-box-row">
        <button class="btn btn-5 btn-5b icon-play game-buttons">
          <span>Start Game</span>
        </button>
      </div>
      <div class="game-box-row">
        <button class="btn btn-5 btn-5b bh-icon-smiley game-buttons">
          <span>About Us</span>
        </button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>
<style scoped>
.app-container{
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: lightgray;
}
.game-box{
  border-radius: 5%;
  height: 60%;
  width: 50rem;
  box-shadow: gray 0 0 10px;
  background-color: white;
}
.game-box-row{
  text-align: center;
  margin-top: 10px;
  margin-bottom: 10px;
}
.game-title {
  font-size: 3em;
  color: skyblue;
  text-align: center;
  margin-top: 100px;
  margin-bottom: 50px;
}
.game-buttons{
  background-color: skyblue;
  width: 300px;
}
</style>
