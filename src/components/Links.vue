<template>
  <div class="flex">
    <a href="https://www.youtube.com/@HoopsyMakesGames" class="youtube fa fa-youtube"></a>
    <a href="https://www.twitch.tv/hoopsymakes" class="fa fa-twitch twitch"></a>
    <a href="https://ko-fi.com/hoopsy" class="fa fa-kofi">kofi</a>
    <a href="https://github.com/Hoopsier" class='fa fa-github github'></a>
    <a href="https://www.linkedin.com/in/renan-horuz-99a41a28b/" class="fa fa-linkedin linkedin"></a>
  </div>
</template>

<script>
export default {
  name: 'MyLinks',
  props: {
    youtube: String,
    github: String,
    twitch: String,
    linkedin: String
  }
}
</script>

<style scoped>
.flex {
  display: flex;
}
</style>
<style scoped>
div {
  margin-top: 2px;
  direction: rtl;
}

a {
  margin-right: 5px;
  font-size: 24px;
  color: #e9c460;
  text-decoration: none;
}
</style>
