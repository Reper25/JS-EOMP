<template>
    <nav class="topnav">
        <routerlink class="menu" to="/">Home</routerlink>
        <routerlink class="menu" to="/">Products</routerlink>
        <routerlink class="menu" to="/">About</routerlink>
    </nav>
</template>
<script>
export default {

}
</script>
<style scoped>

.topnav{
    background-color: black;
    overflow: hidden
}

routerlink {
    float: left;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
}

</style>