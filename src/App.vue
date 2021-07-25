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

<style>
  * {
    font-family: Roboto;
    font-style: normal;
    line-height: 24px;
  }
  ::-webkit-scrollbar {
    width: 8px;
}
 
::-webkit-scrollbar-track {
    background: #EFEFEF;
    border-radius: 3px !important;
}
 
::-webkit-scrollbar-thumb {
    border-radius: 3px !important;
    background: #97A4BA; 
}
</style>
