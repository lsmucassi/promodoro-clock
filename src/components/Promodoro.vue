<template>
    <v-card class="mt-6">
        <v-tabs v-model="timerType" >
            <v-tab
                v-for="tab in tabTitles"
                :key="tab" >
                {{ tab }}
            </v-tab>
        </v-tabs>
    </v-card>
</template>

<script>
export default {
    data() {
        return {
            timerType: 0,
            tabTitles: ['Promodoro', 'Short Break', 'Long Break']
        }
    }
}
</script>

<style lang="saas" scoped>
/* .v-card {
    width: 400px;
} */
</style>