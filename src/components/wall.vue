<template>
    <div class="wall">
        <input type="text" name="wall" id="wall" placeholder="Что у вас нового?">
        <input type="button" value="Добавить" v-on:click='addValue'>
        <div class="wall__info">

        </div>
    </div>
</template>

<style lang="scss">
@import '@/assets/style/components/wall.scss';
</style>
<script>
export default {
    name: 'wall',
    methods: {
        addValue : function() {
            document.querySelector('.wall__info').innerHTML += `<div><p>${document.querySelector('#wall').value}</p></div>`
        }
    }
}
</script>