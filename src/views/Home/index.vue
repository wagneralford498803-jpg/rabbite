<script setup>
import HomeCategory from './components/HomeCategory.vue'
import HomeBanner from './components/HomeBanner.vue'
import HomeNew from './components/HomeNew.vue'
import HomeHot from './components/HomeHot.vue'
import HomeProduct from './components/HomeProduct.vue'
import HomePanel from './components/HomePanel.vue'

</script>

<template>
  <div class="container">
    <HomeCategory />
    <HomeBanner />
  </div>
  <HomeNew />
  <HomeHot />
  <HomeProduct />

  <HomePanel title="新鲜好物" subTitle="更多商品">

  </HomePanel>
  <!-- 更多热门商品 -->
  <HomePanel title="更多热门商品" subTitle="更多热门商品">
    <div class="product-list">
      插槽
    </div>
  </HomePanel>
  <!-- 更多商品 -->
  <HomePanel title="人气推荐" subTitle="更多商品">

  </HomePanel>
</template>
