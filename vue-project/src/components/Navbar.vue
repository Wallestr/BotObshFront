<template>
    <nav class="navbar">
        <router-link to="/" class="nav-link">Задачи</router-link>
        <router-link to="/profile" class="nav-link">Профиль</router-link>

    </nav>
</template>

<script>
export default{
    name: "Navbar"
}
</script>

<style>
    .navbar{
        display: flex;
        justify-content: space-around;
        align-items: center;
        height: 60px;
    }

    .nav-link{
        text-decoration: none;
        color: black;
        font-size: 16px;
        font-weight: 500;
    }
</style>