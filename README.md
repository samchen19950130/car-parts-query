# 汽车配件查询系统

静态版汽车配件适配查询工具，部署在 GitHub Pages。

## 隐私提醒

GitHub Pages 发布的是静态文件。仓库里的 `index.html`、`data.json` 以及任何随站点发布的 CSV/JSON 文件，都应按公开数据处理；不要把未公开的采购价、供应商、真实销量、客户信息等敏感数据放进仓库。

导入功能写入的是当前浏览器的 `localStorage`，不会自动上传到 GitHub。若要让所有访问者都看到新数据，需要更新仓库里的 `data.json`。

## 数据字段

默认数据使用：

- `brand`
- `model`
- `yearStart`
- `yearEnd`
- `partName`
- `partNumber`
- `notes`
