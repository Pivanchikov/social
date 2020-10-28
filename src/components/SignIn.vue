<template>
    <div class="div">
       <div class="sign_in">
            <form action="#" 
            @submit="checkForm"
            method="post">
                <input type="text" v-model="login" placeholder="Телефон или email">
                <input type="password" v-model="password" placeholder="Пароль">
                <br/>
                <input type="submit" value="Войти">
            </form>
            <a href="#">Забыли пароль?</a>
        </div>
    </div>
</template>
    
<script>

export default {
    name: 'registration__sign',
}
</script>

<style lang="scss" scoped>
.sign_in {
            width: 300px;
            background-color: rgb(231, 227, 227);
            text-align: center;

            & form {
                height: 150px;
                align-content: space-around;

                & input{
                    height: 30px;
                    margin: 10px 0 0 5px;
    
                }
                & input[type='submit'] {
                    background-color: darkblue;
                    color: #fff;
                    width: 70px;
                    height: 30px;
                }
            }
        }
</style>
