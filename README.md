# pdf-awesome-tools

## 用户

- [PDF 补丁丁](https://github.com/wmjordan/PDFPatcher)
    - 查看文档结构
- [Abbyy Fine Reader](https://github.com/james-curtis/abbyy-fine-reader-crack) 【[下载](https://nsaneforums.com/topic/442672-abbyy-finereader-pdf-16-v160147295/)】
    - ocr
    - 编辑
- [Adobe Acrobat]()
    - 删除 metadata
    - 加密
    - 编辑
    - 打印预检
    - 查看/编辑 pdf 内容结构
    - 批量压缩 pdf
- 金山 pdf 独立版
    - 只推荐用来阅读 pdf
- [exiftool](https://exiftool.org/)
    - 查看 metadata
- [PDF Guru](https://github.com/kevin2li/PDF-Guru/releases/tag/v1.0.12)
    - 解密 pdf
- [PDF24](https://tools.pdf24.org/zh/creator)
    - 解密 pdf
    - [批量压缩 pdf](https://creator.pdf24.org/manual/11/#:~:text=pdf24%2DDocTool.exe%20%2Dcompress)（无法压缩大文件；似乎无法压缩纯图 pdf）
    - 大量 word 转 pdf
- [Dataku](https://dataku.ai)
    - PDF抽取工具
- [FileLocator Pro](https://www.52pojie.cn/thread-1386712-1-1.html)
    - 全文检索
- [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF)

## 开发
- [pdftk cli](https://www.pdflabs.com/docs/pdftk-cli-examples/)
  - 解压 pdf
- [PyPDF2](https://pypdf2.readthedocs.io/en/3.0.0/dev/pdf-format.html)
- PyMuPDF
  - [删除 object](https://github.com/pymupdf/PyMuPDF/discussions/1855)
  - [压缩 pdf](https://github.com/pymupdf/PyMuPDF/discussions/2107)
  - [使用 redact 删除文本](https://stackoverflow.com/a/73234495)
    - pymupdf 作者说法 https://github.com/pymupdf/PyMuPDF/discussions/1019
    - https://blog.csdn.net/hbh112233abc/article/details/128201653
  - [替换 stream 大法](https://stackoverflow.com/a/73851388)
- [QPDF](https://stackoverflow.com/a/6562443)
  - [解压 pdf](https://qpdf.readthedocs.io/en/stable/cli.html#option-qdf)：`qpdf --qdf --object-streams=disable original.pdf unpacked.pdf`
- 提取元素
  - pdfplumber
  - pdfminer.six
- [Ghostscript 压缩 pdf](https://github.com/deimo/pdf-compress)
- [添加平铺水印](https://xie.infoq.cn/article/e3752245b7952d51ab98fd416)
  - [reportlab使用自定义字体](https://blog.csdn.net/plutus_sutulp/article/details/7708992)


 ## 推荐阅读
 - https://stackoverflow.com/questions/69973586/print-all-objects-inside-a-pdf-file-with-python
 - https://stackoverflow.com/questions/22675690/if-identifying-text-structure-in-pdf-documents-is-so-difficult-how-do-pdf-reade
 - https://github.com/pymupdf/PyMuPDF/issues/698#issue-726924547
