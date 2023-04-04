<div align="center">
<img src="https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/logo.png" width="200" alt="cantor" align=center />

基于 [Vue3](https://vuejs.org/) + [Github API](https://docs.github.com/cn/rest/reference/repos#contents) 实现的个人图床


[前往在线地址](https://pichub.tngeek.com/)
</div>
<img src="https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/posi.webp"  />   

[![HitCount](https://hits.dwyl.com/lewkamtao/PicHub.svg?style=flat-square)](http://hits.dwyl.com/lewkamtao/PicHub)

## 简介

一个基于 GitHub API & jsDelivr 开发的具有 CDN 加速功能的图床管理工具
> https://pichub.tngeek.com/

## 优化
```
1.fancybox升级到5.0
2.favicon图标找不到
3.左上图标居中（强迫症）
4.图片名字改成24位hash
5.新增CDN选择
6.新增html标签
```

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
gcore.jsdelivr.net

fastly.jsdelivr.net

originfastly.jsdelivr.net

quantil.jsdelivr.net

https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名@发布的版本号/文件路径

https://cdn.jsdelivr.net/gh/xiezhr/mycdn/source/bgimg/back-rain.png       ## 获取最新资源
https://cdn.jsdelivr.net/gh/xiezhr/mycdn@1.0/source/bgimg/back-rain.png   ## 获取1.0版本的资源


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

## 截图
![如果打不开，就是被墙了](https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/微信图片_20220330111032_jnf4ou_.jpg)
![如果打不开，就是被墙了](https://raw.githubusercontent.com/lewkamtao/PicHub-Cloud/master/PicHub/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_202203301110324_6e6ahv_.jpg)
![如果打不开，就是被墙了](https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/微信图片_202203301110323_dhnlh2_.jpg)
![如果打不开，就是被墙了](https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/微信图片_202203301110324_6e6ahv_.jpg)
![如果打不开，就是被墙了](https://cdn.jsdelivr.net/gh/lewkamtao/PicHub-Cloud@master/PicHub/微信图片_20220330111045_yj3dhp_.jpg)

## 反馈

安装和使用过程中，如果遇到问题，请提 [Issue](https://github.com/lewkamtao/PicHub/issues) 。

## 贡献

欢迎小伙伴以各种形式的贡献，界面、功能、改进、修复 Bug 等。
