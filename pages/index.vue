<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        feeb/
      </h1>
      <h2 class="subtitle">
        feeb/ domains coming soon
      </h2>
      <div class="links">
        <a
          href="https://twitter.com/dotfeeb"
          target="_blank"
          class="button--green"
        >
          Twitter
        </a>
        <a
          href="https://namebase.io/"
          target="_blank"
          class="button--grey"
        >
          Namebase
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/feeblogo.png'
export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
}
</style>
