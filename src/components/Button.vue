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
        padding: 10px 18px;
        text-transform: uppercase;
        font-size: 0.9rem;
        border-width: 1px;
        border-style: solid;
        flex-shrink: 0;
        transition: transform 0.3s;
    }

    button:hover {
      transform: scale(1.2);
    }
</style>