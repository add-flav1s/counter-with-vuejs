<template>
    <div class="container">
        <img alt="numbers binary" src="./assets/logo.jpg" />
        <Counter />
    </div>
</template>

<script>
import Counter from "./components/Counter.vue";

export default {
    name: "App",
    components: {
        Counter,
    },
};
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
.container {
    margin: 0 auto;
    max-width: 960px;
}

.container img {
    width: 500px;
    height: 300px;
}
</style>
