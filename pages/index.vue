<template>
  <div class="page-index">
    <section class="about">
      <h2>夏目漱石</h2>
      <ArticleBody>
        <img src="~/assets/images/owl.png" alt="souseki" />
        <p>日本の小説家日本の小説家日本の小説家</p>
      </ArticleBody>
    </section>

    <section>
      <h2>代表作</h2>
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

<style lang="scss" scoped>
.about,
.works {
  h2 {
    display: flex;
    align-items: center;
    margin: 50px 0 30px;
    font-size: 30px;

    &::after {
      content: '';
      display: block;
      flex: 1;
      height: 1px;
      margin-left: 10px;
      background-color: $color-black;
    }
  }
}
</style>
