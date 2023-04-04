<div align="center">
<img src="https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/logo.png" width="200" alt="cantor" align=center />

基于 [Vue3](https://vuejs.org/) + [Github API](https://docs.github.com/cn/rest/reference/repos#contents) 实现的个人图床


[前往在线地址](https://upload.png.cool/)
</div> 

## 简介

一个基于 GitHub API & jsDelivr 开发的具有 CDN 加速功能的图床管理工具
> https://upload.png.cool/

## 优化
- 新增，CDN选择
- 新增，html标签
- 优化，fancybox升级到5.0
- 修复，favicon图标找不到
- 优化，左上图标居中（强迫症）
- 优化，图片名字改成16位hash


## 特性

- 使用 Vue 3 + Typescript + Vite 开发。
- 安全且快速，数据只存在本地。
- 支持**点击、拖拽、复制粘贴**图片上传。
- 一键复制**jsdelivr CDN**加速链接。
- 复制转换 Markdown 格式。
- 谷歌 [squoosh](https://squoosh.app/) 压缩图片。
- [Fancybox](https://fancyapps.com/) 的加持，让图片的预览效果更好。
- ···

## CDN配置
```
cdn.jsdelivr.net
gcore.jsdelivr.net
fastly.jsdelivr.net
originfastly.jsdelivr.net
quantil.jsdelivr.net

https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径
```

## 安装

```
# 安装依赖
npm i
# 运行开发环境
npm run dev
# 编译代码
npm run build
```