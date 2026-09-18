# Yiming Zhao — Research CV

English and Chinese academic CVs adapted from the supplied Research CV Template.

中英文科研简历，内容对应，使用 XeLaTeX 编译。

| Version / 版本 | LaTeX source / 源码 | PDF |
| --- | --- | --- |
| English | [main.tex](main.tex) | [Yiming_Zhao_CV_EN.pdf](Yiming_Zhao_CV_EN.pdf) |
| 中文 | [main_zh.tex](main_zh.tex) | [赵一鸣_CV_CN.pdf](赵一鸣_CV_CN.pdf) |

- **Compiler:** XeLaTeX (TeX Live, including TeX Gyre and Fandol fonts)

## Build

```sh
latexmk -xelatex -jobname=Yiming_Zhao_CV_EN main.tex
latexmk -xelatex -jobname=赵一鸣_CV_CN main_zh.tex
```

Or run `xelatex -interaction=nonstopmode -halt-on-error` twice with the desired `.tex` file.

## Overleaf

Upload the project ZIP to Overleaf, choose **XeLaTeX**, and set `main.tex` (English) or `main_zh.tex` (中文) as the main document. The source is self-contained and uses fonts included in TeX Live.

中文版本保留论文的英文原题、作者顺序与通讯作者标记；两版的日期、数值和投稿状态保持一致。

## Content

Content is adapted from Yiming Zhao's resume dated September 16, 2026. Author order, corresponding-author markers, source entry dates, and accepted/submitted distinctions are preserved. Venue rankings and impact factors are omitted. The LightVLN research entry was updated on September 18, 2026 from the latest author-provided manuscript, including model size, benchmark results, and hardware-in-the-loop inference rates. Other quantitative results and publication statuses reflect the supplied resume; these claims have not been independently revalidated.

The public CV includes professional email and GitHub contact details; personal telephone, birth date, and WeChat ID are omitted. Empty template sections are removed. The source template and original resume are not redistributed in this repository.
