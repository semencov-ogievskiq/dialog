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
            <WorkMessages/>
        </v-col>
        <v-col
            cols="4"
        >
            <ListMessages/>
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
    .v-card {
        border: 1px solid #EFF0F2;
    }
</style>

<script>
    import Filters from '../components/Filters.vue'
    import WorkMessages from '../components/WorkMessages.vue'
    import ListMessages from '../components/ListMessages.vue'

    export default {
        name: 'Index',

        data: () => ({
            
        }),
        components: {
            Filters,
            WorkMessages,
            ListMessages
        }
    }
</script>
