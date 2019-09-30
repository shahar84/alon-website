<template>
  <div>
    <v-navigation-drawer
      v-model="drawer"
      fixed
      app
      right
    >
      <v-list>
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
        >
          <v-list-item-action>
            <v-icon>{{ item.icon }}</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="item.title"/>
          </v-list-item-content>
        </v-list-item>


        <v-list-item href="tel:0547355113">
          <v-list-item-action>
            <v-icon>mdi-phone</v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-title v-text="'054-7355113'"/>
          </v-list-item-content>
        </v-list-item>
      </v-list>


    </v-navigation-drawer>
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
    >
      <v-app-bar-nav-icon @click.stop="drawer = !drawer" v-if="$vuetify.breakpoint.smAndDown"/>
      <div v-if="!$vuetify.breakpoint.smAndDown">
        <v-btn
          v-for="(item, i) in items"
          :key="i"
          :to="item.to"
          router
          exact
          text
        >
          {{item.title}}
        </v-btn>
      </div>
      <v-spacer/>
      <v-btn href="tel:0547355113" text>054-7355113</v-btn>
      <v-spacer/>

      <v-toolbar-title v-text="title"/>
    </v-app-bar>
  </div>
</template>

<script>
export default {
    name: "top-nav",
    data() {
        return {
            clipped: false,
            drawer: false,
            fixed: false,
            items: [
                {
                    icon: 'mdi-home',
                    title: 'דף הבית',
                    to: '/'
                },
                {
                    icon: 'mdi-information-variant',
                    title: 'אודות',
                    to: '/about'
                },
                {
                    icon: 'mdi-chart-bubble',
                    title: 'הדבר מכרסמים',
                    to: '/mouse'
                }, {
                    icon: 'mdi-chart-bubble',
                    title: 'ריסוס',
                    to: '/spraying'
                },

            ],
            title: 'אלון המדביר'
        }
    }
}
</script>

<style scoped>

</style>
