<template>
  <div class="list-item">
    <slot />
  </div>
</template>

<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  name: 'GListItem',
  props: {},
  setup() {},
})
</script>
