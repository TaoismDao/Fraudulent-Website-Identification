# Fraudulent-Website-Identification

诈骗网站/平台群组索引列表，支持关键词搜索过滤。

## 诈骗平台索引列表

- 虚假短信平台 https://www.textboostsms.com/
- 骗子短信群组 https://t.me/TextBoostSMSNet



## 本地预览

直接双击 `index.html` 或用浏览器打开即可预览。

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
