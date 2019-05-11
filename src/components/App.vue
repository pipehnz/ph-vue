<template lang="pug">
    .jumbotron
        .container
            .row
                .col.text-center
                    h1.display-3.font-weight-light PH Vue
                    p Plantilla basíca para desarrollar con Vue.js y Pug
                    a.btn.btn-primary(:href='link') Ver más
</template>


<script>
export default {
    data () {
        return {
            link: 'https://github.com/pipehnz/ph-vue'
        }
    }
}
</script>

<style lang="scss">
    @import url('https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.3.1/css/bootstrap.min.css');
    @import url('https://bootswatch.com/4/cosmo/bootstrap.min.css');
    @import url('https://fonts.googleapis.com/css?family=Lato:100,100i,300,300i,400,400i,700,700i,900,900i');

    * {
        font-family: 'Lato', sans-serif;
    }
</style>