<template>
    <div>
        <Nav />
        <div class="container">
            <router-view />
        </div>
    </div>
</template>

<script>
import Nav from './components/Nav';
import '../node_modules/materialize-css/dist/css/materialize.min.css';
import '../node_modules/materialize-css/dist/js/materialize.min.js';

export default {
    name: 'App',
    components: {
        Nav
    }
};
</script>

<style scoped></style>
