<template>
    <div>
        <div class="mt-10 ml-15">
            <p class="text-h3 font-weight-black">Selecciona tu propio camino.</p>
            <p class="mt-7 text-h4 font-weight-black">Tu eliges como!</p>
            <v-divider :thickness="5" color='orange' width="100" class="ml-15 mt-8 border-opacity-100"></v-divider>
        </div>
        <div class="mt-10">
            <v-sheet :elevation="8" height="400" class="mx-8" rounded>
                <v-slide-group show-arrows height="600">
                    <v-slide-group-item >
                        <v-sheet :elevation="3" width="500" height="330" class="my-10 mx-7">
                            <div class="d-flex justify-center">
                                <v-img height="170" width="500" src="../assets/auth_bg.png" cover></v-img>
                            </div>
                            <p class="text-h2 text-center font-weight-medium">Curso 1</p>
                            <p class="text-h6 text-center font-weight-medium">4.2/5</p>
                            <div class="d-flex justify-center">
                                <v-btn to="/curso1/resumen" width="300" color="#55FC7B" class="mx-15  mt-5">Fundamentos I</v-btn>
                            </div>
                        </v-sheet>
                    </v-slide-group-item>
                    <v-slide-group-item>
                        <v-sheet :elevation="3" width="500" height="330" class="mr-7 my-10">
                            <div class="d-flex justify-center">
                                <v-img height="170" width="500" src="../assets/encryption.jpg" cover></v-img>
                            </div>
                            <p class="text-h2 text-center font-weight-medium">Curso 2</p>
                            <p class="text-h6 text-center font-weight-medium">3.7/5</p>
                            <div class="d-flex justify-center">
                                <v-btn to="/curso2/resumen" width="300" color="#55FC7B" class="mx-15 mt-5">Fundamentos II</v-btn>
                            </div>
                        </v-sheet>
                    </v-slide-group-item>
                    <v-slide-group-item>
                        <v-sheet :elevation="3" width="500" height="330" class="my-7 my-10">
                            <div class="d-flex justify-center">
                                <v-img height="170" width="500" src="../assets/auth_bg.png" cover></v-img>
                            </div>
                            <p class=" text-h2 text-center font-weight-medium">Curso 3</p>
                            <p class="text-h6 text-center font-weight-medium">4.7/5</p>
                            <div class="d-flex justify-center">
                                <v-btn to="/curso3/resumen" width="300" color="#55FC7B" class="mx-15 mt-5">Fundamentos III</v-btn>
                            </div>
                        </v-sheet>
                    </v-slide-group-item>
                </v-slide-group>
            </v-sheet>
        </div>
        
    </div>

    

</template>
    

<script>
export default{
  head(){
    return{
      title: "Mi pagina de prueba"
    };
  }
}

</script>
<style scoped>
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html,
body {
  font-size: 62.5%;
  font-family: "Raleway", sans-serif;
}
@media screen and (max-width : 620px) {
  html,
body {
    font-size: 45%;
  }
}
@media screen and (max-width : 480px) {
  html,
body {
    font-size: 70%;
  }
}

.forhtml {
  background: radial-gradient(circle at bottom, #aac1c7, #f7fbfb 80%) no-repeat center center fixed;
  background-size: cover;
}

body {
  color: #686e74;
  
  min-height: 100vh;
}

section {
  width: 100vw;
  max-width: 90%;
  min-width: 58.9rem;
  margin: 0 0 0 5%;
  
}
@media screen and (max-width : 480px) {
  section {
    min-width: 19rem;
  }
}

.title {
  font-size: 4rem;
  font-weight: 900;
  padding-top: 10vh;
}
@media screen and (max-width : 480px) {
  .title {
    font-size: 3rem;
    text-align: center;
    position: relative;
    padding-top: 6vh;
  }
}
.title:after {
  content: "";
  display: block;
  height: 0.3rem;
  width: 5.4rem;
  background-color: #fbcd8a;
  transform: translate(0.3rem, 2rem);
}
@media screen and (max-width : 480px) {
  .title:after {
    left: 50%;
    position: absolute;
    transform: translate(-50%, 2rem);
  }
}

.cards-container{
  width: 100%;
  overflow-x: auto;
}

.cards {
  padding-top: 6rem;
  display: flex;
  justify-content: flex-start;
  width: 100%;
  overflow-x: auto;
  white-space: nowrap;
  scrollbar-width: thin; /* Ancho de la barra de desplazamiento en navegadores compatibles */
  scrollbar-color: #aaa #eee; /* Color de la barra de desplazamiento en navegadores compatibles */
}
@media screen and (max-width : 480px) {
  .cards {
    flex-direction: column;
    align-items: center;
  }
}

.card {
  width: 45rem;
  height: 30.5rem;
  background-color: #f9fbfb;
  border-radius: 6px;
  position: relative;
  display: inline-block; /* Cambiar de flex a inline-block */
  color: #5a6c7a;
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.05rem;
  box-shadow: 0 1rem 3rem #aac1c7;
  margin: 0 5% 3% 0; /* Ajuste para evitar el espacio entre las cards */
  flex-shrink: 0; /* Evitar que las cards se reduzcan cuando no hay suficiente espacio */
}
@media screen and (max-width : 480px) {
  .card {
    margin-bottom: 2rem;
  }
}

.card:hover{
  cursor: pointer;
  background-color: rgba(222, 222, 222, 0.393);
}

.card__svg-container {
  height: 50%;
  display: flex;
  justify-content: center;
  align-items: flex-end;
}
.card__svg-wrapper {
  width: 8rem;
}
.card__count-container {
  flex-grow: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}
.card__count-text {
  transform: translate(0, -0.5rem);
}
.card__count-text--big {
  text-transform: uppercase;
  font-size: 5rem;
  font-weight: 300;
}
.card__stuff-container {
  margin: 0 auto;
  width: 90%;
  height: 15%;
  border-top: 2px solid #e7edef;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgba(38, 255, 0, 0.553);
}
.card__stuff-icon, .card__stuff-text {
  display: inline-block;
}
.card__stuff-icon {
  width: 1.3rem;
  height: 1.3rem;
  transform: translate(0, -0.3rem);
}
.card__stuff-text {
  text-transform: uppercase;
  margin-left: 0.4rem;
  transform: translate(0, -0.2rem);
}
.card:after {
  content: "";
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  width: 16rem;
  height: 5.625rem;
  transform: translate(1.5rem, 22.5rem);
  pointer-events: none;
}
.card--oil:after {
  background-image: radial-gradient(ellipse at top, rgba(106, 122, 135, 0.5), transparent 70%);
}
.card--tree:after {
  background-image: radial-gradient(ellipse at top, rgba(106, 191, 96, 0.5), transparent 70%);
}
.card--water:after {
  background-image: radial-gradient(ellipse at top, rgba(96, 203, 231, 0.5), transparent 70%);
}
</style>
