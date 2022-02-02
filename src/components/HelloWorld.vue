<template>
  <h1>Nguyễn Anh Tuấn</h1>
            <p>Software developer and game designer</p>
            <i>
                Give a man a game and he will have fun for a day. Teach a man to make game and he will never have fun again.
            </i>
            <p>Author: someone on the internet</p>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
</style>