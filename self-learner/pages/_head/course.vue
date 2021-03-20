<template>
    <div>
        <h1>Bonjour tout le monde !</h1>
        <b>{{param}}</b>
    </div>
</template>

<script>
export default {
  async asyncData({ params, redirect }) {
    return {
        param: params.head
    }
  }
}
</script>
