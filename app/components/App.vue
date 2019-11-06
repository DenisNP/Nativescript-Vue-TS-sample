<template>
    <Label class="message" :text="msg" col="0" row="0"/>
</template>

<script lang="ts">
    import { Vue, Component } from "vue-property-decorator";
    @Component
    export default class App extends Vue {
        msg: string = "Hello";
    }
    // export default {
    //     data() {
    //         return {
    //             msg: 'Hello World!'
    //         }
    //     }
    // }
</script>

<style scoped>
    .message {
        vertical-align: center;
        text-align: center;
        font-size: 20;
        color: #000;
    }
</style>