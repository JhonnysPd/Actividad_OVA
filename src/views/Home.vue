<template>
<div class="fondo">
    <v-parallax
      dark
      src="@/assets/bg.png"
      cols="12"
      height="1000"
      class="fondo1"
    >
     <v-row align="center" justify="center">
        <v-col class="text-center" cols="12">
          <v-container
            class="col-12"
            responsive
          >
            <v-row>
              <v-col>
               <img src="../assets/12.png">
                 <div class='hero-btn'>
                  <router-link to="/dashboard" tag="div">
                     <button class='btn'>SIGUIENTE</button>
                </router-link>
               </div>

               
              </v-col>
            </v-row>
          </v-container>
        </v-col>
      </v-row>
     </v-parallax>
  </div>
 
</template>

<style scoped>
.fondo1 {
  display: grid;
  margin: 0;
  padding: 0;
  position: relative;
  height: 100vh;
  width: 100%;
  background-size: cover;
  background-image: url('../assets/bg.png');
}

.v-align {
  text-align: center;
  margin: 100px auto;
	width: 80%;
}

.v-align img { 
	margin-bottom: 3%;
	width: 32%;
}

@import url("https://fonts.googleapis.com/css?family=Montserrat:400, 600");
.hero-btn {
  width: 220px;
  margin: auto;
}
.hero-btn .btn {
  background-color: #ff0083;
  border: none;
  outline: none;
  text-decoration: none;
  text-transform: uppercase;
  color: #fff;
  display: inline-block;
  width: 100%;
  height: 100%;
  text-align: center;
  line-height: 66px;
  font-size: 22px;
  font-family: "Montserrat", sans-serif;
  font-weight: 600;
  letter-spacing: 2px;
  -moz-border-radius: 6px;
  -webkit-border-radius: 6px;
  border-radius: 6px;
  white-space: nowrap;
  text-overflow: ellipsis;
  -moz-user-select: -moz-none;
  -ms-user-select: none;
  -webkit-user-select: none;
  user-select: none;
  -moz-appearance: none;
  cursor: pointer;
  -webkit-appearance: none;
  -moz-box-shadow: 0 15px 40px rgba(255, 0, 131, 0.5);
  -webkit-box-shadow: 0 15px 40px rgba(255, 0, 131, 0.5);
  box-shadow: 0 15px 40px rgba(255, 0, 131, 0.5);
  -moz-transform: perspective(600px) rotateX(0deg) scale(1);
  -ms-transform: perspective(600px) rotateX(0deg) scale(1);
  -webkit-transform: perspective(600px) rotateX(0deg) scale(1);
  transform: perspective(600px) rotateX(0deg) scale(1);
  -moz-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  -webkit-transition: all 0.2s linear;
  transition: all 0.2s linear;
}
.hero-btn .btn:hover {
  background-color: #e60076;
  -moz-box-shadow: 0 20px 40px rgba(255, 0, 131, 0.5);
  -webkit-box-shadow: 0 20px 40px rgba(255, 0, 131, 0.5);
  box-shadow: 0 20px 40px rgba(255, 0, 131, 0.5);
}
.hero-btn .btn:active {
  -moz-transform: perspective(600px) rotateX(15deg) scale(0.9);
  -ms-transform: perspective(600px) rotateX(15deg) scale(0.9);
  -webkit-transform: perspective(600px) rotateX(15deg) scale(0.9);
  transform: perspective(600px) rotateX(15deg) scale(0.9);
  font-size: 21px;
  -moz-box-shadow: 0 20px 40px rgba(255, 0, 131, 0.5);
  -webkit-box-shadow: 0 20px 40px rgba(255, 0, 131, 0.5);
  box-shadow: 0 20px 40px rgba(255, 0, 131, 0.5);
}

@media screen and (max-width: 1000px) {
	.v-align img {
		width: 65%;
	}

}


</style>