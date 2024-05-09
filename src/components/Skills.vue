<script setup>
import frontend from './utils/frontend.vue'
import backend from './utils/backend.vue'
import fullstack from './utils/fullstack.vue'
import database from './utils/db.vue'
</script>

<template>
  <div class="container py-4">
    <h2>Kemampuan Saya</h2>
    <frontend />
    <backend />
    <fullstack />
    <database />
    <div>
      <span>Arti warna: </span>
      <span class="badge bg-success">PRO</span>
      <span class="badge bg-secondary">MENENGAH</span>
      <span class="badge bg-danger">CUPU</span>
    </div>
  </div>
</template>
