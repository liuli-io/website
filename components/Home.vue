<template>
  <div>
    <Header />
    <section class="body-font">
      <div class="container mx-auto flex px-7 py-24 md:flex-row flex-col items-center">
        <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium ">
            Liuli
            <br class="hidden lg:inline-block">
            <br class="hidden lg:inline-block">
            <h3 class="text-2xl">
              构建一个多源、干净、个性化的阅读环境
            </h3>
          </h1>
          <p class="mb-8 leading-relaxed">
            Liuli是一个开源并且年轻的项目，我们利用机器学习实现广告分类，帮您过滤无效信息，打造一个干净且个性化的阅读环境。项目正处于发展初期，如果您对此很感兴趣，请点击下面的按钮，查看更多详情。
          </p>
          <div class="flex justify-center">
            <a href="https://github.com/howie6879/liuli" class="btn btn-primary">去看看</a>
          </div>
        </div>
        <div class="md:w-1/2 w-5/6 h:">
          <img class="pl-32 rounded " alt="hero" src="https://raw.githubusercontent.com/123seven/oss/master/images/Read.png">
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from './Header.vue'
import Footer from './Footer.vue'
export default {
  components: { Header, Footer }
}
</script>
