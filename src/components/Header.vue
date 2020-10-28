<template>
  <div class="hello">
      <div class="about ">
        <div class="container flex">
            <div class="about__item flex">
                <a href="/">
                    <h1>DEEONE</h1>
                </a>
                <form action="">
                    <input type="search">
                    <input type="button" value="Найти">
                </form>
            </div>
            <div class="switch">
                <a href="#"> Switch to English</a>
            </div>
        </div>
  </div>

  </div>
</template>

<script>
export default {
  name: 'Header',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.about {
    height: 50px;
    padding-top: 10px;
    background-color: darkblue;
    color: #fff;

    &__item{
        width: 450px;
        
        & input{
            height: 15px;
            margin: 8px 2px;
        }
        & input[type='button'] {
            background-color: #fff;
            color: darkblue;
            width: 60px;
            height: 20px;
        }
    }

    & .switch{
        padding: 10px;
        cursor: pointer;
    }
}
</style>
