<template>
  <div class="part-two">
      <div class="container-two">
          <h3>
            <span>
              <a href="" id="titr"> گام های یادگیری </a>
            </span>
          </h3>
          <div class="cards-container">
            <div class="card-one-item">
              <div class="card-one">
                <span class="card-one-title">
              شامل 7 دوره
                </span>
                <a href="" id="card-one-titr">
                 یادگیری جاوا اسکریپت
                </a>
                <p class="card-one-parag">
                   جاوا اسکریپت یکی از زبان های بسیار قدرتمند است که هر روز در حال پیشرفت و تکامل است،تکامل و پیشرفت جاوا اسکریپت را می توان ...
                 </p>
              </div>
            </div>
            <div class="card-one-item">
              <div class="card-one">
                <span class="card-one-title">
              شامل 7 دوره
                </span>
                <a href="" id="card-one-titr">
                 یادگیری جاوا اسکریپت
                </a>
                <p class="card-one-parag">
                   جاوا اسکریپت یکی از زبان های بسیار قدرتمند است که هر روز در حال پیشرفت و تکامل است،تکامل و پیشرفت جاوا اسکریپت را می توان ...
                 </p>
              </div>
            </div>
            <div class="card-one-item">
              <div class="card-one">
                <span class="card-one-title">
              شامل 7 دوره
                </span>
                <a href="" id="card-one-titr">
                 یادگیری جاوا اسکریپت
                </a>
                <p class="card-one-parag">
                   جاوا اسکریپت یکی از زبان های بسیار قدرتمند است که هر روز در حال پیشرفت و تکامل است،تکامل و پیشرفت جاوا اسکریپت را می توان ...
                 </p>
              </div>
            </div>
            <div class="card-one-item">
              <div class="card-one">
                <span class="card-one-title">
              شامل 7 دوره
                </span>
                <a href="" id="card-one-titr">
                 یادگیری جاوا اسکریپت
                </a>
                <p class="card-one-parag">
                   جاوا اسکریپت یکی از زبان های بسیار قدرتمند است که هر روز در حال پیشرفت و تکامل است،تکامل و پیشرفت جاوا اسکریپت را می توان ...
                 </p>
              </div>
            </div>
          </div>
        <span id="last-titr">
          به دنبال گام یادگیری دیگری هستید؟ <a href=""> وارد گام های یادگیری راکت شوید </a>
        </span>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.part-two{
  height: auto;
  padding: 1rem 0 2rem;
  background-color: #334155;
}
.container-two{
  max-width: 95rem;
  margin: auto;
  padding: 0 2rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  
}
.cards-container{
  display: grid;
  grid-template-columns: repeat(4,minmax(0,1fr));
  gap: 1rem;
}
.card-one{
  width: auto;
  height: 15rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 1.2535rem 1rem;
  border-radius: 50px 15px 50px 15px;
  background: #eab308;
}
.card-one-title{
  width: 6rem;
  background-color: #3341554d;
  color: #ffff;
  height: 2.5rem;
  padding: .5rem;
  border-radius: 6px;
  opacity: 510px;
}
#card-one-titr{
  text-decoration: none;
  font-size: x-large;
  color: #ffff;
}
.card-one-parag{
  font-size: medium;
  text-align: justify;
}
h3{
  margin-bottom: 1rem;
}
#titr{
  font-size: x-large;
  text-decoration: none;
  color: white;
}
#last-titr{
  padding-top: 1rem;
  color: white;
}
#last-titr a{
  color: white;
  font-size: large;
}


@media screen and (max-width:69.125rem){
  .cards-container{
  display: grid;
  grid-template-columns: repeat(2,minmax(0,1fr));
  gap: 1rem;
}
}

@media screen and (max-width:50.125rem){
  .cards-container{
  display: grid;
  grid-template-columns: repeat(1,minmax(0,1fr));
  gap: 1rem;
}
}
</style>