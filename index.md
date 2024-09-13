---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "记录点滴"
  text: "学习成长且快乐"
  tagline: 快速访问
  image:
    src: /learn.svg
    alt: Chrome 浏览器插件
  actions:
    - theme: brand
      text: Markdown Examples
      link: /markdown-examples
    - theme: alt
      text: API Examples
      link: /api-examples

features:
  - title: 大师课
    details: 大师课学习过程总结
  - title: Vitepress 构建博客
    icon:
      src: /icon-vue.svg
    details: 四万字符数带你使用 Vitepress 构建博客并部署到 github 平台
    link: https://juejin.cn/post/7362547962604437541?searchId=2024091209070333CA5BD7354159DE472A
    linkText: 查看详情
  - title: 实用插件推荐
    icon:
      src: /chajian.svg
    details: 推荐一些对前端开发来说实用的 Chrome 插件。
    link: https://juejin.cn/post/7327893130572824611
    linkText: 查看详情
---
<style module>
article>img{
  height: 48px;
}
</style>
<!--@include: ./docs/components/test.md-->