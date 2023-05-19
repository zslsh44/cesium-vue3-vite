<!--
 * @Description:
 * @Author: 笙痞77
 * @Date: 2023-01-10 17:02:14
 * @LastEditors: 笙痞77
 * @LastEditTime: 2023-05-17 09:32:43
-->

# Vue 3 + Vite

项目基于 vue3 + vite + cesium，已实现常见三维动画场景，欢迎有兴趣的同学加入共建，一起搞开源，一起学习，一起乐呵呵~~

## 项目启动

```
npm i
npm run dev
```

## 功能（已完成）
- 粒子效果
  - [x] 下雨
  - [x] 下雪
  - [x] 雾天
  - [x] 火焰
- POI点位
  - [x] 基础打点
  - [x] 聚合
  - [x] primitive底层打点（性能佳）
  - [x] primitive聚合（性能佳）
  - [x] 点位动态弹窗
- 第三方服务加载
  - [x] xyz瓦片
  - [x] 3D Tiles
- 材质
  - [x] 道路闪烁
  - [x] 道路流光效果
  - [x] 辐射圈
  - [x] 圆扩散
  - [x] 四色图
  - [x] 流动的水面
  - [x] 天空盒
- 几何
  - [x] 量测
  - [x] 点线面绘制
  - [x] 态势图、箭头
- 场景
  - [x] 水淹模拟
  - [x] 热力图
  - [x] 时间轴
  - [x] 遮罩反选（边界）
- 分析
  - [x] 天际线分析
  - [x] 高程(限高)分析
## TODO

### 计划（需求收集中...）
- [ ] 三维动画网格热图
- [ ] 等高线分析
- [ ] 填挖方

### 优化

- [ ] 量测工具性能卡顿
- [x] 火焰粒子效果不太好看（虽然已经优化过一版，但是感觉还是差点意思，如有更好效果欢迎交流）
- [x] 基于 primitive 实现点聚合效果
- [x] 3dtiles 加载缓慢，尝试使用异步方法优化
