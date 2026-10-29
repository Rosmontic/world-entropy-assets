# 世界熵 · 图片资源库

本仓库存放《世界熵》DEMO 的原创矢量卡图。当前 13 张卡图均以抽象符号表达异常意象，采用统一 600 × 380 画布，可直接在网页中缩放。

## 目录

- `cards/`：按卡牌语义命名的 SVG 卡图。
- `manifest.json`：卡牌编号、图片路径、尺寸和类型索引。

## 替换图片

保持 `manifest.json` 中的 `cardId` 与卡牌数据库一致。若改变文件名，请同步修改卡牌数据库的 `art` 字段；若只替换同路径文件，主程序无需修改。

## 授权

首批原创矢量资源以 CC0 发布，可自由修改和替换。后续第三方素材应单独记录来源与授权，不要直接混入本目录而不注明。

## 关联仓库

- 主程序：https://github.com/Rosmontic/world-entropy-demo
- 卡牌数据：https://github.com/Rosmontic/world-entropy-cards
