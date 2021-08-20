<template>
  <div class="home">
    <div>123</div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  components: {},
  methods: {
    test() {
      const a = 123
      const b = 233
      let c = 11
      c++
      console.log(c, b)
      console.log(a)
      console.log(123)
      const abc = '123123'
      const str = abc + '1231123'
      console.log(str, 'str')
      const str1 = 'wakatime can run in the right way???? I don\'t know'
      console.log(str1)
    }
  }
}
</script>
