---
title: ''
date: 2026-07-17
type: landing
design:
  spacing: '5rem'
sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      headings:
        about: 关于我
        education: 教育经历
        interests: 研究方向
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: large
        shape: circle
  - block: markdown
    id: research
    content:
      title: 研究概览
      subtitle: 面向真实飞行任务，从控制理论走向多机实飞验证
      text: |-
        <div class="research-stats">
          <div><strong>6</strong><span>SCI 论文</span></div>
          <div><strong>3</strong><span>Q1 论文已发表</span></div>
          <div><strong>5</strong><span>发明专利</span></div>
          <div><strong>47</strong><span>荣誉与奖励</span></div>
        </div>

        ### 多无人机协同吊运

        以耗散系统、虚拟无源系统和虚拟管道理论为基础，研究多架无人机通过柔性缆绳协同运输重载的方法。重点解决异构载荷能力、缆长误差、飞行器故障、连接中断、受限空间避障与精确放置等问题，完成最高 **6 架无人机协同吊运 6 kg 负载**的室外实验。

        ### 图像视觉伺服与自主空中加油

        面向软管式自主空中加油与空中对接，建立图像视觉伺服模型并设计速度控制模式下的对接控制器。搭建 MATLAB、UE4、YOLO 与飞控系统融合的高保真平台，在尾流、湍流、阵风和相机安装误差下验证控制方法。

        [查看研究视频与项目 →](/projects/)
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: 代表性论文
      subtitle: 多无人机协同运输、图像伺服与自主飞行
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: citation
  - block: markdown
    id: honors
    content:
      title: 荣誉与科研实践
      text: |-
        - 国家奖学金、国家励志奖学金，北京航空航天大学优秀毕业生、优秀研究生
        - RoboMaster 无人飞行器智能感知技术竞赛全国总决赛冠军
        - 全国虚拟现实技术及应用创新大赛特等奖
        - 深度参与自主空中加油重大项目及国家电网无人化组塔国家重点研发计划
        - 具备从理论推导、仿真平台搭建到 ROS/PX4 实飞代码部署和多机飞行实验的完整研究经验
    design:
      columns: '1'
---
