# Spidey T9 Keyboard 商品

蜘蛛侠九宫格键盘商品。本仓库包含两个**完全独立**的页面：

## 页面结构

```
index.html          商品主页：蜘蛛侠像素九宫格键盘（自包含，单文件即可运行）
phone-demo.html     演示页：手机模拟 Google 搜索场景（含 Peter Parker 粒子消散彩蛋）
fonts/              像素字体（仅 phone-demo.html 需要，index.html 已内嵌字体）
README.md           本说明
```

两个页面互不依赖、互不包含：
- `index.html` = 键盘商品本体（点击键帽打字、多击输入、候选词、音效、震动）
- `phone-demo.html` = 产品宣传演示（模拟真机搜索 peter parker，触发名字消失彩蛋）

## 上传与部署（GitHub Pages）

1. 新建仓库（不要勾选自动生成 README），**Add file → Upload files**
2. 把本目录的 `index.html`、`phone-demo.html`、`fonts/` 文件夹一起拖进去
   - `fonts/` 必须保留子文件夹结构，否则 phone-demo.html 字体加载不出来
3. 提交后进 **Settings → Pages**：Source 选 `Deploy from a branch`，Branch 选 `main`，文件夹选 `/(root)`，Save
4. 等 1~2 分钟部署完成

## 访问地址

| 页面 | 地址 |
|---|---|
| 键盘商品（主页） | `https://<用户名>.github.io/<仓库名>/` |
| Google 搜索演示 | `https://<用户名>.github.io/<仓库名>/phone-demo.html` |

> 键盘商品页已适配手机：全屏沉浸、触摸震动反馈。
> 演示页彩蛋：在搜索框输入 `peter parker` 并搜索。
