<template>
    <v-layout>
        <v-navigation-drawer permanent>
                <NuxtLink to="/" style="text-decoration: none;">
                    <p style="color: black;" class="text-h5 text-center font-weight-bold mt-6 mb-10">CyberSafe Coach</p>
                </NuxtLink>
            <v-list lines="two">
                <NuxtLink to="/" style="text-decoration: none;">
                    <v-list-item class="link my-10 ml-6" prepend-icon="mdi-view-dashboard" title="Panel"> </v-list-item>
                </NuxtLink>
                <NuxtLink to="/cursos" style="text-decoration: none;">
                    <v-list-item class="link my-10 ml-6" prepend-icon="mdi-book-education-outline" title="Cursos"> </v-list-item>
                </NuxtLink>
                <NuxtLink to="/perfil" style="text-decoration: none;">
                    <v-list-item class="link my-10 ml-6" prepend-icon="mdi-account-circle" title="Perfil"> </v-list-item>
                </NuxtLink>
                <v-divider color="orange"></v-divider>
                <v-btn to="/login" rounded="lg" width="70%"prepend-icon="mdi-login" class="mt-15 mx-8">
                    <p>Iniciar Sesión</p>
                </v-btn>
                <v-btn to="/register" rounded="lg" width="70%"prepend-icon="mdi-account-plus" class="mt-5 mx-8">
                    <p>Registrase</p>
                </v-btn>
            </v-list>
        </v-navigation-drawer>
        <v-main>
            <slot />
        </v-main>
    </v-layout>
</template>
<style scoped>
.link{
    color: gray;
}

.link:hover{
    color: #1DF02D;
}
</style>