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
<div class="container">
    <div class="row">
        <div class="col-12">
            <div style="width: 1423px; height: 800px;  background: rgb(0,198,255);background: linear-gradient(343deg, rgba(0,198,255,1) 40%, rgba(0,151,255,1) 66%);">
                <div class="container"><div class="row"><div class="col-12"><img style="transform: translateX(200px);" src="./logo.svg" alt="">
                <p style="width: 200px;color: white; transform: translate(300px,-70px);">O‘ZBEKISTON RESPUBLIKASIGIDROMETEOROLOGIYA XIZMATI MARKAZI</p>
        <img style="transform: translate(700px,-110px);" src="./web-site.svg" alt="">
        <button style="transform: translate(900px,-110px);" type="button" class="btn btn-primary">+998(71) 123-45-67</button>
        <img style="transform:translate(1000px,-110px);" src="./aa.svg" alt="">
        </div>
    </div>
</div>

<div class="container"><div class="row"><div class="col-12">
<p id="malum">
<a href="#">Bosh Sahifa</a>
<a href="#">Tashkilot haqida</a>
<a href="#">Foliyati</a>
<a href="#">Tuzulmasi</a>
<a href="#">Malumotlar</a>
<a href="#">Xizmatlar</a>
<a href="#">Hujjatlar</a>
<a href="#">Axborat xizmati</a>
<a href="#">Bog'lanish</a>
</p>
         </div>
    </div>
</div>  

<div class="container">
    <div class="row">
        <div class="col-12">
            <img style="border-radius: 15px; transform: translate(20px,0px);" src="https://www.gazeta.uz/media/img/2018/06/z4Qecu15282641867645_b.jpg?r=1532589070" alt="">
        <img style="transform: translate(50px,20px);" src="./ob-havo.svg" alt="">
        </div>
    </div>
</div>
    </div>
    
    <div class="col-12">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div style="background-color: whitesmoke; width: 1423px;height: 1000px;">
                  <h1>Ob-havo</h1>
                  <img src="./ob-havo.svg" alt="">
                  <img src="./ob-havo.svg" alt="">
                  <img src="./ob-havo.svg" alt="">
                  <img src="./ob-havo.svg" alt="">
                  <img src="./ob-havo.svg" alt="">
                  <img src="./ob-havo.svg" alt="">
                    </div>
                </div>
            </div>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div style="background-color: whitesmoke; width: 1423px;height: 2000px;">
                    <h1>Yangiliklar</h1>
                    <p style="width: 500px;border:2px dotted black;">Toshkentda meteorologik kuzatuvlar 1867 yilning dekabridan boshlab olib borilgan. 1870 yilning martidan "Туркестанские ведомости" (Toshkent) gazetasida ob-havo, meteokuzatuv ma'lumotlari nashr qilina boshlagan. 1873 yildan Toshkent astronomiya va fizika observatoriyasi faoliyat yurita boshladi. 1876 yilning sentyabirida Toshkent - observatoriya meteostansiyasi ochildi va hozirgi kungacha ishlab kelyapti.
</p>
<img style="transform: translate(600px,-200px);" src="./yang.svg" alt="">
<button style="transform: translate(-570px,-100px); width: 200px;height: 50px;" type="button" class="btn btn-primary">Barcha xizmati</button>
                   <h1>Tadbirlar</h1>  
                   <img style="box-shadow: 50px 50px 20px gray;" src="./tadbir.svg" alt="">
                   <button style="width: 200px;height: 50px; transform: translate(-880px,400px);" class="btn btn-primary">Bizning tadbirlar</button>
                     <br>
                   <h1 style="transform: translateY(150px);">Hududlar boyicha</h1>
                   <img style="transform: translate(20px,200px);" src="./hh.svg" alt="">
                   <img style="transform: translate(50px,200px);" src="./hh.svg" alt="">
                   <img style="transform: translate(20px,220px);" src="./hh.svg" alt="">
                   <img style="transform: translate(50px,220px);" src="./hh.svg" alt="">
                     </div>
                </div>
            </div>
        </div>

    </div>
        </div>
    </div>
</div>

<footer>
    <ul style="color: white;margin: 20px !important;">
        <li>Yaratuvchi:Aqilbek Ubaydullayev</li>
        <li>Telegram: https://t.me/FED_222</li>
        <li>Malumot uchun:https://t.me/FED_222</li>
        <li>Telefon:+99897-314-77-44</li>
        <li>Ustozi:Ziyodulla Ustoz</li>
    </ul>
</footer>
</template>