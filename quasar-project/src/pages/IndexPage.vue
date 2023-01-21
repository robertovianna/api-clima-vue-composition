<template>
     <div class="q-pa-md">
    <q-btn-toggle
      v-model="model"
      toggle-color="primary"
      :options="[
        {label: 'One', value: 'one'},
        {label: 'Two', value: 'two'},
        {label: 'Three', value: 'three'}
      ]"
    />
  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage'
})
</script>
