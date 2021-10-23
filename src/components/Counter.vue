<template>
    <div class="counter">0</div>
    <div class="buttons">
        <button>+</button>
        <button>-</button>
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
