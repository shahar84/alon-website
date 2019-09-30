<template>
  <v-app>
    <top-nav/>
    <v-content>
         <nuxt/>
     </v-content>
    <v-footer fixed app>
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
import TopNav from '../components/top-nav';

export default {
    components: {
        TopNav,
    },
    data() {
        return {
            title: 'Vuetify.js'
        }
    }
}
</script>
<style lang="scss">
  @import '../assets/global';

</style>
