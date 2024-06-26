<template>
  <v-container class="comp pa-0">
    <v-row justify="center" no-gutters>
      <v-col cols=12>
        <p class="text-center blk">DESCRIPTION OF TRADE IN</p>
      </v-col>
      <v-col cols=2>
        <v-text-field :dirty="true"
					variant="solo" 
          label="YEAR"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6>
        <v-text-field :dirty="true"
					variant="solo"
          label="MAKE"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=4>
        <v-text-field :dirty="true"
					variant="solo"
          label="MODEL"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=4>
        <v-text-field :dirty="true"
					variant="solo" 
          label="BODY TYPE"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=4>
        <v-text-field :dirty="true"
					variant="solo"
          label="COLOR"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=4>
        <v-text-field :dirty="true"
					variant="solo"
          label="MILEAGE"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=12>
        <v-text-field :dirty="true"
					variant="solo" 
          label="VEHICLE I.D. OR SERIAL NO."
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=5>
        <v-text-field :dirty="true"
					variant="solo" 
          label="LICENSE OR TITLE NO."
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=7>
        <v-text-field :dirty="true"
					variant="solo" 
          label="LIENHOLDER'S NAME"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=12>
        <v-text-field :dirty="true"
					variant="solo" 
          label="LIENHOLDER'S ADDRESS"
          flat
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'DescriptionTradeIn',

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
  font-size: 10pt;
  font-weight: bold;
}

:deep(.v-field__field) label{
  font-size: 7pt;
}

:deep(.v-field__field) input{
  padding: 0;
  padding-left: 22px;
  padding-top: 15px;
  border: 1px solid gray;
  min-height: 20px;
  font-size: 10pt;
}
</style>
