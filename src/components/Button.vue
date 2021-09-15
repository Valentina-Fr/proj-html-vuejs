<template>
  <button type="button">{{text}}</button>
</template>

<script>
export default {
name: 'Button',
props: ['text']
}
</script>

<style scoped lang="scss">
    button {
        color: #fff;
        border-radius: 5px;
        padding: 5px 10px;
        text-transform: uppercase;
        font-size: 0.7rem;
        border-width: 1px;
        border-style: solid;
    }
</style>