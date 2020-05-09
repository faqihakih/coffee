<template>
  <v-parallax
    dark
    src="https://cdn.vuetifyjs.com/images/parallax/material2.jpg"
  >
    <v-row
      align="center"
      justify="center"
    >
      <v-col class="text-center" cols="12">
        <h1 class="display-1 font-weight-thin mb-4">Kirik Luwak</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur aut, praesentium aperiam distinctio magnam cum aliquam, similique eaque minus fuga facere odit in explicabo molestiae non asperiores culpa cumque temporibus.</p>
      </v-col>
    </v-row>
  </v-parallax>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
    name: 'tentang',
    components: {
      //HelloWorld
    }
  }
</script>
<style scoped>
  *{
    padding-top: 60px;
    min-height: 400px;
  }
</style>