<template>
    <div class="card">
        <img :src="newsItem.imgUrl" :alt="newsItem.title">
        <address>
            <div><i class="fas fa-user"></i>&nbsp;{{newsItem.author}}</div>
            <div><i class="far fa-clock"></i>&nbsp;{{newsItem.days}} Days Ago</div>
        </address>
        <a :href="newsItem.url" class="text-center">{{newsItem.text}}</a>
        <p>{{newsItem.preview}}</p>
        <div class="overlay"></div>
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
    z-index: 1;
    img {
        max-width: 100%;
        border-radius: 5px;
    }
    a {
        position: absolute;
        top: 210px;
        left: 20px;
        right: 20px;
        font-size: 1.2rem;
        font-weight: 700;
        z-index: 3;
    }
    p {
        display: none;
        position: absolute;
        bottom: 30px;
        left: 20px;
        right: 20px;
        color: #fff;
        text-align: center;
        font-size: 1rem;
        z-index: 2;
    }
    address {
        display: none;
        position: absolute;
        top: 40px;
        left: 10px;
        z-index: 1;
    }
}
address div{
    display: inline-block;
    padding: 0 20px;
    color: #fff;
}
.overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-color: rgba(1,1,1,0.5);
    border-radius: 5px;
}

.card:hover p, .card:hover address{
    display: block;
}

.card:hover .overlay {
    background-color: rgba(1,1,1,0.7);
}

.fas, .far {
    margin-right: 8px;
}
</style>