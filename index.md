---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: '大模型微调与部署指南'
  text: ''
  tagline: '大模型基础知识、如何微调及部署'
  image:
    src: /logo.png
    alt: logo

  actions:
    - theme: brand
      text: 开始阅读
      link: /intro
---

# 关于本书

这是一本专注于大模型微调和部署的开源电子书，详细介绍了微调所需的相关知识，包括：

- 大模型基础知识
- 微调的基本原理、需要哪些资源
- 微调中的所有超参数解释
- 如何提升微调速度、降低显存占用
- 如何构造训练数据、评估模型效果
- 如何部署微调后的模型

相对于其它书籍和文献，本书的特点是：

1. **专注于微调**，因此能有更多篇幅详细介绍所有参数细节。
2. **追求实用性**，不再介绍已经很少人用的 RNN、Masked、Encode、Adapter 等技术，本书所有介绍的内容都是当前流行的技术。
3. **重视理论和实践结合**，不仅有公式、图解和源码。
4. **善于使用工具**，介绍了如何借助工具来调试和分析大模型，相比理论分析，工具的输出结果更直观也更易用。
5. **深入底层原理**，分析如何提升内核性能及减低显存占用。

除此之外，本书还提供了所有引用 arXiv 论文的翻译稿，请访问「[幻觉翻译](https://hjfy.top)」平台查看。
