---
title: DelightDocs
description: 这是一个希望分享些东西的博客网站
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Delightdocs: A Docsy Example and Starter Project!"
  height="full td-below-navbar"
  image_anchor="top"
%}}

<!--
  Want a cover without an image?
  Add the following argument to the blocks/cover shortcode:
    color="primary bg-gradient td-below-navbar"
-->

<!-- prettier-ignore -->
{{% _param description %}}
{.display-6}

<!-- prettier-ignore -->
<div class="td-cta-buttons my-5">
  <a {{% _param btn-lg primary %}} href="docs/">
    Learn more
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    Get the code
    {{% _param FA brands github "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

Delightdocs是一个用于分享知识和生活的个人博客网站，考虑到博主个人水平有限，还望各位以自己的思考为主
，也欢迎各位提出见解和补充

(遗憾的是，这个博客网站目前只是测试用，并不用来上架任何实际内容，或许以后会吧哈哈)

{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="New chair metrics!" icon="fa-lightbulb" %}}

The Goldydocs UI now shows chair size metrics by default.

Please follow this space for updates!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Contributions welcome!" icon="fab fa-github"
  url="https://github.com/google/docsy-example"
%}}

We do a [Pull Request](https://github.com/google/docsy-example/pulls)
contributions workflow on **GitHub**. New users are always welcome!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Follow us on X!" icon="fab fa-x-twitter"
  url="https://x.com/docsydocs"
%}}

For announcement of latest features etc.

{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="white" type="row text-center h1" %}}

上面的英文板块是关于Docsy模板的

{{% /blocks/section %}}

{{% blocks/section color="secondary" type="row text-center h1" %}}

这里什么也没有~

{{% /blocks/section %}}
