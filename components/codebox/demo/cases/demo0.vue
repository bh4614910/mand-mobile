<template>
  <div class="md-example-child md-example-child-codebox md-example-child-codebox-0">
    <md-codebox
      v-model="code"
      :maxlength="4"
      autofocus
    />
  </div>
</template>

<script>
import {Codebox} from 'mand-mobile'

export default {
  name: 'codebox-demo',
  /* DELETE */
  title: '默认',
  /* DELETE */
  components: {
    [Codebox.name]: Codebox,
  },
  data() {
    return {
      code: '',
    }
  },
}

</script>
