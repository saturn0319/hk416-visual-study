# 展示仓库发布指南

## 推荐名称

```text
hk416-visual-study
```

中文展示名称：**HK416 三维造型作品展示**。

## 仓库简介

可直接用于 GitHub 的 About：

```text
HK416 主题个人三维造型作品展示，记录外观建模练习与视觉呈现。
```

英文备选：

```text
A personal HK416-themed 3D visual study focused on exterior form and presentation.
```

建议 Topics：

```text
3d-art, portfolio, hard-surface, visual-study
```

## 发布内容

将本展示目录作为独立仓库使用。现有忽略规则仅允许说明文档和 `images/` 下的 PNG、JPG、JPEG、WebP 静态图片。

当前缺少作品图片。作为作品集正式展示前，补充不含尺寸标注、剖面、内部结构或功能细节的整体外观图片，并在 README 中添加实际图片链接。不要将空目录或不存在的图片链接写进 README。

图片可以按以下规则命名：

| 用途 | 建议路径 |
| --- | --- |
| 整体外观 | `images/overview.png` |
| 左侧外观 | `images/left-view.png` |
| 右侧外观 | `images/right-view.png` |
| 表面材质细节 | `images/surface-detail.png` |

这些图片当前尚未生成，表格只是后续命名建议。

## 上传步骤

1. 在 GitHub 创建空仓库，填写上方仓库名称与简介。
2. 上传本展示目录中的文件，保持 `README.md` 位于仓库根目录。
3. 确认 `.gitignore`、`.gitattributes` 及 `docs/` 一并上传。
4. 检查 README 链接和图片显示，再添加 Topics。

本目录仅包含展示说明，不包含原始建模文件。
