# ivcsl 模板

这是一个支持中文的 Beamer/Metropolis 模板，已内置重庆大学圆形校徽与实验室组合 logo，以及 Metropolis 主题文件。

## 编译方式

```bash
xelatex ivcsl_template.tex
```

## 文件说明

- `ivcsl_template.tex`: 主模板文件。
- `ivcsl_template.pdf`: 当前模板预览。
- `images/logo_cqu_alphanull.png`: 首页右上角使用的蓝色重庆大学圆形校徽、分割线与实验室组合 logo。
- `images/logo_cqu_alphanull_white.png`: 正文页顶部深色栏使用的白色重庆大学圆形校徽、分割线与实验室组合 logo。
- `images/logo.png` / `images/logo_white.png`: 原始重庆大学横版 logo。
- `theme/`: 已内置的 Metropolis/mtheme 主题文件。
- `build/`: 编译产生的辅助文件，可忽略。

使用这份文件夹时，不需要单独下载 `matze/mtheme` 或 `beamertheme-metropolis`。目标电脑仍需要可用的 XeLaTeX 中文环境，例如 MacTeX/TeX Live 中的 `ctexbeamer`、`beamer`、`fontspec`、`xeCJK` 等基础包。
