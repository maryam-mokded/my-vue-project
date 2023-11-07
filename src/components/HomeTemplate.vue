<template>
  <v-container class="fill-height">
    <v-responsive class="align-center text-center fill-height">
      <h1>Test library project</h1>

      <HomeLibrary></HomeLibrary>

      <Stepper></Stepper>
    </v-responsive>
  </v-container>
</template>

<script lang="ts" setup>
import { HomeLibrary } from 'my-library'
import  {Stepper}  from 'my-first-library'
</script>
