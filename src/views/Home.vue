<template>
  <v-app>
    <Nav></Nav>
    <tentang></tentang>
    <choose></choose>
  </v-app>
</template>



<script>
// @ is an alias to /src
import Nav from '@/components/navbar.vue'
import tentang from '@/components/tentang.vue'
import choose from '@/components/choose.vue'

export default {
    name: 'Home',
    components: {
      Nav,tentang,choose
    }
  }


</script>
