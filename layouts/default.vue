<template>
  <div>
    <nuxt />
  </div>
</template>

<script>
export default {
  head: {
    link: [
      {
        rel: 'stylesheet',
        href: 'https://fonts.googleapis.com/css?family=Work+Sans:300'
      }
    ]
  }
}
</script>

<style>
html,
body {
  margin: 0px;
  padding: 5px;
  font-family: 'Work Sans', 'Avenir', sans-serif;
  font-size: 18px;
  line-height: 26px;
}
a {
  color: blue;
  text-decoration: none;
}
a:visited {
  color: blue;
}
a:hover {
  color: red;
  text-decoration: underline;
}
</style>
