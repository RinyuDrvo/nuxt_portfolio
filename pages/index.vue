<template>
  <div class="page-index">
    <section class="about">
      <h2 class="section-title">夏目漱石</h2>
      <ArticleBody>
        <img src="~/assets/images/owl.png" alt="souseki" />
        <p>日本の小説家日本の小説家日本の小説家</p>
      </ArticleBody>
    </section>

    <section>
      <h2 class="section-title">代表作</h2>
      <ArticleBody>
        <p>吾輩は猫であるがデビュー作</p>
        <ul>
          <li>吾輩は猫ある</li>
          <li>吾輩は猫ある</li>
          <li>吾輩は猫ある</li>
          <li>吾輩は猫ある</li>
        </ul>
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
