<template>
    <div class="intro">
        <img src="https://vuejs.org/images/logo.png" alt="">
        <h1>{{ app }}</h1>
        <small>Plantilla por <a :href="github">@pipehnz</a></small>
    </div>
</template>

<script>
export default {
    data () {
        return {
            app: 'Bievenido a tu proyecto de Vue JS 2',
            github: 'https://github.com/pipehnz'
        }
    }
}
</script>

<style>
    @import url('https://fonts.googleapis.com/css?family=Lato:300,400,900i');

    * {
        font-family: 'Lato', sans-serif;
    }

    body {
        margin: 0 auto;
    }

    .intro {
        text-align: center;
    }

    h1 {
        font-weight: 900;
        font-style: italic;
    }

    small {
        font-weight: 300;
    }
</style>


