<template>
  <div class="page-index">
    <section class="about">
      <h2>夏目漱石</h2>
      <div class="article-body">
        <img src="~/assets/images/owl.png" alt="souseki" />
        <p>日本の小説家日本の小説家日本の小説家</p>
      </div>
    </section>

    <section>
      <h2>代表作</h2>
      <div class="article-body">
        <p>吾輩は猫であるがデビュー作</p>
        <ul>
          <li>吾輩は猫ある</li>
          <li>吾輩は猫ある</li>
          <li>吾輩は猫ある</li>
          <li>吾輩は猫ある</li>
        </ul>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
@import '~assets/scss/variables';

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

.article-body {
  h3 {
    font-size: 20px;
    margin: 30px 0 20px;
  }

  p {
    line-height: 1.75;
    + p {
      margin-top: 20px;
    }

    a {
      color: $color-blue;
    }
  }

  ul {
    list-style: circle;
    margin-top: 20px;
    margin-left: 20px;

    li {
      &:nth-of-type(n + 2) {
        margin-top: 0.5em;
      }
    }
  }
  img {
    max-width: 100%;
  }
}
</style>
