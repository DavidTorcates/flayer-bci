<template>
<div class="body">
  <header class="header">
    <div><img class="yellow-alien" src=".\assets\img\yellow-alien.svg" alt="yellow-alien"></div>
    <div><img class="welcome-text" src=".\assets\img\welcome-text.png" alt="welcome-text"></div>
    <div><img class="green-alien" src=".\assets\img\green-alien.svg" alt="green-alien"></div>
  </header>
  <Buttons />
  <ContentCenter />
  <FooterSection />
</div>
</template>

<script>
import Buttons from '@/components/buttons.vue'
import ContentCenter from '@/components/ContentCenter.vue'
import FooterSection from '@/components/FooterSection.vue'

export default {
  name: 'App',
  components: {
    Buttons,
    ContentCenter,
    FooterSection,
}}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

.body {
  padding-top: 32px;
  background-image: url('.\assets\img\background.png');
  background-repeat: no-repeat;
  background-position: center 0;
  max-width: 1200px;
  margin-inline: auto;
  height: 1300px;
}

.header {
  max-width: 1200px;
  display: flex;
  justify-content: center;
  margin-inline: auto;
  padding-inline: 16px;
}

.welcome-text {
  width: 210px;
  margin-top: 32px;
  margin-inline: 120px;
}

.yellow-alien, .green-alien{
  background: transparent;
  height: 290px;
  width: 240px;
  object-fit: cover;
}
</style>
