<template lang="html">

  <section class="app-top-overview">
    <AppViewCard />
    <AppViewCard />
    <AppViewCard />
    <AppViewCard />
  </section>

</template>

<script lang="js">
import AppViewCard from '@/shared/AppViewCard.vue';


export default {
  name: 'AppTopOverview',
  props: [],
  mounted() {

  },
  data() {
    return {

    }
  },
  methods: {

  },
  computed: {

  },
  components: {
    AppViewCard
  }
}


</script>

<style scoped lang="scss">
.app-top-overview {
  display: flex;
  gap: 24px;
  background-color: #023A6233;
  border-radius: 16px;
  padding: 24px;
}
</style>
