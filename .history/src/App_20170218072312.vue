<template>
    <md-toolbar>
            <h1 class="md-title">My Title</h1>
        </md-toolbar>
    <div id="app">
        <router-view></router-view>
    </div>
</template>

<script>
    export default {
      name: 'app'
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #999;
        margin-top: 60px;
    }
</style>
