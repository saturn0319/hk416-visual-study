# GitHub 仓库发布指南

## 仓库信息

**Repository name**

```text
hk416-visual-study
```

**中文展示名称**

```text
HK416 三维造型作品展示
```

**About / Description**

```text
HK416 主题个人三维造型作品展示，记录外观建模练习与视觉呈现。
```

**英文备选**

```text
A personal HK416-themed 3D visual study focused on exterior form and presentation.
```

**Topics**

```text
3d-art, portfolio, hard-surface, visual-study
```

项目对应仓库：[saturn0319/hk416-visual-study](https://github.com/saturn0319/hk416-visual-study)。

## 本地布局

主说明文件位于 `HK416` 根目录；补充文档位于 `docs/`；反馈模板位于 `.github/ISSUE_TEMPLATE/`。

不再使用嵌套的 `hk416-visual-study/` 展示文件夹。旧的 `docs/PUBLISHING.md` 已统一为 `docs/GITHUB_SETUP.md`。

## 发布文件

当前展示文档清单如下：

```text
README.md
LICENSE.md
NOTICE.md
CONTRIBUTING.md
.gitignore
.gitattributes
docs/PROJECT_NOTES.md
docs/GITHUB_SETUP.md
.github/ISSUE_TEMPLATE/visual-feedback.yml
```

现有 Git 规则只允许展示文档、反馈模板和指定的外观静态图片。通过网页上传时，也应按上述清单选择文件，保持 README 位于仓库根目录。

## 外观图片

当前尚未提供作品图片。补充不含尺寸标注、剖面、内部结构或功能细节的外观图片后，统一放到 `docs/images/`。

| 用途 | 建议路径 |
| --- | --- |
| 整体外观 | `docs/images/overview.png` |
| 左侧外观 | `docs/images/left-view.png` |
| 右侧外观 | `docs/images/right-view.png` |
| 表面材质细节 | `docs/images/surface-detail.png` |

上述路径只是后续命名建议，当前没有对应图片。

## 更新已有仓库

1. 将本地展示文档的改动提交到现有仓库，保持相同目录结构。
2. 用新的 `docs/GITHUB_SETUP.md` 替换旧的 `docs/PUBLISHING.md`。
3. 确认隐藏文件及 `.github/` 目录一并提交。
4. 检查 README 的本地链接与图片显示，再按需更新 About 和 Topics。

本地文件移动不会自动同步 GitHub；线上内容以实际提交的版本为准。
