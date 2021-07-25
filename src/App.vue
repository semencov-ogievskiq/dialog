<template>
  <v-app>
    <Header/>
    <Sidebar/>    
    
    <v-main
      style="background-color: #F7F7F7 !important"
    >
      <v-container fluid>
        <Index/>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Header from './components/Header'
import Sidebar from './components/Sidebar'
import Index from './pages/Index'

export default {
  name: 'App',

  components: {
    Header,
    Sidebar,
    Index
  },

  data: () => ({
    //
  })
};
</script>
