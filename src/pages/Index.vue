<template>
    <v-row dense>
        <v-col cols="12">
            <h2 class="font-weight-light mt-4">Интерфейс аналитика</h2>
        </v-col>
        <v-col
            cols="4"
        >
            <Filters/>
            <ListMessages/>
        </v-col>
        <v-col
            cols="8"
        >
            <WorkMessages/>
            <v-card
                outlined
                style="height: 39.5rem"
                class="d-flex align-center"
            >
                <v-card-text clas="">
                    <v-img class=" mx-auto" height="210" width="310" src="/undraw_Group_chat_unwm.png"/>
                    <p class="text-center mt-4" style="color: #9796A8; font-size: 16px;">Тут будет подробное сообщение</p>
                </v-card-text>
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
