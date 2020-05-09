<template>
<div class="pilihan">
  <v-row>
    <v-col class="pilih">
      <v-btn class="mx-2" fab dark x-large color="white">
        <v-icon color="rgb(37, 18, 0)">mdi-coffee</v-icon>
      </v-btn>
      <p>Gallery</p>
    </v-col>
    <v-col class="pilih">
      <v-btn class="mx-2" fab dark x-large color="white">
        <v-icon color="rgb(37, 18, 0)">mdi-message-text</v-icon>
      </v-btn>
      <p>Articel</p>
    </v-col>
    <v-col class="pilih">
      <v-btn class="mx-2" fab dark x-large color="white" href="/About">
        <v-icon color="rgb(37, 18, 0)">mdi-account</v-icon>
      </v-btn>
      <p>About</p>
    </v-col>
  </v-row>
  </div>
</template>
<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
    name: 'choose',
    components: {
      //HelloWorld
    }
  }
</script>
<style scoped>
.pilihan{
  padding-top: 25px;
  padding-bottom: 0px;
  background: rgb(37, 18, 0);
}
.pilih{
  display: flex;
  align-self: center;
  justify-content: center;
}
p{
  color: white;
  font-size: 30px;
  margin-left: -86px;
  margin-top: 80px;
}
</style>