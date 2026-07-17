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

        [查看研究视频与项目 →](projects/)
    design:
      columns: '1'
  - block: markdown
    id: publications
    content:
      title: 代表性论文
      subtitle: 论文成果及对应的仿真与实飞验证
      text: |-
        ## 已发表

        <article class="paper-showcase">
          <span class="paper-status published">SCI Q1 · 已发表</span>
          <h3>Image-based Visual Servo Docking Control for Autonomous Aerial Refueling</h3>
          <p class="paper-authors">Quan Quan, <strong>Runxiao Liu</strong>, Hao Liu, Zeqing Ma, Jinrui Ren</p>
          <p><em>Journal of Guidance, Control, and Dynamics</em>, 48(7), 2025 · 学生一作，导航领域顶刊</p>
          <div class="paper-videos single"><figure><video controls preload="metadata"><source src="videos/图像伺服空中加油论文视频.mp4" type="video/mp4"></video><figcaption>图像伺服自主空中加油仿真</figcaption></figure></div>
        </article>

        <article class="paper-showcase">
          <span class="paper-status published">SCI Q1 · 中科院一区 TOP · 已发表</span>
          <h3>Probe-and-Drogue Autonomous Aerial Refueling with a Velocity Control Mode: An Image-Based Visual Servo Method</h3>
          <p class="paper-authors"><strong>Runxiao Liu</strong>, Yuantan Huang, Jinrui Ren, Kai-Yuan Cai, Quan Quan</p>
          <p><em>Aerospace Science and Technology</em>, 176(A), 112007, 2026 · 第一作者</p>
          <div class="paper-videos single"><figure><video controls preload="metadata"><source src="videos/速度接口空中加油图像伺服控制论文视频.mp4" type="video/mp4"></video><figcaption>速度控制接口下的图像伺服自主空中加油</figcaption></figure></div>
        </article>

        <article class="paper-showcase">
          <span class="paper-status published">SCI Q1 · 已发表</span>
          <h3>Virtual-Passivity-Based Distributed Cooperative Control for Multi-UAV Heavy-Load Transport</h3>
          <p class="paper-authors"><strong>Runxiao Liu</strong>, Xiangli Le, Shuang Gu, Quan Quan</p>
          <p><em>IEEE Transactions on Network Science and Engineering</em>, 13, 5905–5923, 2026 · 第一作者</p>
          <div class="paper-videos"><figure><video controls preload="metadata"><source src="videos/速度跟踪控制论文仿真.mp4" type="video/mp4"></video><figcaption>协同速度跟踪仿真</figcaption></figure><figure><video controls preload="metadata"><source src="videos/速度跟踪控制论文实验.mp4" type="video/mp4"></video><figcaption>6 架无人机吊运 6 kg 负载实飞实验</figcaption></figure></div>
        </article>

        ## 审稿中与已投稿

        <article class="paper-showcase">
          <span class="paper-status reviewing">SCI Q1 · 共同一作 · 一审</span>
          <h3>Self-Organizing Aerial Swarm Robotics for Resilient Load Transportation: A Table-Mechanics-Inspired Approach</h3>
          <p class="paper-authors">Quan Quan, Jiwen Xu, <strong>Runxiao Liu</strong>, Yi Ding, Jiaxing Che, Kai-Yuan Cai</p>
          <p><em>International Journal of Robotics Research</em> · 机器人领域顶刊</p>
          <div class="paper-videos"><figure><video controls preload="metadata"><source src="videos/耗散协同论文500机仿真.mp4" type="video/mp4"></video><figcaption>500 机协同运输仿真</figcaption></figure><figure><video controls preload="metadata"><source src="videos/耗散协同论文5机飞行实验.mp4" type="video/mp4"></video><figcaption>5 机室外飞行实验</figcaption></figure><figure><video controls preload="metadata"><source src="videos/耗散协同论文负载能力异构实验.mp4" type="video/mp4"></video><figcaption>负载能力异构实验</figcaption></figure><figure><video controls preload="metadata"><source src="videos/耗散协同论文绳索长度异构实验.mp4" type="video/mp4"></video><figcaption>缆绳长度异构实验</figcaption></figure><figure><video controls preload="metadata"><source src="videos/耗散协同论文容错实验.mp4" type="video/mp4"></video><figcaption>飞行器容错实验</figcaption></figure><figure><video controls preload="metadata"><source src="videos/耗散协同论文空中脱钩实验.mp4" type="video/mp4"></video><figcaption>空中脱钩实验</figcaption></figure></div>
        </article>

        <article class="paper-showcase">
          <span class="paper-status reviewing">SCI Q1 · 中科院一区 TOP · 大修</span>
          <h3>Virtual-Tube-Based Cooperative Transport Control for Multi-UAV Systems in Constrained Environments</h3>
          <p class="paper-authors"><strong>Runxiao Liu</strong>, Pengda Mao, Xiangli Le, Shuang Gu, Yapeng Chen, Quan Quan</p>
          <p><em>IEEE Transactions on Industrial Electronics</em> · 第一作者</p>
          <div class="paper-videos single"><figure><video controls preload="metadata"><source src="videos/虚拟管道耗散协同控制论文视频.mp4" type="video/mp4"></video><figcaption>受限空间中的虚拟管道协同运输</figcaption></figure></div>
        </article>

        <article class="paper-showcase">
          <span class="paper-status reviewing">SCI Q1 · 中科院一区 TOP · 已投稿</span>
          <h3>Aerial Placement of Cable-Suspended Loads: A Multi-UAV Cooperative Control Approach Integrating Visual Servo and Virtual Passivity</h3>
          <p class="paper-authors"><strong>Runxiao Liu</strong>, Pengda Mao, Xiangli Le, Shuang Gu, Yapeng Chen, Quan Quan</p>
          <p><em>IEEE/ASME Transactions on Mechatronics</em> · 第一作者</p>
          <div class="paper-videos single"><figure><video controls preload="metadata"><source src="videos/图像伺服精确放置论文视频.mp4" type="video/mp4"></video><figcaption>多机协同悬挂负载精确放置</figcaption></figure></div>
        </article>
    design:
      columns: '1'
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
