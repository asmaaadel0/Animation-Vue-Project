<template>
    <div class="container">
        <h2>All Users</h2>
        <router-link to="/goals">Course Goals</router-link>
    </div>
</template>
<style scoped>
a {
    text-decoration: none;
    color: #c6086d;
    display: inline-block;
    padding: 0.75rem 1.5rem;
    border: 1px solid transparent;
}

a:active,
a:hover,
a.router-link-active {
    border: 1px solid #c6086d;
}
</style>