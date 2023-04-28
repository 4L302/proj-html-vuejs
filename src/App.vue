<template>
  <div>
    <headerComponent/>
    <mainComponent/>
    <footerComponent/>
  </div>
</template>

<script>
import headerComponent from './components/headerComponent.vue';
import mainComponent from './components/mainComponent.vue';
import footerComponent from './components/footerComponent.vue';

export default {
  name: 'App',
  components: {
    headerComponent,
    mainComponent,
    footerComponent
  },
  data() {
    return {

    }
  }

}
</script>

<style lang="scss" scoped></style>