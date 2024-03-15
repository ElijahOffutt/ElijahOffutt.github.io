<template>
    <v-navigation-drawer app location="right">
        <v-list-item title="Connect" />
        <v-list-item>
            <v-row dense>
                <v-col cols="6">
                    <v-btn block size="small" color="#008A00">sign up</v-btn>
                </v-col>
                <v-col cols="6">
                    <v-btn block size="small" color="#0050EF">login</v-btn>
                </v-col>
            </v-row>
        </v-list-item>
        <v-divider class="my-2" />
        <v-list-item title="Tools & Projects" subtitle="My recent obsessions">
            <br />
            <v-btn block size="large">
                Edge AI
            </v-btn>
        </v-list-item>
    </v-navigation-drawer>
</template>