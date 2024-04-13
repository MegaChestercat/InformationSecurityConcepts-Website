<template>
    <div class="d-flex justify-center fill-hight">
        <v-sheet :elevation="3" width="500" height="600" class="d-flex justify-center mt-15">
            <div>
                <v-avatar size="200" color="#79827B" class="mt-8"></v-avatar>
                <v-text-field variant="solo" class="mt-10" label="Nombre"></v-text-field>
                <v-text-field variant="solo" label="Correo Electrónico"></v-text-field>
                <v-text-field variant="solo" label="Contraseña"></v-text-field>
                <v-btn color="#EE3A1D" width="200" prepend-icon="mdi-logout">
                    <p>Cerrar Sesión</p>
                </v-btn>
            </div>
        </v-sheet>
    </div>
</template>