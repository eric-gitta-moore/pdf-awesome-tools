# pdf-awesome-tools

## for user

- [PDF 补丁丁](https://github.com/wmjordan/PDFPatcher)
    - view pdf content structure
- [Abbyy Fine Reader](https://github.com/james-curtis/abbyy-fine-reader-crack) (Win, Mac) 【[下载](https://nsaneforums.com/topic/442672-abbyy-finereader-pdf-16-v160147295/)】
    - ocr
    - edit
- Adobe Acrobat (Win, Mac)
    - remove metadata
    - encrypt
    - edit
    - print production
    - view / edit pdf content structure
    - batch compress pdf
- 金山 pdf 独立版 / wps (Win, Mac)
    - recommend for reading only
    - pdf 转 word 还得是这个
- [exiftool](https://exiftool.org/) (Cli, Win, Mac)
    - [jExifToolGUI](https://github.com/hvdwolf/jExifToolGUI)
    - view metadata
- [PDF Guru](https://github.com/kevin2li/PDF-Guru) (Win, Mac, Linux)
    - remove pdf's password
    - compress batched
    - Anki card
    - 添加(支持多行)/**删除**水印
    - 加签名，支持手写
- [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF) (.jar, All Platform)
  - compress pdf
  - 删除 pdf 签名
  - 加签名
  - 添加水印 (支持多行)
- [PDF24](https://tools.pdf24.org/zh/creator)
    - remove pdf's password
    - [batch compress pdf](https://creator.pdf24.org/manual/11/#:~:text=pdf24%2DDocTool.exe%20%2Dcompress)（~~无法压缩大文件；似乎无法压缩纯图 pdf~~，看命令行日志是使用 Ghostscript 实现的）
    - 大量 word 转 pdf
    - extract pdf images
- [Dataku](https://dataku.ai)
    - extract PDF page
- [FileLocator Pro](https://www.52pojie.cn/thread-1386712-1-1.html)
    - full text search
- [avif cli](https://github.com/lovell/avif-cli)

## for dev
- [pdftk cli](https://www.pdflabs.com/docs/pdftk-cli-examples/)
  - decompress pdf
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


 ## recommend reading
 - https://stackoverflow.com/questions/69973586/print-all-objects-inside-a-pdf-file-with-python
 - https://stackoverflow.com/questions/22675690/if-identifying-text-structure-in-pdf-documents-is-so-difficult-how-do-pdf-reade
 - https://github.com/pymupdf/PyMuPDF/issues/698#issue-726924547

## others awesome
 - https://github.com/py-pdf/awesome-pdf
 - https://github.com/abhi18av/awesome-pdf
