<template>
    <v-card
        outlined
    >
        <v-card-title class="font-weight-regular pb-2">Фильтры</v-card-title>

        <v-card-text>
            <v-row dense>
                <v-col cols="12" lg="6" v-for="(index, item) in [0,1,2,3,4,5,6,7,8,9]" :key="item" >
                    <span class="mx-1">
                        <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect x="0.5" y="0.5" width="15" height="15" rx="2.5" fill="white" stroke="#848FA3"/>
                        </svg>
                    </span>
                    <span  class="mx-1">Фильтр {{index+1}}</span>
                </v-col>
            </v-row>
        </v-card-text>

    </v-card>
</template>

<script>
export default {
    name: 'Filters',

    data: () => ({
      
    }),
}
</script>

<style scoped>

</style>
