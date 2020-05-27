<template>
  <div class="page-about">
    <section class="about">
      <h2>初めまして</h2>
      <div class="article-body">
        <p>夏目漱石夏目漱石夏目漱石夏目漱石夏目漱石夏目漱石夏目漱石夏目漱石</p>
      </div>
    </section>
    <section class="history">
      <h2>経歴</h2>
      <div class="article-body">
        <h3>幼少期</h3>
        <p>どこに生まれてどこで育った</p>
        <h3>イギリス留学</h3>
        <p>英語教師英語教師英語教師英語教師英語教師英語教師</p>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
@import '~assets/scss/variables';

.about,
.history {
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
