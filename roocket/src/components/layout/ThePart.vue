<template>
  <article>
    <div class="article-control">
      <div class="article">
        <div class="parag-article">
          <div class="start">
            <a href="" id="start">
              شروع یادگیری برنامه نویسی
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="w-5 mr-2">
              <path fill="currentColor" d="M128.09 220H424a24 24 0 0 1 24 24v24a24 24 0 0 1-24 24H128.09l-35.66-36z" class="opacity-40"></path>
              <path fill="currentColor" d="M142.56 409L7 273.5v-.06a25.23 25.23 0 0 1 0-34.84l.06-.06 135.5-135.49a24 24 0 0 1 33.94 0l17 17a24 24 0 0 1 0 33.94L92.43 256 193.5 358a24 24 0 0 1 0 33.94l-17 17a24 24 0 0 1-33.94.06z" class="fa-primary"></path>
              </svg>
            </a>
            <h1 class="titr">
              آموزش برنامه نویسی با راکت 
            </h1>
            <p class="parag">
               ما باور داریم که کاربران ایرانی لایق بهترین ها هستند،از این رو ما تمام تلاش خود را می کنیم تا بتوانیم فیلم ها و مقالات آموزشی بروز و کاربردی در اختیارتان قرار دهیم تا با استفاده از آنها بتوانید جزء بهترین ها در صنعت طراحی و برنامه نویسی وب شوید.ما ادعا نمی کنیم که بهترین هستیم ولی همیشه تمام تلاش خود را می کنیم بهترین عملکرد را به شما ارائه دهیم.
            </p>
          </div>
        </div>
      </div>
    </div>
  </article>
</template>

<script>
export default {

}
</script>

<style scoped>
article{
  background-color: #475569;
}
.article-control{
  padding:2rem 0;
  display: flex;
}
.article{
  max-width: 95rem;
  margin: auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
}
.parag-article{
  width: 50%;
  display: flex;
  justify-items: flex-start;
}
.start{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-content: flex-start;
}
#start{
  width: 15rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #2722227c;
  color: #ffff;
  text-decoration: none;
  transition-duration: 150ms;
  transition: ease-in-out;
  padding: .5rem 1rem;
  margin-bottom: 1rem;
  border-radius: 3rem;
}
#start:hover{
  background-color: yellow;
  color: #475569;
}
.titr{
  color: white;
  font-weight: 1200;
  font-size: 3rem;
  margin-bottom: 1rem;
}
.parag{
  color: white;
  font-size: 1.57rem;
  font-weight: 400;
}



@media screen and (max-width:69.125rem) {
  .parag-article{
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    align-content: center;
  }
  .titr{
    align-self: center;
  }
  #start{
    align-self: center;
  }
}
</style>