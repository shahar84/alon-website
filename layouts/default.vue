<template>
  <v-app>
    <top-nav/>
    <v-content>
      <nuxt/>
    </v-content>
    <v-footer fixed app style="border-top:1px solid #6200ea ">
      <v-layout row align-center justify-center>
        <v-flex xs12 sm8 md8 xl6>
          <div class="text-center">
            <span>כל הזכויות שמורות לאלון המדביר&copy; {{year}}</span>
          </div>
        </v-flex>
      </v-layout>
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
            title: 'Vuetify.js',
            year: (new Date()).getFullYear()
        }
    },

}
</script>
<style lang="scss">
  @import '../assets/global';

</style>
