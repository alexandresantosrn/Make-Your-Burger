<template>
    <div id = "nav">
        <router-link to="/">
            <img :src="logo" :alt="alt" id="logo">
        </router-link>

        <router-link to="/">Home</router-link> |
        <router-link to="/pedidos">About</router-link>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
    props: ['logo', 'alt']
}
</script>
