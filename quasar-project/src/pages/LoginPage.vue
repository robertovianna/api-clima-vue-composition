<template>
  <q-page class="flex flex-center">
    <q-card class="my-card">
      <img src="https://cdn.quasar.dev/img/mountains.jpg" ratio="1" width="200px" />

      <q-card-section>
        <div class="text-h5">Login</div>
        
      </q-card-section>

      <q-card-section class="q-pt-none">
        {{ lorem }}
      </q-card-section>
    </q-card>

    <q-card class="my-card">
      <q-img src="https://cdn.quasar.dev/img/parallax2.jpg">
        <div class="absolute-bottom text-subtitle2 text-center">
          Title
        </div>
      </q-img>
    </q-card>
  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
