<template>
<section>
  <section data-transition="convex">
    <h2>前后端分离</h2>
    <ul>
      <li class="fragment">不分离优点</li>
      <li class="fragment">分离后优点</li>
      <li class="fragment">适用场景</li>
    </ul>
  </section>
  <section data-transition="convex">
    <h2>前后端不分离优点</h2>
    <ul>
      <li class="fragment">开发快速</li>
      <li class="fragment">页面加载快</li>
      <div style="font-size: 0.7em;">
        <p class="fragment">1. 省去了客户端JS或异步二次请求数据，服务端的网络环境要优于客户端</p>
        <p class="fragment">2. 首屏加载时间更快，浏览器内容解析优化机制能够发挥作用，DOM渲染</p>
      </div>
      <li class="fragment">SEO效果好</li>
      <div style="font-size: 0.7em;">
        <p class="fragment">网络抓取工具并不会等待异步请求完成后再行抓取页面内容</p>
        <p class="fragment">操作演示</p>
      </div>
    </ul>
  </section>
  <section data-transition="convex">
    <h2>前后端分离优点</h2>
    <ul>
      <li class="fragment">
        <div>分工协作<span class="fragment">(社会分工——工业革命的主线)</span></div>
      </li>
      <div style="font-size: 0.7em;">
        <p class="fragment">工业1.0实现了工匠与工人的分工</p>
        <p class="fragment">工业2.0开始了管理革命，实现操作工与管理层的分工</p>
        <p class="fragment">工业3.0，出现了管理工具，实现了管理层与管理咨询、管理管理软件工具的分工</p>
      </div>
      <li class="fragment">SPA体验好 WEB页面称作WEB APP</li>
      <li class="fragment">跨平台复用性好</li>
      <div style="font-size: 0.7em;">
        <p class="fragment">后端的接口的复用</p>
        <p class="fragment">前端的虚拟DOM思想</p>
      </div>
    </ul>
  </section>
  <section data-transition="convex">
    <div>
      <img src="@/assets/5.png" alt="">
    </div>
  </section>
  <section data-transition="convex">
    <h2>适用场景</h2>
    <ul>
      <li class="fragment">
        <div>企业官网<span class="fragment">  --- SSR</span></div>
      </li>
      <li class="fragment">
        <div>管理系统<span class="fragment">  --- SPA</span></div>
      </li>
      <li class="fragment">
        <div>多平台终端<span class="fragment">  --- 前后端分离</span></div>
      </li>
    </ul>
  </section>
</section>
</template>

<style scoped>
</style>
