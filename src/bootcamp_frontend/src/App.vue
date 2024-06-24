<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Siema!
    <br/>
    Licznik: {{ counter }} <br/>
    <button @click="increase">Zwiększ licznik</button>
  </main>
</template>

<script>
export default {
  data() {
    return {
      counter: 0
    }
  },
  methods: {
    increase() {
      this.counter++
    }
  },
}
</script>
