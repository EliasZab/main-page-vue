<template>
  <v-app>
        <!--  ////////////////////// HEADER ////////////////////////  -->
    <v-toolbar
      height="100%"
      elevation="0"
    >
      <v-row>
        <v-col cols="5" md="2">
          <v-img
            class="img mb-2"
            max-height="100%"
            max-width="100%"
            width="100%"
            src="./assets/images/OLIVOS PNG GRAND 1.png"
          ></v-img>
        </v-col>

        <v-spacer></v-spacer>
        
        <v-col class="mt-5" cols="6" md="3">

          <v-row>
            <v-col class="iconos" cols="4" xs="2" md="2">
              
              <a href="#">
                <v-img
                  class="img"
                  max-height="100%"
                  max-width="100%"
                  width="85%"
                  src="./assets/images/Internet (1).png"
                ></v-img>
              </a>
              
              <a href="#">
                <v-img
                  class="img"
                  max-height="100%"
                  max-width="100%"
                  width="85%"
                  src="./assets/images/Instagram Circle.png"
                ></v-img>
              </a>

              <a href="#">
                <v-img
                  class="img"
                  max-height="100%"
                  max-width="100%"
                  width="85%"
                  src="./assets/images/Facebook.png"
                ></v-img>
              </a>
            </v-col>

          </v-row>

        </v-col>
      </v-row>
    </v-toolbar>

      <hr class="hr1 mt-2" size="40">
    
        <v-row class="">
      <v-col class="mt-10" cols="12" md="12">
          <h1>Lorem ipsum</h1>
          <h3>Lorem ipsum dolor sit amet, dolor sit amet</h3>
      </v-col>

    <!--  ////////////////////// INPUTS ////////////////////////  -->

    <v-row class="mb-16">
        <v-col class="mt-16 ml-16 mr-10" cols="12" md="5">
          
          <v-card class="pa-5">
            <v-form
              ref="form"
              v-model="valid"
              lazy-validation
            >
              <v-text-field
                :rules="[v => !!v || 'Is required']"
                label="Lorem ipsum Lorem ipsum"
                outlined
                required
              ></v-text-field>

              <v-text-field
                :rules="[v => !!v || 'Is required']"
                label="Lorem ipsum Lorem ipsum"
                outlined
                required
              ></v-text-field>

              <v-text-field
                :rules="[v => !!v || 'Is required']"
                label="Lorem ipsum Lorem ipsum"
                outlined
                required
              ></v-text-field>

              <v-text-field
                :rules="[v => !!v || 'Is required']"
                label="Lorem ipsum Lorem ipsum"
                outlined
                required
              ></v-text-field>

              <v-checkbox
                :rules="[v => !!v || 'You must agree to continue!']"
                label="Acepto los términos y condiciones"
                required
              ></v-checkbox>

              <v-btn
                color="#FF4E17"
                dark
                rounded
                width="90%"
                height="40px"
              >
                Lorem ipsum 
              </v-btn>

            </v-form>
          </v-card>
        </v-col>

        <v-col class="mt-16 mr-16 ml-10" cols="12" md="5">
          <v-img
          class="img ma-auto"
          max-height="100%"
          max-width="100%"
          width="100%"
          src="./assets/images/FAMILIA MANUAL 1.png"
          ></v-img>

          <p class="parrafo">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
            sit amet, consectetur adipiscing elit. 
          </p>
        </v-col>
      </v-row>
    </v-row> 

    <!--  ////////////////////// SOMOS ////////////////////////  -->

    <div class="div-Somos">
      <v-row>
        <v-col class="mt-10 mb-10" cols="12" md="12">
          <h3 class="h3-somos">Somos tu mejor opcion en la protección exequial de tu familia, aquí te contamos por qué:</h3>
        </v-col>
        <v-col>
          <v-row>
            <v-col class="ma-auto" cols="12" md="2">
              <v-avatar
                color="white"
                size="150"
              >
                <v-img
                  class="img"
                  max-height="45%"
                  max-width="45%"
                  width="100%"
                  src="./assets/images/Pray.png"
                ></v-img>
              </v-avatar>
              <p>Lorem ipsum dolor sit amet, dolor sit amet</p>
            </v-col>

            <v-col class="ma-auto" cols="12" md="2">
              <v-avatar
                color="white"
                size="150"
              >
                <v-img
                  class="img"
                  max-height="45%"
                  max-width="45%"
                  width="100%"
                  src="./assets/images/Pray.png"
                ></v-img>
              </v-avatar>
              <p>Lorem ipsum dolor sit amet, dolor sit amet</p>
            </v-col>

            <v-col class="ma-auto" cols="12" md="2">
              <v-avatar
                color="white"
                size="150"
              >
                <v-img
                  class="img"
                  max-height="45%"
                  max-width="45%"
                  width="100%"
                  src="./assets/images/Pray.png"
                ></v-img>
              </v-avatar>
              <p>Lorem ipsum dolor sit amet, dolor sit amet</p>
            </v-col>

          </v-row>
        </v-col>
      </v-row>
    </div>
    <!--  ////////////////////// VECTOR ////////////////////////  -->

    <v-img
      class="img ma-auto"
      max-height="100%"
      max-width="100%"
      width="100%"
      src="./assets/images/Vector.png"
    ></v-img>

    <!--  ////////////////////// QUE PLAN ////////////////////////  -->

    <v-row>
      <v-col class="mt-16 mb-10" cols="12" md="12">
        <h1>¿Que plan de protección escoges?</h1>
        <h3>Contamos con una variedad de planes exequiales según tus necesidades:</h3>
      </v-col>

      <v-col class="mb-16">
        <v-row>
          <v-col class="ma-auto" cols="12" md="4">
            <v-card>
              <v-img
                class="img ma-auto"
                max-height="100%"
                max-width="70%"
                width="100%"
                src="./assets/images/Mesa de trabajo 1 1.png"
              ></v-img>
              <h1>Planes Empresas</h1>
              </v-card>
          </v-col>

          <v-col class="ma-auto" cols="12" md="4">
            <v-card>
              <v-img
                class="img ma-auto"
                max-height="100%"
                max-width="70%"
                width="100%"
                src="./assets/images/Mesa de trabajo 1 copia 1.png"
              ></v-img>
              <h1>Planes Personas</h1>
              </v-card>
          </v-col>
        </v-row>
      </v-col>
    </v-row>

     <v-img
      class="img ma-auto"
      max-height="100%"
      max-width="100%"
      width="100%"
      src="./assets/images/Vector 2.png"
    ></v-img>   

    <!--  ////////////////////// SUMERGÉTE ////////////////////////  -->

    <v-row class="mb-16">
      <v-col class="mt-16" cols="12" md="12">
        <h1 class="mb-5">Sumergéte en un mundo de protección y muchos beneficios</h1>
        <h3 class="mb-7">Afiliandote desde aquí, reclama tu tarjeta beneficios con cobertura inmediata</h3>
        <v-img
          class="img ma-auto"
          max-height="100%"
          max-width="25%"
          width="100%"
          src="./assets/images/Rectangle 8.png"
        ></v-img>
      </v-col>
      <v-img
        class="img mt-16"
        max-height="100%"
        max-width="100%"
        width="100%"
        src="./assets/images/Vector (1).png"
      ></v-img>
    </v-row>


    <v-row class="mb-16 ml-16 mr-16">
      <v-col class="mr-5" cols="12" md="5">
        <v-img
          class="img mt-5"
          max-height="100%"
          max-width="100%"
          width="100%"
          src="./assets/images/Mesa de trabajo 2 1.png"
        ></v-img>
      </v-col>

      <v-col class="ml-10" cols="12" md="6">
        <v-col>
          <h3 class="mt-10">Lorem ipsum dolor sit amet, dolor sit amet</h3>
        </v-col>
        
        <v-col>
            <v-btn
              color="#FF4E17"
              dark
              rounded
              width="80%"
              height="40px">
              Lorem ipsum 
            </v-btn>
        </v-col>
      </v-col>
    </v-row>


    <!--  ////////////////////// FOOTER ////////////////////////  -->

    <hr class="hr1" size="30">

    <v-footer>
      <v-row>
        <v-col class="mt-1 mb-1">
          <h1 class="h1-footer">© 2022 Digital Alliance</h1>
        </v-col>
      </v-row>
    </v-footer>

  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  text-align: center;
}
.iconos{
  display: flex;
}
.hr1{
  height: 3px;
  background: rgb(219, 219, 219);
  border: none;
}
.div-inputs{
  border-radius: 5%;
  box-shadow: 2px 2px 2px 2px rgba(0, 0, 0, 0.2);
  padding: 30px;
}
h1, h2{
  color: #FF4E17;
}
h3{
  font-size: 30px;
  color: black;
}
p{
  color: black;
}
.h3-somos{
  font-size: 40px;
  font-weight: 400;
}
.parrafo{
  font-size: 30px;
  text-align: justify;
}
.div-Somos{
  background: #FF4E17;
}
.div-Somos h3{
  color: white;
  margin-left: 20%;
  margin-right: 20%;
  text-align: center;
}
.div-Pray{
  background: white;
  border-radius: 50%;
  width: 150px;
  height: 150px;
  align-self: center;
}
.div-Somos p{
  color: white;
  font-size: 25px;
}
.h1-footer{
  color: #A9A2A2;
  font-size: 25px;
  font-weight: 400;
}
</style>