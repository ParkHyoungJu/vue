<template>
  <div id="activity" >
      <body_top></body_top>
      <body_bottom></body_bottom>
  </div>
</template>

<script>
import BODYTOP from './Body_top'
import BODYBOTTOM from './Body_bottom'

export default {
  components: {
      'body_top' : BODYTOP,
      'body_bottom' : BODYBOTTOM
  }
}
</script>
