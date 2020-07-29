<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router" target="_blank" rel="noopener">router</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>

      <!-- HEADER-->
        <h1 class="ui small header">Heading 1</h1>
        <h2 class="ui tiny header">Heading 2</h2>
        <h3 class="ui medium header">Heading 3</h3>
        <h4 class="ui large header">Heading 4</h4>
        <h5 class="ui huge header">Heading 5</h5>
        <h6 class="ui small header">Heading 6</h6>

        <hr>

        <!--BUTTONS-->
        <button class="ui button">Read More</button>
        <button class="ui primary button">Read More</button>
        <button class="ui secondary button">Read More</button>
        <button class="ui positive button">Read More</button>
        <button class="ui negative button">Read More</button>
        <br><br>
        <button class="ui disabled red button">Read More</button>
        <button class="ui loading blue button">Read More</button>
        <button class="ui green button">Read More</button>
        <button class="ui massive purple button">Read More</button>
        <button class="ui huge yellow button">Read More</button>
        <button class="ui big brown button">Read More</button>
        <button class="ui large orange button">Read More</button>
        <button class="ui medium olive button">Read More</button>
        <button class="ui small teal button">Read More</button>
        <button class="ui tiny violet button">Read More</button>
        <button class="ui mini grey button">Read More</button>
        <br><br>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
