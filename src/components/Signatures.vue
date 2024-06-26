<template>
  <v-container class="pa-0">
    <v-row justify="start" no-gutters align="end">
      <v-col cols=12>
        <b><p class="txt">Buyer acknowledges that this agreement incldudes all of the terms
        and conditions pertaining to this purchase and no other agreement or promise of
        any kind (verbal or written) will be recognized. Upon failure or refusal of the
        buyer to complete this agreement, all or part of the cash deposit may be retained
        as liquidated damages. The buyer certifies he/she is of legal age and
        acknowledges herewith receipt of a copy of this agreement. Not valid unless
        accepted by Authorized Representative.</p></b>
      </v-col>
      <v-col cols=6>
        <h4>BUYER'S SIGNATURE: </h4>
      </v-col>
      <v-spacer/>
      <v-col cols=6>
        <hr/>
      </v-col>
      <v-col cols=6>
        <h4>SALESPERSON: </h4>
      </v-col>
      <v-spacer/>
      <v-col cols=6>
        <hr/>
      </v-col>
      <v-col cols=6>
        <h4>DEALER ACCEPTANCE: </h4>
      </v-col>
      <v-spacer/>
      <v-col cols=6>
        <hr/>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'Signatures',

  data: () => ({

  }),
}
</script>

<style scoped>
.txt {
  font-size: 9pt;
  text-align: justify;
  padding-bottom: 0px;
  line-height: 1em;
}

h4 {
  padding-top: 10px;
  font-size: 11pt;
}
</style>
