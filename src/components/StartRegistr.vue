
<template>
    <div class="registration" id="registration">
        <h2>Впервые у нас?</h2>
        <form action="">
            <input type="text" placeholder="Ваше имя">
            <input type="text" placeholder="Ваша Фамилия">
            <h4>Дата рождения</h4> 
            <select name="day" id="day" >
               <option v-for="day of days" :key="day">{{day}}</option>
            </select>
            <select name="month" id="month">
                <option v-for="item of month" :key="item" >{{item}}</option>
            </select>
            <select name="year" id="year" >
                <option v-for="year of years" :key="year">{{year}}</option>
            </select>
            <h4>Ваш пол</h4>
            <input type="radio" id="men" value="men" v-model="picked">
            <label for="men">Мужской</label>
            <input type="radio" id="women" value="women" v-model="picked">
            <label for="women">Женский</label>
            <br/>
            <input type="button" value="Продолжить регистрацию">
        </form>
    </div>
</template>
    
<script>


export default {
    name: 'startRegistr',
    data(){
        return {
        days: [1,2,3,4,5,6,7,8,9,10,11,12,13,
            14,15,16,17,18,19,20,21,22,23,24,25,
            26,27,28,29,30,31],
        month: ['Январь','Февраль','Март','Апрель',
        'Май','Июнь','Июль','Август','Сентябрь','Октябрь',
        'Ноябрь','Декабрь'],
        years: [1990, 1991, 1992, 1993, 1994, 
            1995, 1996, 1997, 1998, 1999, 2000, 
            2001, 2002, 2003, 2004, 2005, 2006, 2007, 
            2008, 2009, 2010, 2011, 2012, 
            2013, 2014, 2015, 2016, 2017, 2018, 2019], 
        picked: '',
        }
    }
     
}
</script>

<style lang="scss" scoped>
    .registration {
        width: 300px;
        background-color: rgb(231, 227, 227);
        text-align: center;

        & form {
            align-content: space-around;

            & input{
                height: 30px;
                margin: 10px 0 0 5px;
            }

            & input[type='radio']{
                height: 10px;
            }
            
            & input[type='button'] {
                background-color: darkblue;
                color: #fff;
                width: 250px;
                height: 30px;
            }
        }
    }
</style>