<template>
<section>
  <section>
    <h2>jQuery和Vue</h2>
    <div style="text-align: left;">
      <p class="fragment">jQuery是一个JavaScript函数库</p>
      <p class="fragment">Vue是一套用于构建用户界面的渐进式框架</p>
    </div>
  </section>

  <section data-transition="convex">
    <h2>DOM</h2>
    <p>(Document Object Model, 文档对象模型)</p>
    <p>提供一种便捷、高效、可跟踪的文档修改方式。</p>
    <div class="fragment">
      <img src="@/assets/1.jpeg" alt="">
    </div>
  </section>

  <section data-transition="convex">
    <div>
      <p style="float: left;">代码</p>
      <img src="@/assets/3.png" width="50%">
    </div>
    <div>
      <p style="float: left;">页面</p>
      <img src="@/assets/2.png" width="50%">
    </div>
  </section>

  <section data-transition="convex">
    <h2>虚拟DOM</h2>
    <pre>
      <!-- <div id="app">
        <p class="text">hello world!!!</p>
      </div> -->
      <code style="max-height: initial; margin-top: -3em;">
        {
          tag: 'div',
          props: {
            id: 'app'
          },
          chidren: [
            {
              tag: 'p',
              props: {
                className: 'text'
              },
              chidren: [
                'hello world!!!'
              ]
            }
          ]
        }
      </code>
    </pre>
  </section>

  <section data-transition="convex">
    <h2>虚拟DOM优势</h2>
    <ul>
      <li class="fragment">空div实现众多的规范(属性、DOM事件)</li>
      <li class="fragment">diff算法通过补丁方式修改变化的DOM</li>
      <li class="fragment">跨平台能力，浏览器DOM、移动端组件</li>
    </ul>
  </section>
</section>
</template>

<style scoped>
</style>
