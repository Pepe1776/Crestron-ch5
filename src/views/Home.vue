<template>
  <div class="main">
    <h1 class="text-8xl color1">Hello</h1>
    <font-awesome-icon icon="couch" />
    <font-awesome-icon icon="sink" />
    <font-awesome-icon icon="house-damage" />
    <font-awesome-icon icon="bed" />
    <font-awesome-icon icon="dice" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue { }
</script>
