<template>
  <div class="d-flex align-center justify-center bg fill-height">
    <div >
      <v-card width="400" class=" px-5 pb-5 rounded-xl" color="rgba(255, 255, 255, 0.8)">
        <v-card-title class="my-3 text-center font-weight-bold">Iniciar Sesión</v-card-title>
        <form>
          <v-text-field
          label="Correo Electrónico"
          variant="solo">
          </v-text-field>
          <v-text-field
          label="Contraseña"
          variant="solo">
          </v-text-field>
          <div class="d-flex justify-center">
            <div class="d-block">
              <v-btn width="300" color="#0CE43D" class="text-none">
                <p>Iniciar Sesión</p>
              </v-btn>
              <v-btn width="300" class="d-block mt-4 text-none" color="#F11717">
                <p>Cancelar</p>
              </v-btn>
            </div>
    
          </div>
        </form>
      </v-card>
    </div>
  </div>
</template>
<script>
definePageMeta({
  layout: false
})
</script>
<style scoped>
.bg{
  background-image: url("../assets/auth_bg.png");
  background-size: cover;
}
</style>