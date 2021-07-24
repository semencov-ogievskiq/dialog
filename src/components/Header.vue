<template>
  <v-app-bar
    app
    clipped-left
    color="#FFF"
    dense
    light
    flat
    style="border-bottom: 1px solid #DEE5EF"
  >
    <v-app-bar-nav-icon></v-app-bar-nav-icon>

    <v-spacer/>
    <v-divider inset vertical/>

    <v-avatar class="mx-4" size="32" color="primary"></v-avatar>

    <v-menu offset-y nudge-bottom="13px">
        <template v-slot:activator="{ on }">
            <span v-on="on">Алексей Семенцов <v-icon>mdi-menu-down</v-icon></span>
        </template>
        <v-list>
            <v-list-item>
                <v-list-item-title>fffreereetertr ret erter ter tert retreterter</v-list-item-title>    
            </v-list-item>
        </v-list>
    </v-menu>

  </v-app-bar>
</template>


<script>

export default {
  name: 'Header',


  data: () => ({
    //
  }),
};
</script>
