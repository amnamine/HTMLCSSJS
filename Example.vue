<template>
    <div id="demo">
        <h1>{{ message }}</h1>
        <input v-model="message">
    </div>
</template>

<script>
var myObject = new Vue({
    el: '#app',
    data: {message: 'Hello Vue!'}
})
</script>
