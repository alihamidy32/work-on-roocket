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

<style >


</style>