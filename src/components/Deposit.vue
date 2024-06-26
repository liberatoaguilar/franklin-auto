<template>
  <v-container class="comp pa-0">
    <v-row justify="start" no-gutters align="end">
      <v-col cols=12>
        <h3 class="title">*Deposit if not refundable if sale is not made, </h3>
      </v-col>
      <v-col cols="auto">
        <h3 class="title pb-1">by:</h3>
      </v-col>
      <v-col cols="auto">
        <v-text-field
          class="pa-0 ma-0 pl-2 pb-1 extra-dense"
          variant="underlined"
          density="compact"
          type="date"
          hide-details
        ></v-text-field>
      </v-col>
      <v-spacer/>
      <v-col cols="auto">
        <div class="text-center initials pr-10">
          <center>
            <hr width="50px"/>
            <p>INITIALS</p>
          </center>
        </div>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'Deposit',

  data: () => ({

  }),
}
</script>

<style scoped>
.comp {
  border: 2px solid black;
}

.title {
  font-size: 12pt;
  text-align: justify;
  padding-left: 10px;
}

.initials {
  text-align: center;
  font-size: 8pt;
  padding: 10px;
  padding-bottom: 0;
}

:deep(.extra-dense) input {
  font-size: 10pt;
}
</style>
