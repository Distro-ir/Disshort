<template>
    <div class="row">
        <button id="star">Login</button>
        <button id="conter">Sign up</button>
    </div>
</template>
<script>
export default {
    name: "theButton",
    components: {

    }
}
</script>
<style scoped>
.row {
    display: flex;
}

#star {
    margin-right: 7px;
    border: 3px solid white;
    background-color: white;
    padding: 20px;
    height: fit-content;
    color: rgb(92, 134, 161);
}

#conter {
    border: 3px solid rgb(70, 163, 238);
    background-color: rgb(70, 163, 238);
    border-radius: 16px;
    padding: 9px;
    height: 50px;
    color: white;
    width: 100px;
    margin-top: 7px;
}
</style>