<template>
  <div class="container">
    <div class="img">
      <img src="@/assets/php.png" alt="php.png" id="img">
      <input type="text" name="" placeholder=" تکمیل ضبط " id="input" class="input" >
      <the-star class="img-item" />
      <the-bell class="img-iteme"/>
    </div>
    <div class="card-title" id="card-titr">
      <h3> آموزش php </h3>
      </div>
      <div class="card-title" id="card-explain">
        <p>
        در دوره آموزش php ما سعی می کنیم php را بشکل جامع و کامل و کاملا رایگان به شما آموزش دهیم تا با استفاده از php بتوانید سایت های خود را بسازید.
      </p>
      </div>
    <div class="card-off">
      <svg id="card-off" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="star" class="svg-inline--fa fa-star fa-w-18" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512"><path fill="currentColor" d="M259.3 17.8L194 150.2 47.9 171.5c-26.2 3.8-36.7 36.1-17.7 54.6l105.7 103-25 145.5c-4.5 26.3 23.2 46 46.4 33.7L288 439.6l130.7 68.7c23.2 12.2 50.9-7.4 46.4-33.7l-25-145.5 105.7-103c19-18.5 8.5-50.8-17.7-54.6L382 150.2 316.7 17.8c-11.7-23.6-45.6-23.9-57.4 0z"></path></svg>
      <p>
        دسترسی رایگان برای کلیه اعضاء
      </p>
    </div>
    <div class="end-card-container">
      <div class="heart">
        <span>
          <the-heart />
        </span>
        <span>
          <p>92</p>
        </span>
      </div>
      <div class="clock">
        <span>
          <the-clock />
        </span>
        <span>
          <p>
            08:51:32
          </p>
        </span>
      </div>
      <div class="parag">
        <span>
          <p id="parag">
            رایگان
          </p>
        </span>
      </div>
    </div>
  </div>

</template>

<script>
import TheBell from '../UI/TheBell.vue'
import TheClock from '../UI/TheClock.vue'
import TheHeart from '../UI/TheHeart.vue'
import TheStar from '../UI/LikeHeart.vue'
export default {
  components: { TheStar, TheBell, TheHeart, TheClock  },
}
</script>

<style scoped>
.container{
  position: relative;
  width:20rem;
  height: 28rem;
  border-radius: 8px;
  background-color: #ffff;
  
}
.img{
  position: absolute;
  top: 1.2rem;
  right: .5rem;
}
#img{
  padding: 2rem;
  border-radius: 1rem;
  width: 18rem;
  height: 11rem;
  background-color: rgba(12, 105, 160, 0.692);
  position: relative;
  right: .5rem;
}
#input{
  position: absolute;
  right: .9rem;
  top: .5rem;
  width: 4.7rem;
  height: 1.5rem;
  outline: none;
  border-radius: 7px;
  padding: .25rem;
  font-family: 'Vazir';
  background-color: #33415580 ; 
}
::placeholder{
  color: #ffff;
  opacity: 1;
}
.img-item{
  position: absolute;
  top: .5rem;
  left: 2.5rem;
}
.img-iteme{
  position: absolute;
  top: 0.5rem;
  left: 0;
}
.card-title{
  font-size: small;
}
h3{
  position: absolute;
  top: 13rem;
  right: 1.5rem;
}
#card-explain p{
  position: absolute;
  top: 15rem;
  right: .5rem;
  text-align: justify;
  margin: .9rem  0;
  padding: 0  1rem;
}
.card-off p{
  position: absolute;
  top: 22.5rem;
  right: 3.5rem;
  color: red;
  font-size: small;
}
#card-off{
  width: 1.5rem;
  height: 1.5rem;
  color: red;
  position: absolute;
  top: 22.3rem;
  right:1.5rem;
}
.end-card-container{
  position: relative;
  left: 0;
  top: 13rem;
  width: 20rem;
  height: 3.5rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 1rem;
  background-color: #f8fafc;
}
.heart{
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
}
.clock{
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
}
#parag{
  font-size: small;
  color: green;
}
</style>