<template>
  <v-container class="pa-0">
    <v-row dense>
      <v-col cols=12 class="pb-0">
        <Header></Header>
      </v-col>
      <v-col cols=6 class="pa-1">
        <v-row style="flex-direction: column" dense>
          <v-col>
            <SoldTo></SoldTo>
          </v-col>
          <v-col>
            <DescriptionTradeIn></DescriptionTradeIn>
          </v-col>
          <v-col>
            <Initials></Initials>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols=6 class="pa-1">
        <v-row style="flex-direction: column" dense>
          <v-col>
            <Description></Description>
          </v-col>
          <v-col>
            <Settlement></Settlement>
          </v-col>
          <v-col>
            <Deposit></Deposit>
          </v-col>
          <v-col>
            <Signatures></Signatures>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import { defineComponent } from 'vue';
import SoldTo from '../components/SoldTo.vue';
import Description from '../components/Description.vue';
import DescriptionTradeIn from '../components/DescriptionTradeIn.vue';
import Settlement from '../components/Settlement.vue';
import Initials from '../components/Initials.vue';
import Deposit from '../components/Deposit.vue';
import Signatures from '../components/Signatures.vue';
import Header from '../components/Header.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    SoldTo,
    Description,
    DescriptionTradeIn,
    Settlement,
    Initials,
    Deposit,
    Signatures,
    Header,
  },
});
</script>
