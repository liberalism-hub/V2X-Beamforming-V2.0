# WCL 稿件下载

点击文件链接后，可在 GitHub 文件页选择 **Download raw file** 下载到电脑。

| 文件 | 内容 | 大小 |
|---|---|---:|
| [wcl_manuscript_complete.zip](wcl_manuscript_complete.zip) | 完整 LaTeX、已编译 PDF、图表、绘图数据、审查说明及独立强基线补充 | 3.19 MB |
| [wcl_latex_source.zip](wcl_latex_source.zip) | 可上传 Overleaf 的源码、正文 PDF 图及绘图数据 | 212 KB |
| [wcl_manuscript.pdf](wcl_manuscript.pdf) | 七页中文修订稿 PDF | 444 KB |

Overleaf 主文件为 `manuscript_revised.tex`，编译器选择 **XeLaTeX**。

## 版本说明

正文为此前 A–C 实验对齐的中文第二至第四节工作稿。完整包的 `latest_mcal_supplement/` 另附后续强校准基线结果，该部分尚未并入正文。本包不应视为已完成强基线更新的投稿定稿。

数据包括重建图表的 CSV、统计摘要与协议，不包含全部蒙特卡洛原始 NPZ 缓存。强基线补充显示，在所测条件中 TC 优于 Bonferroni，但低于 M-Local/M-Global；该结论完整保留。

包内容和上传前副本已完成 CRC 与 SHA256 核验，文件哈希见 [SHA256SUMS](SHA256SUMS)，大小和内容清单见 [package_manifest.json](package_manifest.json)。
