# 周易占卜工具

一个基于周易的占卜工具，包含六爻、梅花易数、奇门遁甲三种占卜方式。

## ✨ 功能特点

- **六爻占卜** - 传统周易六爻预测
- **梅花易数** - 时间、数字、方位起卦
- **奇门遁甲** - 奇门排盘分析
- **AI解读** - 智能解读卦象（支持OpenAI兼容接口）
- **历史记录** - 保存占卜历史

## 🎨 视觉特效

- 星空闪烁 - 50颗随机闪烁的星星
- 萤火虫 - 15只自由飞舞的发光虫
- 魔法粉尘 - 30颗缓缓上升的金色粉尘
- 流星 - 划过天空的流星
- 水波纹 - 扩散的水波效果
- 太极图 - 缓慢旋转的背景装饰（首页）

## 📱 使用方法

1. 下载所有文件
2. 直接用浏览器打开 `index.html` 即可使用
3. 无需服务器，纯前端实现

## 📁 文件结构

```
├── index.html          # 首页
├── liuyao.html         # 六爻占卜
├── meihua.html         # 梅花易数
├── qimen.html          # 奇门遁甲
├── docs/               # 文档
│   ├── README.md
│   ├── SUMMARY.md
│   ├── FIX_SUMMARY.md
│   └── changelog.txt
└── prompts/            # AI提示词
    ├── ai_prompt.txt
    └── liuyao_prompt.txt
```

## ⚙️ AI解读配置

在设置中配置API信息：

| 配置项 | 说明 | 示例 |
|--------|------|------|
| API地址 | OpenAI兼容接口 | `https://api.openai.com/v1` |
| API Key | 你的API密钥 | `sk-xxx...` |
| 模型名称 | AI模型 | `gpt-4o` |

## 🛠️ 技术栈

- HTML5
- CSS3
- JavaScript (原生)
- Canvas 动画

## 🌐 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## 📄 许可证

MIT License
