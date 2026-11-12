# 玩具架 · toys

随手做的小东西，一个仓库一张卡片。

线上：**https://antidotewxy.github.io/toys/**

## 货架

| 玩具 | 说明 | 地址 |
| --- | --- | --- |
| 掷筊 · 请示 | 两块杯，问一件事。圣杯 / 笑杯 / 阴杯 | [/toys/jiaobei/](https://antidotewxy.github.io/toys/jiaobei/) |
| 祈福灯 | 写一句愿，点一盏灯，灯会带着愿望升起来 | [/toys/qifu/](https://antidotewxy.github.io/toys/qifu/) |
| 求签 | 摇动签筒抽一支签，看签诗与解 | [/toys/qian/](https://antidotewxy.github.io/toys/qian/) |

## 结构

```
toys/
├── index.html            玩具架首页（卡片列表）
├── jiaobei/
│   └── index.html        掷筊本体（单文件，零依赖）
├── qifu/
│   └── index.html        祈福灯（单文件，零依赖）
└── qian/
    └── index.html        求签（单文件，零依赖）
```

新增一个玩具：建 `<名字>/index.html`，再在根目录 `index.html` 里加一张卡片。

## 说明

- 全部是单文件静态页，没有后端、没有外部请求、没有统计埋点。
- 掷筊页的杯迹、祈福灯的灯数只存在访问者自己浏览器的 localStorage 里，不上传；祈福灯不保存愿望文字，只保存灯的位置。
- 托管在 GitHub Pages。

