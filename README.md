# my-lesson · 课程精讲讲义

三门课的课堂笔记，逐页提炼课件、补齐推导、统一排版。每章都是**单文件 HTML**：样式、目录、图片全内嵌，可离线阅读、可直接打印。

在线浏览：<https://ka0j1ovo.github.io/my-lesson/>

## 课程

| 课程 | 章节 | 目录 |
|---|---|---|
| 信号与系统 | 第 1–2 章 | [`signals-systems/`](signals-systems/) |
| 半导体器件物理 | 第 1–4 章 | [`semiconductor-physics/`](semiconductor-physics/) |
| 数字集成电路设计 | 第 3–7、10–12 章 | [`digital-ic/`](digital-ic/) |

## 目录结构

```
index.html                    首页（三门课）
├─ signals-systems/index.html       课程目录 → 第 1、2 章
├─ semiconductor-physics/index.html 课程目录 → 第 1–4 章
└─ digital-ic/index.html            课程目录 → 第 3–7、10–12 章
```

导航三层：**首页 → 课程章节目录 → 笔记**。每页笔记左上角有「← 课程名」回到课程目录。

## 阅读工具

每个笔记页右下角（回到顶部按钮上方）：

- **🔍 搜索**：`Ctrl+F` 或点按钮，输入关键字自动跳转并高亮，回车/“下一项”逐个跳，显示 `n / 总数`。
- **✏️ 标注**：选“高亮”后拖动（手机长按）选中文字即变黄；选“擦除”后选中已标注文字即可清除；标注存于浏览器本地，支持**一键导出/导入 JSON**（换设备、换版本可自动重定位）。

## 本地查看

直接双击 `index.html`；或起一个静态服务器模拟线上环境：

```bash
python -m http.server 8000
# 打开 http://localhost:8000/
```

## 说明

- 仓库只放整理后的 HTML 讲义，原始 PPT/PDF 与 Word 源文件不在仓库内。
- 内容依据课堂课件整理，如与课堂讲述不一致，以任课教师要求为准。
