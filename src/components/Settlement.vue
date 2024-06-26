<template>
  <v-container class="comp pa-0">
    <v-row justify="center" no-gutters align="center">
      <v-col cols=12>
        <p class="text-center blk">SETTLEMENT</p>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">CASH PRICE OF VEHICLE</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">TRADE IN</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">SALES TAX</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">PLATES</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">BUYERS TAG</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">DOCUMENTARY FEE</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">INSPECTION FEE</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">TITLE FEE</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">VEHICLE INV. TAX</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">TOTAL CASH PRICE</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">LESS DEPOSITS*</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">DOWN PAYMENT</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
      <v-col cols=6 class="text-end">
        <p class="txt">BALANCE DUE ON DELIVERY</p>
      </v-col>
      <v-col cols=4>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
          reverse
        ></v-text-field>
      </v-col>
      <v-col cols=2>
        <v-text-field class="extra-dense"
					variant="outlined"
          rounded="0"
          :hide-details="true"
          density="compact"
        ></v-text-field>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'Settlement',

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

.txt {
  font-size: 9pt;
  font-weight: bold;
  padding-right: 10px;
}

:deep(.extra-dense) input {
  padding-top: 0;
  padding-bottom: 0;
  font-size: 14px;
  min-height: 20px;
}
</style>
