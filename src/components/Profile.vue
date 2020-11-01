<template>
    <div class="main__info flex">
               <img src="../assets/cat.jpg" alt="photo" 
               width="250px" height="200px">
               <div class="main__about">
                   <div class="name"><strong>Павел Иванчиков</strong></div>
                   <hr>
                   <div class="age"><span>Дата рождения: </span>19.12.1995</div>
                   <div class="town"><span>Город: </span>Гомель</div>
                   <div class="sp"><span>Семейное положение: </span>Не женат</div>
                    <div class="wall">
                        <div class="div">
                            <input type="text" name="wall" id="!" placeholder="Что у вас нового?">
                        </div>
                    </div>
               </div>
           </div>
</template>

<script>
export default {
    name: 'profile',
}
</script>

<style scoped lang="scss">
@import '~@/assets/style/components/profile.scss';
</style>