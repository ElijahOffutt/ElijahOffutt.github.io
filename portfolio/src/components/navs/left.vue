<template>
    <v-navigation-drawer app>
        <v-list-item title="Elijah Offutt" subtitle="Digital Engineer" />
        <v-divider />
        <v-list-item>
            <v-btn tag="a" href="mailto:einzenheim@yahoo.com" class="mr-2" size="x-small" color="#410093" icon>
                <v-icon :icon="`mdi-yahoo`" />
            </v-btn>
            <v-btn class="mr-2" target="black" :href="b.link" :disabled="b.active" size="x-small" v-for="b in socials"
                :color="b.color" icon>
                <v-icon :icon="`mdi-${b.icon}${b.style ? `-${b.style}` : ''}`" />
            </v-btn>
        </v-list-item>
        <v-divider />
        <v-list-item title="" />
    </v-navigation-drawer>
</template>

<script setup>
let socials = [
    {
        icon: 'linkedin',
        link: 'https://www.linkedin.com/in/elijahoffutt/',
        color: '#0A66C2',
        style: '',
        active: false
    },
    {
        icon: 'github',
        link: 'https://github.com/ElijahOffutt',
        color: '#7ce38b',
        style: '',
        active: false
    }
]
</script>