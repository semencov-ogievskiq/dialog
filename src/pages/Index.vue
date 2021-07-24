<template>
    <v-row dense>
        <v-col cols="12">
            <h2 class="font-weight-light">Интерфейс аналитика</h2>
        </v-col>
        <v-col
            cols="4"
        >
            <Filters/>
        </v-col>
        <v-col
            cols="8"
        >
            <v-card
                outlined
            >
                <v-card-title class="font-weight-regular">Работа с сообщениями</v-card-title>
            </v-card>
        </v-col>
        <v-col
            cols="4"
        >
            <v-card
                outlined
            >
                <v-card-title class="font-weight-regular">Список сообщений</v-card-title>
            </v-card>
        </v-col>
        <v-col
            cols="8"
        >
            <v-card
                outlined
            >
                <v-card-text>1</v-card-text>
            </v-card>
        </v-col>
    </v-row>
</template>

<style scoped>
    .col {
        padding: 0.5rem !important;
    }
</style>

<script>
    import Filters from '../components/Filters.vue'

    export default {
        name: 'Index',

        data: () => ({
            
        }),
        components: {
            Filters
        }
    }
</script>
