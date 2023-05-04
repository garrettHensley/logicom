<template>
  <v-app>
    <v-container>
      <v-row>
        <v-col>
          <p class="text-h4 text-center">Voice Provisioning</p>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-select
            variant="solo"
            bg-color="blue-lighten-5"
            label="Select a Partner"
            :items="['Sprout']"
          ></v-select>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="6">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="First Name"
          ></v-text-field>
        </v-col>
        <v-col cols="6">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Last Name"
          ></v-text-field>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="3">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Address"
          ></v-text-field>
        </v-col>
        <v-col cols="3">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="City"
          ></v-text-field>
        </v-col>
        <v-col cols="3">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="State"
          ></v-text-field>
        </v-col>
        <v-col cols="3">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Zip"
          ></v-text-field>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="6">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Contact Phone"
          ></v-text-field>
        </v-col>
        <v-col cols="6">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Contact Email"
          ></v-text-field>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="4">
          <v-select
            variant="solo"
            bg-color="blue-lighten-5"
            label="Customer Type"
            :items="[]"
          ></v-select>
        </v-col>
        <v-col cols="4">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Phone Number to Provision"
          ></v-text-field>
        </v-col>
        <v-col cols="4">
          <v-text-field
            variant="solo"
            bg-color="blue-lighten-5"
            label="Sip Password"
          ></v-text-field>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="4">
          <v-select
            variant="solo"
            bg-color="blue-lighten-5"
            label="Ported"
            :items="['']"
          ></v-select>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="4">
          <v-checkbox label="Bypass E11 Address Automation"></v-checkbox>
        </v-col>
        <v-col cols="8">
          <v-alert prominent type="warning" variant="outlined" border="top">
            (By checking "Bypass E911 Address Automation" you agree to manually add this
            phone number and address to Bandwidth)
          </v-alert>
        </v-col>
      </v-row>
      <v-row>
        <v-col>
          <v-btn class="bg-indigo-darken-4">Provision</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script setup>
// noth9ing
</script>

<style scoped></style>
