<template>
  <section class="brand-bg-secondary">
      <div class="container">
        <h5 class="brand-color">OUR EDITORIAL CONTENT</h5>
        <h2>Latest <span class="brand-bg-secondary brand-color">News</span></h2>
        <div class="d-flex">
            <p class="font-grey">Every week we publish content about what is best in the business world</p>
            <Button class="btn-brand" text="See all"/>
        </div>
        <div class="row">
            <div class="col" v-for="(news, index) in newsData" :key="index">
                <Card :newsItem="news"/>
            </div>
        </div>    
      </div>
  </section>
</template>

<script>
import Button from './Button.vue';
import Card from './Card.vue';

export default {
name: 'News',
components: {
    Button,
    Card,
},
data(){
    return {
        newsData:[
            {
                imgUrl: require ('../assets/images/news-1.jpg'),
                title: 'news 1',
                text: 'Increasing creativity is possible for everyone',
                url:'#'
            },
            {
                imgUrl: require ('../assets/images/news-2.jpg'),
                title: 'news 2',
                text: 'Because market research is part of the business plan',
                url:'#'
            },
            {
               imgUrl: require ('../assets/images/news-3.jpg'),
               title: 'news 3',
               text: 'Working from home is a new trend',
               url:'#'
            }
        ]
    }
}
}
</script>

<style scoped lang="scss">
h5 {
    padding-top: 40px;
    padding-bottom: 20px;
}

h2 {
    padding-bottom: 20px;
}

p {
    padding-right: 250px;
}

.d-flex {
    justify-content: space-between;
    align-items: center;
}

.col {
    width: calc(100% / 3 - 20px);
}
    
.row {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

</style>