<template>
    <div class="counter">
        {{ counter }}
    </div>
    <div class="buttons">
        <button @click="incrementCounter">+</button>
        <button @click="decrementCounter">-</button>
    </div>
</template>

<script>
export default {
    name: "Counter",
    data() {
        return {
            counter: 0,
        };
    },
    methods: {
        incrementCounter() {
            this.counter++;
        },
        decrementCounter() {
            this.counter--;
        },
    },
};
</script>

<style scoped>
div {
    margin: 40px 0;
}

.counter {
    font-size: 4rem;
}

.buttons button {
    font-size: 2.5rem;
    width: 100px;
    margin: 0 20px;
}
</style>
