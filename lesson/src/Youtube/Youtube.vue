<script>
import '../assets/youtube.css'
</script>
<!-- <template>
    <button @click="get" class="btn btn-warning" style="margin: 10px;padding: 10px;">Get Posts</button>

    <div v-for="p in post" :key="p.id">
    <h2 style="padding: 15px;margin: 10px;  ">
        {{ p.id }} - {{ p.title }}
    </h2> 
    <p style="padding: 10px;margin: 10px;">{{ p.body }}</p>
    </div>
</template>


<script>
 export default (await import('vue')).defineComponent({
    data(){
        return{
            post: []
        }
    },

    methods: {
        get(){
            fetch('https://jsonplaceholder.typicode.com/posts/')
            .then(response => response.json())
            .then(data => this.post = data)
        }
    }
})
</script> -->
<!------------------------------------------------------------------------------------------------------------------------------->
<template>
    <div class="yellow">
        <div class="container">
        <div class="tabs_a">
            <span><a href="#">Uzb</a></span>
            <span><a href="#">Rus</a></span>
            <span><a href="#">Eng</a></span>
        </div>
</div>
</div>
<div class="cn_bg">
    <h1>Грузовые перевозки</h1>
</div>
<div class="cn_c">
    <h1>грузоперевозки по европе</h1>
    <img style="width: 500px;height: 500px; transform: translate(500px);" src="./car_b.svg" alt="">
    <h4>Страны Евросоюза, а также Украина,Белоруссия со всеми документами.</h4>
    <button style="width: 200px;height: 50px;transform: translate(-950px,420px);color: white; background-color: #C8A35F;border: none;" type="button" class="btn btn-warning">Подробное</button>
</div>

<div class="cccp">
    <h1>Услуги</h1>
    <img src="./url.svg" alt="">
</div>

<div class="ccp">
    <h1>О компании</h1>
    <p>Lorem Ipsum - это текст-"рыба", часто используемый в печати и вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов на латинице с начала XVI века. В то время некий безымянный печатник создал большую коллекцию размеров и форм шрифтов, используя Lorem Ipsum для распечатки образцов. Lorem Ipsum не только успешно пережил без заметных изменений пять веков, но и перешагнул в электронный дизайн.</p>
<div id="a"></div>
<div id="b"><h2>48 офисов</h2></div>
<div id="c"><h2>361 <br> грузовиков</h2></div>
<div id="d"><h2>1500 сотрудников</h2></div>
<div id="e"></div>
</div>
<div class="aab"></div>
<footer></footer>
</template>