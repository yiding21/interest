# 照片存放说明

网站只有两个页面：`index.html`（首页）和每个树种一个 HTML 页（如 `jiulixiang.html`）。
照片放在 `assets/images/<树种名>/` 里，页面里直接用相对路径引用。

## 九里香的照片

```
assets/images/jiulixiang/
├── cover.png               ← 封面（首页大图 + 详情页头图）
├── 01-yuanyang-01.jpg      ← 原样
├── 02-chengpin-01.jpg      ← 成品
├── 03-beibu-01.jpg         ← 背部
└── 04-guocheng-01~03.jpg   ← 制作过程（盆底检查、垫网穿线、铺陶粒）
```

## 加照片 / 加树种

1. **补照片**：把新照片放进对应文件夹，打开该树种的 HTML 页，照着现有 `<figure>` 复制一段、
   改一下文件名和说明文字即可。
2. **加新树种**：在 `assets/images/` 下新建文件夹放照片 → 复制一份 `jiulixiang.html` 改名
   （如 `rongshu.html`）→ 改里面的标题、文字和图片路径 → 打开 `index.html`，
   照着九里香那张卡片复制一段，改链接和文字。
3. 没拍好的照片位置不用删代码：页面会自动显示灰底占位，标注应放的文件名。
