<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >

   
    <q-card class="q-mt-md" style="width: 300px; text-align: center">
      <q-card-section>
        <div class="text-h6">Dobrodosli u quasar</div>
        <p>komponenta qcard dodana.</p>
      </q-card-section>

      <q-btn label="klikni" color="primary" class="q-mt-md" />
    </q-card>
  </q-page>
</template>


<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
