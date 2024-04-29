<!-- <template>
    <div class="">
        <p class="text-h5 font-weight-bold text-center mt-16">El curso de fundamentos II posee el siguiente contenido:</p>
        <v-container class="mt-8">
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
            </v-row>
            <v-row justify="center" class="my-5">
                <v-col cols="2">
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/quiz.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">3 Exámenes Rápidos</p>
                    </v-sheet>
                </v-col>
                <v-col>
                    <v-sheet :elevation="3" width="220" height="220" rounded>
                        <v-img height="170" width="220" src="~~/assets/cursos/resumen/adicional.jpg" cover></v-img>
                        <p class="text-center font-weight-bold">Documentación Adicional</p>
                    </v-sheet>
                </v-col>
                <v-col cols="2"></v-col>
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

</style> -->



<template>
    <div class="container">
      <h2 class="text-center mt-16">El curso de fundamentos II posee el siguiente contenido:</h2>
      <div class="content">
        <div class="card" v-for="(item, index) in items" :key="index" @click="navigate(item.link)">
          <img :src="item.image" alt="Imagen" class="card-img">
          <p class="text-center font-weight-bold">{{ item.title }}</p>
        </div>
      </div>
      <div class="d-flex justify-center mt-8">
        <button @click="navigate('/curso2/dashboard')">Continuar</button>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        items: [
          {
            title: "Hacking y Hackers",
            image: "https://cdn.pixabay.com/photo/2018/08/18/00/32/hunter-3614043_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Detección de Intrusos",
            image: "https://cdn.pixabay.com/photo/2020/04/07/15/07/vault-5013752_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Acercamiento a la Detección de Intrusos",
            image: "https://cdn.pixabay.com/photo/2014/04/03/10/53/shredder-311638_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Honeypots y Herramientas de Sniffing",
            image: "https://cdn.pixabay.com/photo/2017/01/30/14/11/blue-light-2020909_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Ejemplo de Sistema: Snort",
            image: "https://cdn.pixabay.com/photo/2020/07/02/04/24/eye-5361679_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Firewalls",
            image: "https://cdn.pixabay.com/photo/2012/04/12/11/07/firewall-29503_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "DDoS y Software Malicioso",
            image: "https://cdn.pixabay.com/photo/2012/04/25/00/33/virus-41379_1280.png",
            link: "/curso1/dashboard"
          },
          {
            title: "Resumen",
            image: "https://cdn.pixabay.com/photo/2013/07/13/12/12/camera-159401_1280.png",
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
  