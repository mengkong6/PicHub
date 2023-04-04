<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
  <div class="about-wrapper">
    <h2>关于</h2>
    <div class="content">
      本项目基于<a target="_blank" href="https://github.com/lewkamtao/PicHub">PicHub</a>进行的二次开发
      <br/>它是一个基于 GitHub API & jsDelivr 开发的具有 CDN 加速功能的图床管理工具
      <br /><br />
      调整内容
      <ul>
        <li>新增，支持html复制</li>
        <li>新增，CDN选择，防止污染</li>
        <li>优化，fancybox升级到5.0</li>
        <li>优化，左上图标居中（强迫症）</li>
        <li>优化，图片全部重命名16位字符串</li>
        <li>修复，favicon图标找不到</li>
      </ul>

      <br />
      特别的是
      <ul>
        <li>支持点击、拖拽、复制图片上传</li>
        <li>
          谷歌 <a href="https://squoosh.app" target="_blank">squoosh</a>
          压缩图片
        </li>
        <li>
          <a href="https://fancyapps.com" target="_blank">Fancybox</a>
          的加持，让图片的预览效果更好。
        </li>
        <li>安全且快速，数据只存在本地。</li>
        <li>封装组件（按钮表单上传等）</li>
        <li>复制转换 Markdown 格式</li>
      </ul>
      <br />
      <h2>如有问题请联系，微信公众号：干货助手</h2>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about-wrapper {
  max-width: 700px;
  margin: 70px auto;
  padding: 50px;
  color: var(--text-color);
  .content {
    margin-top: 20px;
    color: var(--text-color);
    line-height: 30px;
    a {
      color: var(--primary-color);
      text-decoration: underline;
    }
  }
}
</style>
