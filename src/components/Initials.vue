<template>
  <v-container class="comp pa-0">
    <v-row justify="center" no-gutters>
      <v-col cols=6 class="right-box">
        <div>
          <h4 class="title">SOLD AS IS<br/>NO WARRANTY</h4>
          <p class="txt">The Dealer, Franklin Auto Sales makes no warranties. The Dealer herby
          disclaims all warranties, either expressed or implied, for new or used motor
          vehicles, including any implied warranty of merchantability or fitness for a
          particular purpose, and the Dealer niether assumes nor authorizes any other
          person to assume for it any liability in connection with the sale of the
          vehicle.</p>
          <div class="text-center initials">
            <center>
              <hr width="50px"/>
              <p>INITIALS</p>
            </center>
          </div>
        </div>
      </v-col>
      <v-col cols=6 class="left-box">
        <div>
          <h4 class="title pt-4 pb-2">DOCUMENTARY FEE</h4>
          <p class="txt">A Documentary Fee is not an official fee. A documentary is not
          required by law, but may be charged to buyers for handling documents and
          performing services related to the closeing of a sale. Buyers may avoid payment
          of the fee to the seller by handling the documents and performing the services
          related to the closing of the sale. This notice is required by law.</p>
          <div class="text-center initials">
            <center>
              <hr width="50px"/>
              <p>INITIALS</p>
            </center>
          </div>
        </div>
      </v-col>
      <v-col cols=12>
        <v-row no-gutters>
          <v-col cols=3>
            <div class="text-center initials pl-2 pt-8">
              <center>
                <hr width="50px"/>
                <p>INITIALS</p>
              </center>
            </div>
          </v-col>
          <v-col cols=9>
            <p class="cap-txt">IT IS RECOMMENDED THAT A MECHANIC OF YOUR CHOICE EXAMINE THE
            VEHICLE YOU PLAN TO BUY BEFORE IT IS TAKEN FROM THE LOT.</p>
          </v-col>
          <v-col cols=3>
            <div class="text-center initials pl-2">
              <center>
                <hr width="50px"/>
                <p>INITIALS</p>
              </center>
            </div>
          </v-col>
          <v-col cols=9>
            <p class="cap-txt">AFTER THE VEHICLE LEAVES THE LOT, IT IS YOUR
            RESPONSIBILITY FOR ANY MALFUNCTION THAT MAY OCCUR.</p>
          </v-col>
          <v-col cols=3>
            <div class="text-center initials pl-2">
              <center>
                <hr width="50px"/>
                <p>INITIALS</p>
              </center>
            </div>
          </v-col>
          <v-col cols=9>
            <p class="cap-txt">ES RECOMENDABLE QUE SU MECANICO DE CONFIANZA EXAMINE EL
            VEHICULO QUE USTED DESEA COMPRAR ANTES DE ADQUIRIRLO.</p>
          </v-col>
          <v-col cols=3>
            <div class="text-center initials pl-2 pb-2">
              <center>
                <hr width="50px"/>
                <p>INITIALS</p>
              </center>
            </div>
          </v-col>
          <v-col cols=9>
            <p class="cap-txt">SALIDO EL VEHICULO DE LA AGENCIA QUEDA BAJO SU
            RESPONSIBILIDAD TODO TIPO DE FALLA QUE PUEDA OCURRIR.</p>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'Initials',

  data: () => ({

  }),
}
</script>

<style scoped>
.comp {
  border: 2px solid black;
}

.blk {
  background-color: black;
  color: white;
}

.txt {
  font-size: 7pt;
  text-align: justify;
  padding: 10px;
  line-height: 1em;
}

.title {
  text-align: center;
  padding-top: 5px;
  line-height: 1em;
  font-size: 10pt;
}

.initials {
  text-align: center;
  font-size: 6pt;
  padding: 8px;
  padding-top: 15px;
}

.right-box {
  border-right: 1px solid black;
  border-bottom: 2px solid black;
}

.left-box {
  border-left: 1px solid black;
  border-bottom: 2px solid black;
}

.cap-txt {
  font-size: 6pt;
  text-align: justify;
  padding: 10px;
  padding-bottom: 0px;
  font-weight: bold;
  line-height: 1em;
}
</style>
