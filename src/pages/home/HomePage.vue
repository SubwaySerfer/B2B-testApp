<template>
  <main>
    <promo-home-section></promo-home-section>
    <comparison-home-info></comparison-home-info>
    <tours-home-info></tours-home-info>
  </main>
</template>

<script>
import PromoHomeSection from '../../components/home/PromoHomeSection.vue';
import ComparisonHomeInfo from '../../components/home/ComparisonHomeInfo.vue'
import ToursHomeInfo from '../../components/home/ToursHomeInfo.vue'

export default {
  components: { PromoHomeSection, ComparisonHomeInfo, ToursHomeInfo }
}
</script>