<script setup lang="ts">
import { ref } from 'vue'
import '../styles/Card.scss'

const props = defineProps<{title_header: string, title_left: string, title_right: string}>()

</script>

<template>
<div class="card">
    <div class="title-container">
      <h2> TKO IMA VEĆEG???? </h2>
    </div>
    <div class="divider">
      &nbsp;
    </div>
    <div class="survey-container">
      <div class="survey">
        <div class="left">
          <p>Milanović</p>
        </div>
        <div class="right">
          <p>Plenković</p>
        </div>
      </div>
    </div>
  </div>
</template>