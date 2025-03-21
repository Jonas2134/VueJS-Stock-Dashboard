<template lang="html">
  <section class="app-main-content">
    <AppTopOverview />
    <div>
      <AppCard />
      <AppCard />
    </div>
    <div>
      <AppCard />
      <AppCard />
      <AppCard />
    </div>
  </section>

</template>

<script lang="js">
import AppCard from '@/shared/AppCard.vue';
import AppTopOverview from './AppTopOverview.vue';


export default {
  name: 'AppMainContent',
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
    AppTopOverview,
    AppCard
  }
}


</script>

<style scoped lang="scss">
.app-main-content {
  display: flex;
  align-items: center;
  gap: 32px;
  flex-direction: column;

  > div {
    display: flex;
    gap: 32px;
  }
}
</style>
