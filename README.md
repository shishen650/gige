# MC 骨骼动画图鉴 (MC Animation & Skeleton Atlas)

从**最新版基岩版**官方 bedrock-samples 与 **Java版** 客户端反编译源码中提取的全部实体动画、骨骼与 Molang 变量。

## 特点

- 单文件静态网站，零依赖，打开即用
- 开头介绍骨骼系统（骨骼层级、父/子骨骼、变换属性）
- 每个实体展示: 几何骨骼 → 动画（含驱动骨骼与完整变换关键帧 + 中文作用描述）→ 动画控制器
- 数据**不做任何去重**，保留原始出现顺序

## 数据统计

- 基岩版实体: 180
- 动画条目(不去重): 442
- 骨骼出现次数: 1995
- 变量出现次数: 2772
- Java 模型类: 140 / Java 动画方法: 73

## 目录结构

- `网页/index.html` — 图鉴网站主文件（单文件，内嵌数据）
- `.github/workflows/部署图鉴网站.yml` — GitHub Actions 自动部署工作流

## 在线访问

https://shishen650.github.io/gige/

推送到 `gugedonghua` 分支后会自动触发 Actions 构建并部署。