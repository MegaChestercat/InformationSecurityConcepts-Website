<!-- <template>
    <div class="">
        <p class="text-h5 font-weight-bold text-center mt-16">El curso de "Introducción a la Seguridad Informática" posee el siguiente contenido:</p>
        <v-container class="mt-8">
            <v-row justify="center">
                <v-col>
                    <v-sheet :elevation="3" rounded>
                        <v-img height="170" width="220" src="https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/brain-training.svg" cover></v-img>
                        <p class="text-center font-weight-bold">Motivación: Amenazas de Ciberseguridad</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/ataques.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">La Web: Superficie, Deep y Dark</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/prevencion.png" cover></v-img>
                        <p class="text-center font-weight-bold">Tendencias en la Seguridad</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/prevencion.png" cover></v-img>
                        <p class="text-center font-weight-bold">La Arquitectura de Seguridad OSI</p>
                    </v-sheet>
                </v-col>
            </v-row>
            <v-row justify="center">
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/seguridad.png" cover></v-img>
                        <p class="text-center font-weight-bold">Motivación: Amenazas de Ciberseguridad</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/ataques.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">La Web: Superficie, Deep y Dark</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/prevencion.png" cover></v-img>
                        <p class="text-center font-weight-bold">Tendencias en la Seguridad</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/prevencion.png" cover></v-img>
                        <p class="text-center font-weight-bold">La Arquitectura de Seguridad OSI</p>
                    </v-sheet>
                </v-col>
            </v-row>
        </v-container>
        <div class="d-flex justify-center">
            <v-btn width="70vw" color="success" append-icon="mdi-arrow-right" to="/curso1/dashboard">
                Continuar
            </v-btn>
        </div>
    </div>
</template>
<style>

v-sheet{
    display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
	padding: 16px 24px;
	height: 176px;
	width: 188px;
	border: solid #e5e5e5;
	border-width: 2px 2px 4px;
	border-radius: 16px;
	cursor: pointer;
	transition: all 0.3s;
}


</style>
 -->

 <template>
    <div class="container">
      <h2 class="text-center mt-16">El curso de fundamentos I posee el siguiente contenido:</h2>
      <div class="content">
        <div class="card" v-for="(item, index) in items" :key="index" @click="navigate(item.link)">
          <img :src="item.image" alt="Imagen" class="card-img">
          <p class="text-center font-weight-bold">{{ item.title }}</p>
        </div>
      </div>
      <div class="d-flex justify-center mt-8">
        <v-btn to='/curso1/dashboard' size="x-large" width="70vh" append-icon="mdi-arrow-right" rounded="xl"color="success">Continuar</v-btn>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        items: [
          {
            title: "Motivación: Amenazas de Ciberseguridad",
            image: "https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/brain-training.svg",
            link: "/curso1/dashboard"
          },
          {
            title: "La Web: Superficie, Deep y Dark",
            image: "https://cdn.pixabay.com/photo/2015/12/08/19/08/castle-1083570_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Tendencias en la Seguridad",
            image: "https://cdn.pixabay.com/photo/2015/12/10/16/39/shield-1086702_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "La Arquitectura de Seguridad OSI",
            image: "https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/job-opportunities.svg",
            link: "/curso1/dashboard"
          },
          {
            title: "Amenazas en la Seguridad: Pasivas y Activas",
            image: "https://d35aaqx5ub95lt.cloudfront.net/images/user-motivation-survey/school.svg",
            link: "/curso1/dashboard"
          },
          {
            title: "Servicios de Seguridad y Mecanismos",
            image: "https://cdn.pixabay.com/photo/2013/07/12/19/23/vault-154685_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Un Modelo para la Seguridad en la Red",
            image: "https://cdn.pixabay.com/photo/2016/01/03/11/32/wireless-signal-1119306_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Métodos de Defensa: Biométricos",
            image: "https://cdn.pixabay.com/photo/2017/12/27/10/14/image-3042333_1280.png",
            link: "/curso1/dashboard"
          }
        ]
      };
    }
  };
  </script>
  
  <style>
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .content {
    display: grid;
    grid-auto-rows: 1fr;
    grid-gap: 45px;
    grid-template-columns: repeat(4, 1fr);
    margin-top: 32px;
  }
  
  .card {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 16px 24px;
    height: 176px;
    width: 188px;
    border: solid #e5e5e5;
    border-width: 2px 2px 4px;
    border-radius: 16px;
    cursor: pointer;
    transition: all 0.3s;
  }
  
  .card:hover {
    background: #f0f0f0;
    border-width: 2px;
  }
  
  .card-img {
    height: 80px;
    margin-bottom: 12px;
  }
  
  .text-center {
    text-align: center;
  }
  
  button {
    display: flex;
    justify-content: center;
    align-items: center;
    letter-spacing: 1px;
    height: 48px;
    width: 800px;
    border: none;
    outline: none;
    border-radius: 16px;
    background-color: #58cc02;
    margin-top: 16px;
    border: solid #58a700;
    border-width: 0px 0px 4px;
    font-size: 14px;
    text-transform: uppercase;
    color: #fff;
    font-weight: 600;
    cursor: pointer;
  }
  </style>
  