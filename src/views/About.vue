<template>
    <div class="about">
        <h1>Resources</h1>
        <a href="https://cli.vuejs.org/guide/cli-service.html#using-the-binary">Vue</a>
        <a href="https://github.com/serverless/components">Serverless</a>
        <a href="https://quasar.dev/vue-components">Quasar</a>
    </div>
    
</template>

<script>
export default {
    name: "about"
}
</script>

<style>
.about a {
    text-decoration: none;
  padding: 10px 20px;
  margin: 50px 30px;
  border-radius: 4px;
  color: white;
  transition: all 0.3s ease;
  background: black;

}

.about a:hover {
    color: black;
    background: white;
    box-shadow: 3px 3px 3px gray;
}
</style>