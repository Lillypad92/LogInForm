<script setup>

</script>

<template>

<div class="wrapper">
    <h2>Login</h2>
    <form>
        <div>
        <font-awesome-icon icon="fa-solid fa-user" /> <label for="email">Username or Email</label>
        <br>
        <input type="text" id="email" name="email" placeholder="Username..."> 
        </div>
        <div>
        <font-awesome-icon icon="fa-solid fa-lock" /> <label for="password">Password</label>
        <br>
        <input type="text" id="password" name="password" placeholder="Password...">
        </div>
        <button type="submit">Sign out </button>
    </form>
   
</div>


</template>

<style scoped>
h2 {
    font-size: 2rem;
    color: #00bbf0;
    
}
.wrapper {
    background-color: gray;
    border-radius: 5px;
    padding: 20px;
    text-align: inherit;
    width: 350px;
    margin: -130px;
}
input[type=text] {
    width: 100%;
    padding: 12px 20px;
    margin: 8px 0px;
    display: inline-block;
    border: 1px solid;
    -webkit-transition: 0.5s;
    transition: 0.5s;
    outline: none;
    border-radius: 4px;
    box-sizing: border-box;
}
input[type=text]:focus {
    padding: 10px;
    box-shadow: 5px 10px 18px #00bbf0;
}
</style>
