# Fraudulent-Website-Identification

诈骗网站/平台群组索引列表，支持关键词搜索过滤。

## 功能

- 📋 诈骗网站、平台、群组索引展示
- 🔍 关键词实时搜索过滤（支持多词）
- 📱 响应式布局，适配移动端
- 🌙 深色主题，护眼易读

## 本地预览

直接双击 `index.html` 或用浏览器打开即可预览。

或使用本地服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js (需安装 npx)
npx serve .
```

访问 http://localhost:8000

## 部署到 GitHub Pages

1. 将仓库推送到 GitHub
2. 进入仓库 **Settings** → **Pages**
3. **Source** 选择 `Deploy from a branch`
4. **Branch** 选择 `main`，目录选择 `/ (root)`
5. 保存后等待部署完成

页面将发布在：`https://<你的用户名>.github.io/Fraudulent-Website-Identification/`

## 添加数据

在 `index.html` 中找到 `FRAUD_DATA` 数组，按以下格式添加条目：

```javascript
{
  name: "诈骗名称",
  url: "https://example.com",
  type: "website",  // website | platform | group
  desc: "诈骗描述"
}
```

## 注意事项

- 数据仅供参考，请勿轻信任何可疑链接
- 建议定期更新维护数据
