# Spidey T9 Keyboard

蜘蛛侠九宫格键盘 —— 模拟真人用手机在 Google 搜索 Peter Parker 的交互页面。

## 文件说明

```
index.html       主页面（已改名为 index，GitHub Pages 直接可访问）
fonts/           像素字体（Press Start 2P + VT323），相对路径引用，必须一起上传
```

## 手动上传部署步骤（GitHub Pages）

1. 在 GitHub 新建一个仓库（Public 或 Private 均可），**不要勾选** "Add a README"（避免冲突）
2. 进入仓库 → 点 **Add file → Upload files**
3. 把本目录里的 `index.html` 和 `fonts/` 文件夹一起拖进去
   - 注意：要保留 `fonts/` 这个子文件夹结构，不要只拖里面的字体文件
4. 提交后，进入仓库 **Settings → Pages**
5. 在 "Build and deployment" 下：
   - Source 选 **Deploy from a branch**
   - Branch 选 **main**，文件夹选 **/(root)**
   - 点 **Save**
6. 等 1~2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/` 即可

> 页面已内置移动端适配（全屏沉浸、触摸震动），手机浏览器直接打开即可体验。
> 彩蛋：在搜索框输入 `peter parker` 并搜索。
