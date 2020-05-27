<template>
  <div class="layout-error">
    <section class="error">
      <h2 class="seciton-title">404</h2>
      <ArticleBody>
        <h3>名前はまだない</h3>
        <p>アクセスされたページは存在しない</p>
      </ArticleBody>
    </section>
  </div>
</template>

<script>
import ArticleBody from '~/components/common/ArticleBody'

export default {
  components: {
    ArticleBody
  }
}
</script>
