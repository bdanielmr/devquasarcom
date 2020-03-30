<template>
<div>
  <EssentialLink title="hi" caption="" link="https://www.youtube.com/"/>
  <QBUTTON/>
</div>
</template>

<script>
import EssentialLink from '../components/EssentialLink'
import QBUTTON from '../../test/jest/__tests__/demo/QBtn-demo'
export default {
  name: 'PageIndex',
  components: {
    EssentialLink,
    QBUTTON
  }
}
</script>
