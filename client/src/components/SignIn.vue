<template>
    <div class="div">
       <div class="sign_in">
            <form action="#" 
            method="post">
                <input type="text" placeholder="Телефон или email">
                <input type="password" placeholder="Пароль">
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
@import '~@/assets/style/components/signIn.scss';
</style>
