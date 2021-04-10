<template>
  <section>
    <div class="part-three">
      <div class="container-three">
        <div class="title">
          <h3>
            <span id="title-one">
              آخرین مقالات
            </span>
          </h3>
          <a href="" id="title-two">
            مشاهده همه مقالات
          </a>
        </div>
        <div class="cards-container">
          <div id="wire ">
            <div class="card-one" id="b">
              <div class="card-one-img-container">
                <div class="card-one-img">
                  <span id="svg">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-6 h-6 " wire:click="setBookmark">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
                    </svg>
                  </span>
                </div>
                <img class="img" src="@/assets/vue.png" alt="">
              </div>
              <div class="part-b">
                <div class="part-b-control">
                  <h2 class="titr">
                    <a href="" id="titr">
                    آموزش استفاده از تصاویر DOCKER
                    </a>
                  </h2>
                </div>
                <div class="tag-container">
                  <a href="" id="tag">
                    #داکر
                  </a>
                  <a href="" id="tag">
                    #docker
                  </a>
                  <a href="" id="tag">
                    #تصویر-در-داکر
                  </a>
                </div>
              </div>
              <div class="footer">
                <div class="footer-card">
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg fill="none" viewBox="0 0 22 22" stroke="currentColor" class="w-5 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                  </div>
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-5 f-5 h-6 hover:text-red-500 cursor-pointer " wire:click="like">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="wire c">
            <div class="card-one">
              <div class="card-one-img-container">
                <div class="card-one-img">
                  <span id="svg">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-6 h-6 " wire:click="setBookmark">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
                    </svg>
                  </span>
                </div>
                <img class="img" src="@/assets/vue.png" alt="">
              </div>
              <div class="part-b">
                <div class="part-b-control">
                  <h2 class="titr">
                    <a href="" id="titr">
                    آموزش استفاده از تصاویر DOCKER
                    </a>
                  </h2>
                </div>
                <div class="tag-container">
                  <a href="" id="tag">
                    #داکر
                  </a>
                  <a href="" id="tag">
                    #docker
                  </a>
                  <a href="" id="tag">
                    #تصویر-در-داکر
                  </a>
                </div>
              </div>
              <div class="footer">
                <div class="footer-card">
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg fill="none" viewBox="0 0 22 22" stroke="currentColor" class="w-5 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                  </div>
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-5 f-5 h-6 hover:text-red-500 cursor-pointer " wire:click="like">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
           <div class="accunt-container" id="a">
            <span class="desc">
              <h3 id="titr-accunt">
                نوشتن راهی برای گسترش ایده ها
              </h3>
              <p id="desc">
                نوشتن کار جالبیه که از هزاران سال همراه ما بوده و کمک کرده تا همیشه بروز باشیم ،ما در راکت فضا رو به شکلی آماده کردیم تا شما بتوانید ایده ها و مطالب جالب حوزه برنامه نویسی رو در اختیار هزاران برنامه نویس عضو راکت قرار بدید.
              </p>
            </span>
            <div class="button">
              <a href="" id="new">
                 ساخت اکانت جدید
              </a>
              <a href="" id="login">
                 ورود به سایت
              </a>
            </div>
          </div>
          <div id="wire d" >
            <div class="card-one" >
              <div class="card-one-img-container">
                <div class="card-one-img">
                  <span id="svg">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-6 h-6 " wire:click="setBookmark">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
                    </svg>
                  </span>
                </div>
                <img class="img" src="@/assets/vue.png" alt="">
              </div>
              <div class="part-b">
                <div class="part-b-control">
                  <h2 class="titr">
                    <a href="" id="titr">
                    آموزش استفاده از تصاویر DOCKER
                    </a>
                  </h2>
                </div>
                <div class="tag-container">
                  <a href="" id="tag">
                    #داکر
                  </a>
                  <a href="" id="tag">
                    #docker
                  </a>
                  <a href="" id="tag">
                    #تصویر-در-داکر
                  </a>
                </div>
              </div>
              <div class="footer">
                <div class="footer-card">
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg fill="none" viewBox="0 0 22 22" stroke="currentColor" class="w-5 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                  </div>
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-5 f-5 h-6 hover:text-red-500 cursor-pointer " wire:click="like">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="wire e">
            <div class="card-one" >
              <div class="card-one-img-container">
                <div class="card-one-img">
                  <span id="svg">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-6 h-6 " wire:click="setBookmark">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
                    </svg>
                  </span>
                </div>
                <img class="img" src="@/assets/vue.png" alt="">
              </div>
              <div class="part-b">
                <div class="part-b-control">
                  <h2 class="titr">
                    <a href="" id="titr">
                    آموزش استفاده از تصاویر DOCKER
                    </a>
                  </h2>
                </div>
                <div class="tag-container">
                  <a href="" id="tag">
                    #داکر
                  </a>
                  <a href="" id="tag">
                    #docker
                  </a>
                  <a href="" id="tag">
                    #تصویر-در-داکر
                  </a>
                </div>
              </div>
              <div class="footer">
                <div class="footer-card">
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg fill="none" viewBox="0 0 22 22" stroke="currentColor" class="w-5 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                  </div>
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-5 f-5 h-6 hover:text-red-500 cursor-pointer " wire:click="like">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="wire f" >
            <div class="card-one" id="a">
              <div class="card-one-img-container">
                <div class="card-one-img">
                  <span id="svg">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-6 h-6 " wire:click="setBookmark">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
                    </svg>
                  </span>
                </div>
                <img class="img" src="@/assets/vue.png" alt="">
              </div>
              <div class="part-b">
                <div class="part-b-control">
                  <h2 class="titr">
                    <a href="" id="titr">
                    آموزش استفاده از تصاویر DOCKER
                    </a>
                  </h2>
                </div>
                <div class="tag-container">
                  <a href="" id="tag">
                    #داکر
                  </a>
                  <a href="" id="tag">
                    #docker
                  </a>
                  <a href="" id="tag">
                    #تصویر-در-داکر
                  </a>
                </div>
              </div>
              <div class="footer">
                <div class="footer-card">
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg fill="none" viewBox="0 0 22 22" stroke="currentColor" class="w-5 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                  </div>
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-5 f-5 h-6 hover:text-red-500 cursor-pointer " wire:click="like">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="wire">
            <div class="card-one" id="a">
              <div class="card-one-img-container">
                <div class="card-one-img">
                  <span id="svg">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-6 h-6 " wire:click="setBookmark">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 5a2 2 0 012-2h10a2 2 0 012 2v16l-7-3.5L5 21V5z"></path>
                    </svg>
                  </span>
                </div>
                <img class="img" src="@/assets/vue.png" alt="">
              </div>
              <div class="part-b">
                <div class="part-b-control">
                  <h2 class="titr">
                    <a href="" id="titr">
                    آموزش استفاده از تصاویر DOCKER
                    </a>
                  </h2>
                </div>
                <div class="tag-container">
                  <a href="" id="tag">
                    #داکر
                  </a>
                  <a href="" id="tag">
                    #docker
                  </a>
                  <a href="" id="tag">
                    #تصویر-در-داکر
                  </a>
                </div>
              </div>
              <div class="footer">
                <div class="footer-card">
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg fill="none" viewBox="0 0 22 22" stroke="currentColor" class="w-5 h-6">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 12h.01M12 12h.01M16 12h.01M21 12c0 4.418-4.03 8-9 8a9.863 9.863 0 01-4.255-.949L3 20l1.395-3.72C3.512 15.042 3 13.574 3 12c0-4.418 4.03-8 9-8s9 3.582 9 8z"></path>
                    </svg>
                  </div>
                  <div class="like">
                    <span class="num-of-like">1</span>
                    <svg viewBox="0 0 24 24" stroke="currentColor" fill="none" class="w-5 f-5 h-6 hover:text-red-500 cursor-pointer " wire:click="like">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                    </svg>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style
TheSave scoped>
.part-three{
  padding: 1rem 0 2rem;
  background-color: rgba(192, 189, 189, 0.438);
  height: auto;
}
.container-three{
  max-width: 95rem;
  padding: 0 2rem;
  margin: auto;
}
.title{
  margin: 0 0 1.5rem;
  display: flex;
  justify-content: space-between;
}
#title-one{
  font-size: x-large;
  color: #475569;
}
#title-two{
  color: #334155;
}
.cards-container{
  display: grid;
  grid-template-columns: repeat(4,minmax(0,1fr));
  grid-template-rows: repeat(2,minmax(0,1fr));
  gap: 1rem;
}
.card-one{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  border-radius: 15px ;
  background: #fff;
}
.card-one-img{
  position: absolute;
  top: 0;
  left: 0;
  margin: 1rem 0 0 1rem;
}
.card-one-img-container{
  position: relative;
  margin: 1rem 0 0 1rem;
  overflow: hidden;
}
#svg{
  display: flex;
}
.w-6{
  width: 1.5rem;
  height: 1.5rem;
  cursor: pointer;
}
.w-5{
  width: 1.5rem;
  height: 1.5rem;
  margin-right: .5rem;
}
.f-5:hover{
  color: red;
  cursor: pointer;
}
.card-one-img-container{
  margin: .75rem;
  overflow: hidden;
}
.img{
  object-fit: cover;
  width: 100%;
  height: auto;
}
.part-b{
  display: flex;
  flex-direction: column;
  padding:0 1rem;
}
.part-b-control{
  display: flex;
  flex-grow: 1;
}
#titr{
  width: 100%;
  color: #334155;
  text-decoration: none;
}
#titr:hover{
  text-decoration: underline;
}
.tag-container{
  display: flex;
  flex-wrap: wrap;
  margin-top: 1rem;
}
#tag{
  color: #475569;
  padding: .25rem;
  margin: .25rem;
  text-decoration: none;
}
.footer-card{
  display: flex;
  padding: 1rem;
}
.like{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.num-of-like{
  padding-top: .5rem;
}
.accunt-container{
  width: auto;
  grid-column: 3 / 5;
  grid-row: 1 / 2;
  align-items: center;
  padding: 1.6rem;
  text-align: center;
  background-image: linear-gradient(rgba(235, 220, 221, 0.493) , rgba(179, 170, 173, 0.671) , rgb(255, 255, 255));
}
#titr-accunt{
  margin-bottom: .5rem;
  font-size: x-large;
  color: #475569;
}
#desc{
  margin-top: 1rem;
  font-size:larger;
  color: #64748b;
}
.button{
  width: auto;
  margin-top: 1rem;
  display: flex;
  flex-direction: column;
  align-items: center;
}
#new{
  width: 9rem;
  height: 3rem;
  text-decoration: none;
  border-radius: 10px;
  color: #ffff;
  background-color: #64748b;
  padding: .5rem;
}
#new:hover ,
    :active{
      background-color: #232a33;
    }
#login{
  width: 7rem;
  height: 3rem;
  text-decoration: none;
  color: #ffff;
  padding: .5rem;
  margin-top: .5rem;
}




@media screen and (max-width:50.125rem){
  .cards-container{
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}
.title{
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
}


</style>