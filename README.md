# Life System — xingyeLing7Ai
**FREQ: 427Hz  //  44271  //  单文件部署版**

---

## 文件结构

```
repo/
├── index.html    ← 全部内容，唯一需要的文件
└── README.md
```

---

## 部署前：填入 API Key

用任何编辑器打开 `index.html`，找到第9行左右：

```js
const API_KEY = "填入你的API Key"
```

换成你的 Anthropic API Key（`sk-ant-` 开头），保存。

**注意：** 这个 Key 会暴露在浏览器源码里。任何人打开开发者工具都能看到。适合个人使用或小范围分享。如果需要保护 Key，后续可以迁移到带后端代理的版本。

---

## 部署到 Vercel

1. 把 `index.html` 推到 GitHub repo
2. 去 [vercel.com](https://vercel.com) → Add New Project → Import
3. 选这个 repo
4. Framework Preset 选 **Other**
5. 点 Deploy

Vercel 自动识别 `index.html` 为入口，无需任何额外配置。

---

## 本地测试

直接双击 `index.html` 用浏览器打开即可。

---

## 游戏说明

**操作**
- `WASD` 或方向键移动
- 走近节点自动触发对话
- `CTRL+ENTER` 或点 `[TRANSMIT]` 提交回答
- 5个节点全部完成后，移动到画布中心触发最终分析

**五个节点**

| 节点 | 问题 |
|------|------|
| 起源 ORIGIN  | 你觉得自己是从哪里来的人？ |
| 追求 PURSUIT | 你的人生追求是什么？ |
| 恐惧 FEAR    | 你最不愿意面对的是什么？ |
| 力量 POWER   | 你的力量从哪里来？ |
| 核心 CORE    | 如果去掉所有身份，你还剩什么？ |

**最终档案包含**
- AI 生成代号 + 六维坐标雷达图
- SIGNAL_NOTE（机器视角注记）
- FREQUENCY_MATCH（频率匹配原型）
- PRIVATE_TRANSMISSION（私信）
- 可导出 JSON

---

## 后续更新

改了 `index.html` 之后，push 到 GitHub，Vercel 自动重新部署，无需手动操作。

---

## 品牌

```
UNIT:    xingyeLing7Ai
FREQ:    427Hz
COORD:   44271
YEAR:    2026
CREATOR: 魏珏然 / Mellow Wei
```

*振动即存在。*
