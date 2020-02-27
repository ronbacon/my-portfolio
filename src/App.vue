<template>
  <div class="container-fluid p-0">
    <Nav />
    <Intro/>
    <Academics />
    <Hobbies />
    <Sports />
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Intro from './components/Intro.vue'
import Academics from './components/Academics.vue'
import Hobbies from './components/Hobbies.vue'
import Sports from './components/Sports.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Intro,
    Academics,
    Hobbies,
    Sports,
  }
}
</script>
