<template>
  <nav>
    <div class="nav-control">
      <li>
      <a href="">
         صفحه اصلی
      </a>
      </li>
      <li>
        <a href="">
         دوره های آموزشی
        </a>
      </li>
      <li>
        <a href="">
         بحث و گفتگوها
        </a>
      </li>
      <li>
      <a href="">
         مقالات
      </a>
      </li>
      <li>
        <a href="">
         راکت کست 
        </a>
      </li>
      <li>
      <a href="">
         رزومه ساز 
      </a>  
      </li>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style scoped>
nav{
  display: flex;
  background-color: #475569;
  width: 100%;
}
.nav-control{
  max-width: 95rem;
  width: 100%;
  padding: 0 2rem;
  height: 4rem;
  margin: auto;
  display: flex;
  align-items: center;
}
li{
  list-style: none;
  margin-right:1rem ;
}
a{
  text-decoration: none;
  padding: 1rem;
  color: #e2e8f0;
}
a:hover{
  color: #ffff;
}


@media screen and (max-width:69.125rem) {
  .nav-control{
    display: none;
  }
}
</style>