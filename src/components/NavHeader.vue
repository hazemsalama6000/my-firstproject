<template>
    <nav>
        <ul>
            <router-link to="/">Home</router-link>
            |
            <router-link to="/about" exact-active-class="sss" replace>
                About
            </router-link>
            |
            <router-link to="/hello"> hello </router-link>
        </ul>
    </nav>
</template>

<style scoped>
nav {
    background-color: gray;
}
</style>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
@Options({
    name: "nav-header",
})
export default class NavHeader extends Vue {}
</script>
