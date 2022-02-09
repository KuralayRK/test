<template>
<div class="body">
  <div class="menu-head">
  <div class="menu">
    <div class="head-logo"> 
      <img src="@/images/biglogo.png" alt="">
    </div>
      <div class="hamburger-menu">
  <input id="menu__toggle" type="checkbox">
  <label class="menu__btn" for="menu__toggle">
    <span></span>
  </label>
    <ul class="menu__box">
      <li class="menu__item">Наши курсы</li>
      <li class="menu__item">О WeDo</li>
      <li class="menu__item">Новости WeDo</li>
      <li class="menu__item">Пройти тест</li>
    </ul>
  </div>
  <div class="menu-right">
<p1>RU</p1>
<button class="login">Войти</button>
  </div>
   </div>
   </div>
   <div class="modern-education">
     <div class="modern-right">
<p3>Онлайн платформа</p3>
<h1>Современное <br> образование</h1>
<button class="education">Пройти обучение</button>
     </div>
     <div class="modern-left">
       <img src="@/images/korp-sait.png" alt="" width="385" height="385">
     </div>
   </div>
   <div class="info-courses">
     <div class="info-text">Проект ориентирован на повышение уровня образования и квалификации нового поколения Казахстана
     </div>
     <div class="info-images">
       <img src="@/images/10.png" alt="">
       <img src="@/images/15.png" alt="">
       <img src="@/images/120.png" alt="">
     </div>
   </div>
   <!-- <div class="course-choice">
     <div class="course-choice-text">
     <h6>Выбери себе курс</h6>
     <p5>Подберите себе подходящее направление</p5>
       </div>
       <div class="button-more">
       <button class="more">Подробнее</button>
   </div>
   </div> -->
   <div class="offer">
    <h2>Что мы предлагаем?</h2>
    <img src="@/images/offer1.png" alt="">
    <img src="@/images/offer2.png" alt="">
    <img src="@/images/offer3.png" alt="">
   </div>
   <!-- <div class="directions">
     <h3>Направления</h3>
     <img src="@/images/direct1.png" alt="">
     <img src="@/images/direct2.png" alt="">
     <img src="@/images/direct3.png" alt="">
     <img src="@/images/direct4.png" alt="">
   </div> -->
   <!-- <div class="slider carousel">
     
    </div>  -->

<div class="footer">
    <div class="partners">
<h4>Компании партнёры</h4>
<div class="part-logo">
<img src="@/images/part1.png" alt="">
<img src="@/images/part2.png" alt="">
<img src="@/images/part3.png" alt="">
<img src="@/images/part2.png" alt="">
</div>
<div class="part-name">
<img src="@/images/logos_behance.png" alt="">
<img src="@/images/logos_netflix.png" alt="">
<img src="@/images/logos_netflix.png" alt="">
</div>
    </div>
    <div class="connect">
      <div class="connect-left">
        <h5>Форма обратной связи</h5>
        <p4>Здесь Вы можете задать <br> интересующие Вас вопросы.</p4>
      </div>
      <div class="connect-right">
        <input type="text" placeholder="ФИО">
        <input type="tel" placeholder="Телефон">
        <input type="email" placeholder="Электронная почта">
        <input type="text" placeholder="Комментарий">
        <p7>Нажимая на кнопку, я соглашаюсь на обработку персональных данных и с правилами пользования платформы</p7>
        <button class="send">Отправить</button>
      </div>
    </div>
  <div class="aboutus">
<div class="contacts">
<p8>Контакты</p8> 
<p>8 (705) 227-44-11</p> 
<p>8 (776) 926-19-99</p> 
<p>г. Алматы, Сейфуллина 597А, 5 этаж</p>
<p>г. Нур-Султан, Майлина 37, 7 этаж</p>
</div>
<div class="napra">
<p8>Направления</p8> 
<p>Коммуникации</p>
<p>Дизайн</p>
<p>Маркетинг</p>
<p>IT</p>
<p>Бизнес и управление</p>
<p>Soft-skills</p>
</div>

<div class="wedo">
<p8>O WeDo Education</p8> 
<p>О платформе</p>
<p>Для студентов</p>
<p>Для партнёров</p>
</div>

<div class="news">
<p8>Новости WeDo</p8> 
<p>Образование</p>
<h>Бизнес</h>
<p>Дизайн</p>
</div>
  </div>
</div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import '../images/_mixins.sass';
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');

.body{
  margin: 0px;
}

.menu{
  @include flex-colu($display-f: inline-flex, $flex-dir: row, $wrap: wrap, $just: flex-star, $item: center);
    display: flex;
    justify-content: space-between;
    padding-left: 120px;
    padding-right: 120px;
    padding-top: 40px;
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif}

.hamburger-menu li {
  display: inline-block;
  margin-left: 50px;
  padding-right: 70px;
  font-size: 20px;
  font-weight: 500;
  line-height: 22px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
.login{
  margin-left: 20px;
  background: #1A5CCE;
  border-radius: 20px;
  width: 100px;
  height: 50px;
  font-size: 20px;
  color: #FFFFFF;
}

.modern-education{
  display: flex;
  align-items: center;
  justify-content: center;
}

.course-choice{
  background: #1A5CCE;
  text-align: center;
  font-style: normal;
  font-weight: 600;
  font-size: 50px;
  line-height: 55px;
  color: #FFFFFF;
  display: flex;
  background-image: url('../images/elki.png');
  background-repeat: no-repeat;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.course-choice p5{
  font-size: 20px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.modern-right p3{
  font-style: normal;
  font-weight: 500;
  font-size: 26px;
  line-height: 29px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.modern-right h1{
  font-style: normal;
  font-weight: 950;
  font-size: 80px;
  line-height: 88px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.education{
  width: 440px;
  height: 80px;
  left: 150px;
  top: 507px;
  background: #1A5CCE;
  border-radius: 20px;
  font-style: normal;
  font-weight: 950;
  font-size: 30px;
  line-height: 33px;
  color: #FFFFFF;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.modern-education{
  justify-content: space-between;
  padding-left: 120px;
  padding-right: 120px;
  padding-top: 120px;
}

.info-courses{
  padding-top: 100px;
  padding-left: 120px;
  padding-right: 120px;
}

.info-text{
  width: 800px;
  font-style: normal;
  font-weight: normal;
  font-size: 40px;
  line-height: 48px;
  padding-bottom: 50px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.info-images img{
  padding-right: 30px;
}

.more{
  width: 180px;
  height: 70px;
  background: rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  font-style: normal;
  font-weight: 950;
  font-size: 20px;
  line-height: 24px;
  color: #FFFFFF;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.offer{
  align-items: center;
  padding-right: 120px;
  padding-left: 120px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.offer h2{
  font-style: normal;
  font-weight: 600;
  font-size: 60px;
  line-height: 66px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.offer img{
  margin-right: 120px;
  margin-bottom: 60px;
}

.footer{
  background: #1A5CCE;
  background-image: url('../images/message.png');
  background-repeat: no-repeat;
  background-position: 0px 1050px;
}

.partners{
  padding-top: 50px;
  padding-left: 120px;
  padding-bottom: 231px;
}

.partners h4{
  font-style: normal;
  font-weight: 600;
  font-size: 40px;
  line-height: 44px;
  color: #FFFFFF;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
} 
.part-logo{
  padding-left: 90px;
  padding-bottom: 110px;
}
.part-logo img{
  margin-right: 140px;
}

.part-name img{
  margin-right: 150px;
}

.connect{
  padding-left: 120px;
  display: flex;
  padding-bottom: 300px;
}
.connect-left{
  font-style: normal;
  font-weight: 600;
  font-size: 40px;
  line-height: 44px;
  color: #FFFFFF;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
.connect-left p4{
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 26px;
  color: #A3BEEB;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
.connect-right input{
  display: flex;
  width: 500px;
  height: 50px;
  padding-left: 15px;
  background: #306CD3;
  border: none;
  border-radius: 10px;
  margin-bottom: 20px;
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 20px;
  color: #FFFFFF;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}
::placeholder{
  color: white

}

.connect-right{
  margin-left: 200px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.send{
  width: 240px;
  height: 50px;
  background: #FFFFFF;
  border-radius: 10px;
  font-style: normal;
  font-weight: normal;
  font-size: 22px;
  line-height: 24px;
  color: #1A5CCE;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.aboutus{
  border-radius: 50px 50px 0px 0px;
  background-color: azure;
  background-size: auto;
  display: flex;
  font-weight: normal;
  font-size: 18px;
  line-height: 20px;
  padding-left: 250px;
  padding-top: 90px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

.contacts{
  margin-right: 100px;
}

.napra{
  margin-right: 100px;
}

.wedo{
  margin-right: 100px;
}

.news{
  margin-right: 100px;
}

.aboutus p8{
  font-style: normal;
  font-weight: 600;
  font-size: 22px;
  line-height: 24px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif
}

@media screen and (max-width:550px) {

#menu__toggle{
  opacity: 0;
}

.menu__btn {
  display: flex; 
  align-items: center;
  position: fixed;
  top: 20px;
  left: 20px;
  width: 26px;
  height: 26px;
  cursor: pointer;
  z-index: 1;
}

.menu__btn > span,
.menu__btn > span::before,
.menu__btn > span::after {
  display: block;
  position: absolute;
  width: 100%;
  height: 2px;
  background-color: #616161;
}
.menu__btn > span::before {
  content: '';
  top: -8px;
}
.menu__btn > span::after {
  content: '';
  top: 8px;
}

.menu__box {
  display: block;
  position: fixed;
  visibility: hidden;
  top: 0;
  left: -100%;
  width: 300px;
  height: 100%;
  margin: 0;
  padding: 80px 0;
  list-style: none;
  text-align: center;
  background-color: #ECEFF1;
  box-shadow: 1px 0px 6px rgba(0, 0, 0, .2);
}

.menu__item {
  display: block;
  padding: 12px 24px;
  color: #333;
  font-family: 'Roboto', sans-serif;
  font-size: 20px;
  font-weight: 600;
  text-decoration: none;
}
.menu__item:hover {
  background-color: #CFD8DC;
}

#menu__toggle:checked ~ .menu__btn > span {
  transform: rotate(45deg);
}

#menu__toggle:checked ~ .menu__btn > span::before {
  top: 0;
  transform: rotate(0);
}

#menu__toggle:checked ~ .menu__btn > span::after {
  top: 0;
  transform: rotate(90deg);
}

#menu__toggle:checked ~ .menu__box {
  visibility: visible;
  left: 0;
}
}
</style>
