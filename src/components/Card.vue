<template>
    <div class="card">
        <img :src="newsItem.imgUrl" :alt="newsItem.title">
        <a :href="newsItem.url" class="text-center">{{newsItem.text}}</a>
    </div>

</template>

<script>
export default {
name: 'Card',
props: ['newsItem']
}
</script>

<style scoped lang="scss">
.card {
    position: relative;
    margin-top: 20px;
    margin-bottom: 20px;
    img {
        max-width: 100%;
        border-radius: 5px;
    }
    a {
        position: absolute;
        top: 230px;
        left: 20px;
        right: 20px;
        font-size: 1.2rem;
        font-weight: 700;
        z-index: 1;
    }
}
.card::after {
    content: "";
    display: inline-block;
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-color: rgba(1,1,1,0.5);
    border-radius: 5px;
}
</style>