<script>
    export default {
        name: 'AppTitle',
        data() {
            return {

            }
        },
        methods: {
            sayHello() {
                alert('Hello Vite!!!')
            }
        }
    }
</script>

<template>
    <h1>La mia prima app con Vite!</h1>
    <button @click="sayHello">Saluta vite</button>
</template>
