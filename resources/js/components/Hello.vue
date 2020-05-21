<template>
    <div>
        <h1>Hello, Word! 啦啦啦啦啦啦啦，德玛西亚</h1>
        <p class="hello">{{ msg }}</p>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                msg: 'This is a Laravel with Vue Demo.'
            }
        }
    }
</script>

<style>
    .hello {
        font-size: 2em;
        color: green;
    }
</style>
