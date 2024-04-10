<template>
    <v-layout>
        <v-navigation-drawer>
            <v-list lines="two">
                <NuxtLink to="/" style="text-decoration: none;">
                    <v-list-item prepend-icon="mdi-view-dashboard" title="Panel"> </v-list-item>
                </NuxtLink>
                <NuxtLink to="/" style="text-decoration: none;">
                    <v-list-item prepend-icon="mdi-account-circle" title="Cursos"> </v-list-item>
                </NuxtLink>
                <NuxtLink to="/" style="text-decoration: none;">
                    <v-list-item prepend-icon="mdi-account-circle" title="Perfil"> </v-list-item>
                </NuxtLink>
                <v-divider color="orange"></v-divider>
                <v-spacer></v-spacer>
                <v-btn to="/login">
                    <p>Iniciar Sesión</p>
                </v-btn>
                <v-btn to="/register">
                    <p>Registrase</p>
                </v-btn>
            </v-list>
        </v-navigation-drawer>
        <v-main>
            <slot />
        </v-main>
    </v-layout>
</template>