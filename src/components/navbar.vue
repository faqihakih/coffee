<template>
  <v-card>
    <v-app-bar
      :collapse="!collapseOnScroll"
      :collapse-on-scroll="collapseOnScroll"
      absolute
      color="rgb(37, 18, 0)"
      dark
      scroll-target="#scrolling-techniques-6"
    >
      <v-toolbar-title>Coffee Place</v-toolbar-title>

      <v-spacer></v-spacer>
    </v-app-bar>
  </v-card>
</template>



<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
    name: 'Nav',
    components: {
      //HelloWorld
    },
    data: () => ({
      collapseOnScroll: true,
    }),
  }


</script>
