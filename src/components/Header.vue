<template>
  <v-container class="pa-0">
    <v-row justify="center" no-gutters>
      <v-col cols=auto class="text-center pa-0">
        <h1 class="title">Franklin Auto Sales</h1>
      </v-col>
      <v-col cols=12 class="text-center pa-0 pt-1">
        <b><p>Phone (915) 566-55555 • Fax (915) 565-3305</p></b>
      </v-col>
      <v-col cols=12 class="text-center pa-0">
        <p>4811 Pershing • El Paso, TX 79903</p>
      </v-col>
    </v-row>
    <v-row justify="space-between" no-gutters align="end">
      <v-col cols=2 class="text-center">
        <v-text-field
          variant="underlined"
          prefix="STOCK #"
          :dirty="true"
          hide-details
        ></v-text-field>
      </v-col>
      <v-col cols=auto class="text-center">
        <b><h3 class="pb-1">Motor Vehicle Purchase Agreement / Bill of Sale</h3></b>
      </v-col>
      <v-col cols="auto" class="text-center">
        <v-text-field
          variant="underlined"
          prefix="DATE:"
          type="date"
          :dirty="true"
          class="extra-dense"
          hide-details
        ></v-text-field>
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
.title {
  font-size: 32pt;
  line-height: 1em;
  color: #50A6DE;
  border-bottom: solid 2px #D3104F;
  width: 440px;
}

h4 {
  padding-top: 10px;
}

:deep(.extra-dense) input {
  padding-top: 18px;
}

p {
  line-height: 1.1em;
}
</style>
