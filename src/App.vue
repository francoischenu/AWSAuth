<template>
 <amplify-authenticator username-alias="email">
     <img alt="Vue logo" src="./assets/logo.png">
     <HelloWorld msg="You Successfully Authenticated a User!  Go You!"/>
     <amplify-sign-out></amplify-sign-out>
 </amplify-authenticator>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
