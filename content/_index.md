---
title: ''
summary: 何明岳的个人主页：科研、工作、教育与项目经历。
type: landing
sections:
- block: resume-biography-3
  content:
    username: me
    text: ''
    headings:
      about: 个人简介
      education: 教育背景
      interests: 研究兴趣
  design:
    background:
      gradient_mesh:
        enable: true
    name:
      size: md
    avatar:
      size: medium
      shape: circle
- block: markdown
  content:
    title: 研究方向
    subtitle: ''
    text: 我的研究经历涵盖深度伪造检测的对抗攻击、小样本类增量音频分类与遥感红外图像超分辨率。结合智能驾驶算法评测与自动化测试的工程经验，关注模型在实际场景中的鲁棒性与持续学习能力。
  design:
    columns: '1'
- block: collection
  id: papers
  content:
    title: 代表性科研经历
    filters:
      folders:
      - publications
      featured_only: true
  design:
    view: article-grid
    columns: 2
- block: collection
  content:
    title: 科研论文
    text: ''
    filters:
      folders:
      - publications
      exclude_featured: false
  design:
    view: citation
- block: markdown
  id: contact
  content:
    title: 联系方式
    text: '邮箱：[scouthe@163.com](mailto:scouthe@163.com)


      电话 / 微信：[(+86) 13037114551](tel:+8613037114551)


      GitHub：[scouthe](https://github.com/scouthe)'
  design:
    columns: '1'
---
