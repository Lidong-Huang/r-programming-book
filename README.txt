使用说明（本地 HTML 电子书）

1) 把你的 lecture2.Rmd ... lecture16.Rmd 复制到本文件夹（与 _quarto.yml 同级）
2) 在 RStudio 里运行：
   source("convert_lectures_to_quarto.R")
   这会生成 lecture2.qmd ... lecture16.qmd（保留每章标题，去掉独立输出设置）

3) 打开 _quarto.yml，把 chapters 里的 lecture3–lecture16 取消注释并补全顺序
4) 在终端或 RStudio 运行：
   quarto render

5) 打开生成的 _book/index.html
