<template>
  <div class="home">
    <n-button>naive-ui</n-button>
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
  </div>
</template>

<script>
import { NButton } from "naive-ui";
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
    NButton,
  },
})
export default class Home extends Vue {}
</script>
