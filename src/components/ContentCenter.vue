<template>
<div class="container">
  <div class="center-content">
    <div class="sections-buttons">
      <img src="..\assets\img\box-with-icons.svg" alt="">
    </div>
    <div class="alien-with-phone">
      <img src="..\assets\img\alien-with-phone.svg" alt="">
    </div>
  </div>
</div>
</template>

<style scoped>
.container {
  max-width: 1200px;
  margin-inline: auto;
  margin-top: 24px;
}

.center-content {
  display: flex;
  justify-content: space-evenly;
  margin-left: 10%;
}

.sections-buttons img {
  height: 450px;
  width: 450px;
}

.alien-with-phone {
  object-fit: cover;
  width: 550px;
}

.alien-with-phone img {
  padding-top: 64px;
  height: 450px;
}
</style>
