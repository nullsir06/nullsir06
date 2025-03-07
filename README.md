## Hi there 👋

<div align="center" class="main-container">
  ![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=Welcome%20to%20My%20GitHub!&fontSize=40&animation=fadeIn)

  <!-- GitHub统计卡片 -->
  <div class="flex-container">
    <img src="https://github-readme-stats.vercel.app/api?username=nullsir06&show_icons=true&theme=radical&hide_title=true" width="48%">
    <img src="https://github-readme-streak-stats.herokuapp.com?user=nullsir06&theme=radical&date_format=M%20j%5B%2C%20Y%5D" width="48%">
  </div>

  <!-- 动态旋转图标 -->
  <div class="icon-container">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="50" style="transform: rotate(360deg); animation: rotation 8s infinite linear;" onmouseover="this.style.animationPlayState='paused'" onmouseout="this.style.animationPlayState='running'">
  </div>

  <!-- 项目展示卡片 -->
  <div class="grid-container">
    <a href="https://github.com/nullsir06/blog_list">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=nullsir06&repo=blog_list&theme=dark&show_owner=true" />
    </a>
    <a href="https://github.com/nullsir06/unicafe">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=nullsir06&repo=unicafe&theme=dark&show_owner=true" />
    </a>
  </div>

  <!-- 3D贡献图 -->
  <div class="graph-container">
    [![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=nullsir06&bg_color=1a1b27&color=38bdae&line=4bc2a8&point=ffffff&area=true&hide_border=true)](https://git.io/streak-stats)
  </div>

  <!-- 访问人数 -->
  <div class="visitor-container">
    <a href="https://github.com/nullsir06" target="_blank">
      <img src="https://komarev.com/ghpvc/?username=nullsir06&label=Profile%20views&color=0e75b6&style=flat-square" alt="nullsir06" />
    </a>
  </div>

  ![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer&fontSize=20)
</div>

<style>
  .main-container {
    max-width: 1000px;
    margin: 0 auto;
  }

  .flex-container {
    display: flex;
    gap: 1rem;
    margin: 2rem 0;
  }

  .icon-container,
  .grid-container,
  .graph-container,
  .visitor-container {
    margin: 2rem 0;
  }

  .grid-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
  }

  @keyframes rotation {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(359deg);
    }
  }
</style>
