<template>
  <div class="hello">
    <h1 v-if="first">{{ msg }}</h1>
    <input type="checkbox" v-model="first" />
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: '欢迎',
      first: false
    }
  }
}
</script>
