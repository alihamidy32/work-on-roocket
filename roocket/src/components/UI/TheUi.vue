<template>
  <section>
    <div>
      <part-one />
    </div>
    <div>
    <part-two-of-card />
    </div>
    <div>
      <part-three-of-card />
    </div>
    <div>
      <part-four />
    </div>
    <div>
      <part-five />
    </div>
    <part-six />
    <div>
      <the-footer />
    </div>
  </section>
</template>

<script>
import PartFive from '../layout/PartFive.vue'
import PartFour from '../layout/PartFour.vue'
import PartOne from '../layout/PartOne.vue'
import PartSix from '../layout/PartSix.vue'
import PartThreeOfCard from '../layout/PartThreeOfCard.vue'
import PartTwoOfCard from '../layout/PartTwoOfCard.vue'
import TheFooter from '../layout/TheFooter.vue'
export default {
  components: {PartTwoOfCard, PartThreeOfCard, PartFour, PartFive, PartSix, TheFooter, PartOne, },

}
</script>

<style scoped>
.part-one{
  width: 100%;
  height: 35rem;
  background-color: rgba(240, 230, 230, 0.555);
  padding: .5rem 3rem 1rem;
  
}
.container{
  display: flex;
  align-content: center;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}
#container-item{
  margin-right: 7rem;
  text-decoration: none;
  font-size: x-large;
  color: #475569;
}
#container-iteme{
  margin-left: 7rem;
  color: #334155;
}
.card{
  position: relative;
  top: 1rem;
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
}

</style>