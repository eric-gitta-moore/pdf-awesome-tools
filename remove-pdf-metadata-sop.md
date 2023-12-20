# remove pdf metadata SOP

1. 任何文件都要转成纯图片pdf
2. 用 Acrobat 对文件消毒（redact）
3. exiftool 再次清理 metadata 检查是否彻底（如果彻底会提示 unchanged）
4. 再次使用 pdf 补丁丁 或者 Acrobat 检查结构和 metadata 信息
5. （可选操作）对 redact 后的 pdf 尝试恢复 metadata 信息
    - [restore pdf metadata](https://exiftool.org/forum/index.php?topic=11493.0)
      - [qpdf 永久删除 metadata youtube](https://youtu.be/SGpxN8sRvMA?si=YH2a8idQO7IWby8o)
      - [ExifTool remove old metadata permanently `qpdf --linearize in.pdf out.pdf`](https://exiftool.org/TagNames/PDF.html)
      - [其他程序删除的 metadata 怎么恢复](https://exiftool.org/forum/index.php?topic=12132.msg65557#msg65557)
    - [How to prevent recovering metadata when using ExifTool?](https://superuser.com/questions/1482619/how-to-prevent-recovering-metadata-when-using-exiftool)
      - 重新线性化估计是无解，exiftool 默认是增量更新的，重新线性化之后就合并抹除了之前的
