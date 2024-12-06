<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <pre>
        This is my first vue.js page for cps530.
        To set this up I had to go through a few steps.

        1. Open command prompt and create a directory for vue.js
        2. Run “npm install vue”
        3. Run “npm install -g @vue/cli”
        4. Create vue project by running “vue create projectName”
        5. Then I went into the folder and opened the project with “vue run serve”
        6. Then I opened the vue html file from file explore with VSCode
        Difficulties
        7. Then I had to link the vueproject to github
        8. Then I made an account at netlify and connected it to the git repo

        1. I had errors and had to go back and update my node js
            a. I downloaded the executable
            b. Run “nvm install latest”
            c. Run “nvm install 22.12.0”
        2. I had to run “npm audit fix --force” some of my vue files where broken

    </pre>
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
