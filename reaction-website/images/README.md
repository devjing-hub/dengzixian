# images 目录说明

这里存放网站的图片，全部使用**相对路径**引用。

## 已有插画（原创 SVG）
- `hero.svg` —— 主页横幅插画
- `brain.svg` —— 大脑
- `clock.svg` —— 时钟
- `moon.svg` —— 月亮
- `eye.svg` —— 眼睛
- `balloon.svg` —— 气球

## 如何加入你自己的图片
1. 把你自己的照片/图片放进这个 `images/` 目录，例如 `images/me.jpg`。
2. 在对应的 HTML 页面里，把占位处的 `<img>` 改成你自己的图片，例如：

```html
<img src="images/me.jpg" alt="我的照片">
```

3. 建议在 `story.html` 的「熬夜的开始」和「转折与改变」两个区块放上你的个人照片（当前是 `moon.svg`、`clock.svg` 占位，替换成 `images/me.jpg` 即可）。

> 注意：保持相对路径，不要写 `C:\...` 或 `file:///...` 这样的绝对路径，否则发布到 GitHub Pages 后会找不到图片。
