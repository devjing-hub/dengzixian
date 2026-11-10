# 反应力觉醒 ⚡

一个以「增强反应力」为主题的个人网站，作者：**邓子贤**。

## 页面清单（共 9 页）

| 文件 | 说明 |
|---|---|
| `index.html` | 主页，含所有分页链接 |
| `story.html` | 初三熬夜经历自述 |
| `reaction-test.html` | 变色反应测试小游戏（3 次取平均） |
| `balloon.html` | 30 秒打气球小游戏（FPS 反应力挑战） |
| `sleep-analyzer.html` | 输入作息 → 即时分析 + 生成 DeepSeek 提示词 |
| `sleep-tips.html` | 早睡好处 / 晚睡坏处 |
| `science.html` | 熬夜影响反应力的科学原理 |
| `training.html` | 提升反应力的训练方法 |
| `about.html` | 作者介绍、制作说明、发布方法、免责声明 |

## 目录结构

```
reaction-website/
├── index.html
├── story.html
├── reaction-test.html
├── balloon.html
├── sleep-analyzer.html
├── sleep-tips.html
├── science.html
├── training.html
├── about.html
├── css/
│   └── style.css
└── images/
    ├── hero.svg  brain.svg  clock.svg  moon.svg  eye.svg  balloon.svg
    └── README.md
```

## 技术特点

- 纯 HTML + CSS + JavaScript，**无外部依赖**，离线也能运行。
- 所有链接和图片都使用**相对路径**，方便整体迁移和部署。
- 图片为原创 SVG 插画，符合「图文并茂、不抄袭」的要求。

## 如何本地预览

直接双击 `index.html` 用浏览器打开即可。

## 发布到 GitHub Pages

1. 在 GitHub 注册账号，新建一个仓库（如 `reaction-website`）。
2. 把整个 `reaction-website` 文件夹里的内容上传到仓库（`index.html` 必须在仓库根目录）。
3. 进入仓库 **Settings → Pages**，把 **Source** 设为 `main` 分支（或 `master`），保存。
4. 稍等一会儿，得到主页地址：`https://你的用户名.github.io/reaction-website/`。
5. 把该地址提交给老师。

> 因为全站都用相对路径，放在仓库根目录或任意子目录都能正常跳转。

## 关于「作息分析」页的 DeepSeek 接入

网页版 DeepSeek 没有可直接嵌入静态页面的免费接口，因此该页采用「生成提示词 → 复制 → 粘贴到 chat.deepseek.com」的方式，完全免费、无需 API Key。页面本身也内置了一份即时的本地分析。
