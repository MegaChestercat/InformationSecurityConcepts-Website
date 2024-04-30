<template>
  <v-col>
    <h1 class="mb-6">Quick Access</h1>
    <div class="scroll-container">
      <v-row class="mx-auto">
        <v-slide-group show-arrows>
          <NuxtLink to="/curso1/dashboard" style="text-decoration: none;">
            <div style="display: flex; flex-direction: column;">
              <v-card class="mr-5 rounded-lg" width="150" height="150" theme="dark" image="https://www.incibe.es/sites/default/files/images/ransomware/cabecera-ransomeware.png">
              </v-card>
              <div style="margin-top: 10px; font-weight: bold;" class="text-black">Curso 1</div>
            </div>
          </NuxtLink>


          <NuxtLink to="/curso2/dashboard" style="text-decoration: none;">
            <div style="display: flex; flex-direction: column;">
              <v-card class="mr-5 rounded-lg" width="150" height="150" theme="dark" image="https://assets-global.website-files.com/62e153e41d6ee298cc9a98f7/631884aaffc021f328c0ef72_Firewall.png">
              </v-card>
              <div style="margin-top: 10px; font-weight: bold;" class="text-black">Curso 2</div>
            </div>
          </NuxtLink>

          <NuxtLink to="/curso3/dashboard" style="text-decoration: none;">
            <div style="display: flex; flex-direction: column;">
              <v-card class="mr-5 rounded-lg" width="150" height="150" theme="dark" image="../assets/encryption.jpg">
              </v-card>
              <div style="margin-top: 10px; font-weight: bold;" class="text-black">Curso 3</div>
            </div>
          </NuxtLink>
        </v-slide-group>
      </v-row>

      <h1 class="mt-6">Previews</h1>
    
      <v-row>
        <v-slide-group show-arrows>
          <v-card
          class="ma-5 rounded-lg"
            max-width="400" >
            <v-img
              class="align-end text-white"
              height="200"
              src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Use_Cases_for_Cyber_Security.jpg"
              cover
            >
              <v-card-title>
                <div style="margin-top: 10px; font-weight: bold;">La Arquitectura de Seguridad OSI</div></v-card-title>
            </v-img>

            <v-card-subtitle class="pt-4">Curso 1 - Tema 4</v-card-subtitle>

            <v-card-text>
              <div>Conoce las 7 capas que caracterizan la comunicación de red y siembran las bases de la seguridad informática.</div>
            </v-card-text>

            <v-card-actions>
              <v-btn to="/curso1/temas/tema4" color="orange" block>Begin</v-btn>
            </v-card-actions>
          </v-card>

          <v-card
          class="ma-5 rounded-lg"
            max-width="400" >
            <v-img
              class="align-end text-white"
              height="200"
              src="https://www.cgtechnologies.com/wp-content/uploads/2023/01/what-is-cyber-security-1024x683.jpg"
              cover
            >
              <v-card-title>
                <div style="margin-top: 10px; font-weight: bold;">Detección de Intrusos</div></v-card-title>
            </v-img>

            <v-card-subtitle class="pt-4">Curso 2 - Tema 2</v-card-subtitle>

            <v-card-text>
              <div>Conoce más acerca de la estrategia para lograr detectar a posibles intrusos dentro de un sistema informático.</div>
            </v-card-text>

            <v-card-actions>
              <v-btn to="/curso2/temas/tema2" color="orange" block>Begin</v-btn>
            </v-card-actions>
          </v-card>

          <v-card
          class="ma-5 rounded-lg"
            max-width="400" >
            <v-img
              class="align-end text-white"
              height="200"
              src="https://cioafrica.co/wp-content/uploads/2024/01/cyber-security.jpeg"
              cover
            >
              <v-card-title>
                <div style="margin-top: 10px; font-weight: bold;">Data Encryption Standard</div>
              </v-card-title>
            </v-img>

            <v-card-subtitle class="pt-4">Curso 3 - Tema 6</v-card-subtitle>

            <v-card-text>
              <div>Conoce las bases sobre uno de los primeros algoritmos de cifrado moderno.</div>
            </v-card-text>

            <v-card-actions>
              <v-btn to="/curso3/temas/tema6" color="orange" block>Ir</v-btn>
            </v-card-actions>
          </v-card>
        </v-slide-group>
      </v-row>
    </div>
  </v-col>
</template>

<script>
  export default {
    data: () => ({
      messages: [
        {
          from: 'Successful',
          message: `Completed assignment 1`,
          time: '10:42am',
          color: 'green',
        },
        {
          from: 'Successful',
          message: 'Completed task 1',
          time: '10:37am',
          color: 'green',
        },
        {
          from: 'In Progress',
          message: 'Task 2 to be completed',
          time: '9:47am',
          color: 'red',
        },
      ],
    }),
  };
</script>

<style scoped>
.container {
  padding: 20px;
}

.search-container {
  position: relative;
}

.search-bar {
  width: calc(100% - 30px); /* Adjust to accommodate the icon width */
  padding: 10px;
  padding-right: 30px; /* Space for the icon */
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 16px;
  outline: none;
}

.search-icon {
  position: absolute;
  top: 50%;
  right: 10px;
  transform: translateY(-50%);
  color: #888;
}
</style>
