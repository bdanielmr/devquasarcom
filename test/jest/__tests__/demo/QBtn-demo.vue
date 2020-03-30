<template>
<div>
  <p class="textContent">{{ input }}</p>
  <span>{{ counter }}</span>
  <br>
  <q-btn label="increment" id="mybutton" @click="increment()"></q-btn>
  <q-btn label="reset" @click="decrement(counter)"></q-btn>
</div>
</template>

<script>
export default {
  name: 'QBUTTON',
  data () {
    return {
      counter: 0,
      input: 'counter'
    }
  },
  methods: {
    increment () {
      this.counter++
    },
    decrement (counter) {
      this.counter = 0
    }
  }
}
</script>
