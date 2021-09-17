<template>
  <div class="card">
    <h4>{{title}}</h4> 
    <ul>
        <li v-for="(link, index) in links" :key="index">
            <i class="fas fa-angle-right font-grey"></i>
            <a class="font-grey" :href="link.url">{{link.text}}</a>
        </li>
    </ul>
  </div>
</template>

<script>
export default {
name: 'LinkCard',
props: ['links', 'title']
}
</script>

<style scoped lang="scss">
.card {
    height: 100%;
    border-radius: 5px;
    background-color: rgba(22, 30, 33, 0.4);
    padding: 25px 0 0 25px;
    h4 {
        color: #fff;
        padding-bottom: 20px;
    }
    li {
        margin-bottom: 20px;
    }
    .fas {
        margin-right: 10px;
        vertical-align: middle;
    }
    a {
        font-size: 0.9rem;
    }
}
</style>