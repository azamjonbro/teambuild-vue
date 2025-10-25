<template >
    <div class="login-page">
        <div class="login-container">
            <h2>Login</h2>
            <div>
                <label for="login-email">Email</label>
                <input type="email" name="" id="login-email"></input>
            </div>
            <div>
                <label for="login-pass">Password</label>
                <input type="password" name="" id="login-pass">
            </div>
            <button class="submit-btn">Submit</button>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.login-page{
    display: flex;
    width: 100%;
    min-height: 100vh;
    justify-content: center;
    align-items: center;
    background-color: rgb(75, 121, 248);
}
.login-container{
    width: 400px;
    height: 400px;
    border: solid white 2px;
    border-radius: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 50px 20px;
    gap: 20px;
}
.login-container input{
    width: 330px;
    height: 30px;
    border-radius: 5px;
    border: none;
    outline: none;
    padding: 0 20px;
}
.login-container h2{
    font-size: 50px;
    color: white;
}
.login-container>div{
    display: flex;
    flex-direction: column;
    gap: 8px;
    color: rgb(213, 209, 209);
}
.login-container>button{
    width: 120px;
    height: 30px;
    border-radius: 5px;
    border: none;
    background-color: rgb(29, 230, 29);
    color: white;
    font-size: 17px;
    margin-top: 30px;
}
</style>