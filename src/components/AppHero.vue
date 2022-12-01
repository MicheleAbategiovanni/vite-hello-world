<script>
import AppTitle from "./AppTitle.vue";

export default {
    components: {AppTitle},
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>

<template>

    <div class="jumbotron">
        
        <div class="container d-flex justify-content-center p-5">

            <h1>
                <AppTitle></AppTitle>
            </h1>

        </div>

    </div>

</template>

<style>

.jumbotron {

    background-image: url("../assets/jumbotron.png");
    height: 550px;
    width: 100vw;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;

}

</style>
