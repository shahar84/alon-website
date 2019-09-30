<template>
  <div>
    <v-parallax
      height="400"
      :src="heroImage"
    >
      <v-layout column align-center justify-center>
        <h1 class="display-3">מדביר חיפה</h1>
      </v-layout>
    </v-parallax>
    <v-container max-w-2xl>


      <v-layout
        row
        align-center
      >
        <v-flex
          xs12
          sm6
          md6
        >
          <v-card class="mt-n10">
            <v-card-text>
              <p class="title">
                מדביר מוסמך בחיפה והסביבה
                הכי חשוב בעבודות הדברה זה איתור וטיפול בבעיה על מנת שלא תחזור
                התקשרו ליעוץ חינם או לתיאום
                <br/>
                <v-btn href="tel:0547355113"  color="primary">054-7355113</v-btn>

              </p>
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
// import heroImage from '~/assets/images/homepage-hero.jpg'

export default {
    components: {},
    data() {
        return {
            heroImage: require('~/assets/images/homepage-hero.jpg')
        }
    }
}
</script>
