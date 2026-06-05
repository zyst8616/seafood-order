# 海产订单管理

幼儿园食品订货+进销存管理系统，纯前端单页面应用，手机端优先。

**在线地址**：<https://zyst8616.github.io/seafood-order/>

## 功能

| 模块 | 说明 |
|------|------|
| 订货单 | 选择产品下单，生成图片（微信分享）或 Excel |
| 进销存 | 按月份/学校统计进货额、出货额、收益，导出 Excel |
| 幼儿园 | 管理客户信息（名称、园长、电话、地址） |
| 产品 | 管理海产品/冷冻品（名称、规格、单位、进价、售价） |
| 订单记录 | 查看/删除历史订单 |

## 技术

- **前端**：单文件 HTML + CSS + JS
- **存储**：localStorage
- **Excel**：[SheetJS](https://cdn.sheetjs.com/) CDN
- **截图**：[html2canvas](https://html2canvas.hertzen.com/) CDN
- **部署**：GitHub Pages

## 维护

```bash
# 源文件路径
D:/seafood-order/standalone.html

# 部署副本
D:/seafood-order-pages/index.html

# 更新并推送
cp D:/seafood-order/standalone.html D:/seafood-order-pages/index.html
cd D:/seafood-order-pages
git add -A && git commit -m "描述你的改动" && git push
```

所有业务逻辑在 `standalone.html` 中，`index.html` 是其同步副本。
