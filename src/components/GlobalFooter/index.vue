<template>
  <global-footer class="footer custom-render">
    <template v-slot:links>
      <!-- <a href="" target="_blank">link</a> -->
    </template>
    <template v-slot:copyright>
      <a target="_blank">Niepr R&D</a>
    </template>
  </global-footer>
</template>

<script>
import { GlobalFooter } from '@ant-design-vue/pro-layout'

export default {
  name: 'ProGlobalFooter',
  components: {
    GlobalFooter
  }
}
</script>
