# 派单转化器

旅游/客运调度管理系统

## 功能

- 文本导入
- Excel导入
- 图片OCR识别（需要网络支持）
- 自动计算时间备注
- 数据持久化
- Excel导出

## 部署说明

本项目使用 GitHub Pages 部署。

### 部署到 GitHub Pages

1. 将所有文件推送到 GitHub 仓库
2. 进入仓库 Settings → Pages
3. Source 选择 "Deploy from a branch"，选择 `main` 分支和 `/ (root)` 目录
4. 保存后等待几分钟即可访问

### 自定义域名

如需使用自定义域名（如 zhipai.zhimai-ai.cn）：

1. 在 DNS 设置中添加 CNAME 记录指向 `Alex179545447.github.io`
2. 在仓库根目录添加 CNAME 文件（已包含）
3. 在 GitHub Pages 设置中填写自定义域名

## 技术栈

- HTML5 + Tailwind CSS
- Vanilla JavaScript
- XLSX.js (Excel处理)
- Tesseract.js (本地OCR)
