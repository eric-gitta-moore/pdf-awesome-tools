# pdf-awesome-tools

workflow1: 下载图书 PDF > 裁剪出血框 (Optional) > [MRC](https://en.wikipedia.org/wiki/Mixed_raster_content) > 成品

workflow2: 长图散件 png > 文件排序 > 创建 PDF > 切割 A4 > 统一 PDF 画布 > workflow1

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
- PDF Expert (Mac)
  - 阅读、标注好用，渲染速度快
  - 支持搜索结果列表，方便搜索
- 金山 pdf 独立版 / wps (Win, Mac)
    - recommend for reading only
    - pdf 转 word 还得是这个
    - 长图分割切 A4
- [exiftool](https://exiftool.org/) (Cli, Win, Mac)
    - [jExifToolGUI](https://github.com/hvdwolf/jExifToolGUI)
    - view metadata
- [PDF Guru](https://github.com/kevin2li/PDF-Guru) (Win, Mac, Linux)
    - remove pdf's password
    - 压缩 pdf (垃圾还不如 Acrobat)
    - Anki card
    - 添加(支持多行)/**删除**水印
    - 加签名，支持手写
- [Stirling-PDF](https://github.com/Frooodle/Stirling-PDF) (.jar, All Platform)
  - ~~compress pdf~~
  - 删除 pdf 签名
  - 加签名
  - 添加水印 (支持多行)
- [PDF24](https://tools.pdf24.org/zh/creator)
    - remove pdf's password
    - [batch compress pdf](https://creator.pdf24.org/manual/11/#:~:text=pdf24%2DDocTool.exe%20%2Dcompress)（~~无法压缩大文件；似乎无法压缩纯图 pdf~~，看命令行日志是使用 Ghostscript 实现的）
    - 大量 word 转 pdf
    - extract pdf images
- PDFgear
- [PDF Squeezer](https://github.com/eric-gitta-moore/PDF-Squeezer) (Mac)
  - Mac 下压缩神器，比 Acrobat 好用，主要是配置方便，但是有点慢
  - 支持压缩前后比对
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

## 常用动作
### 水平/垂直切割
- WPS 切割，需要手动计算切割长度，没找到比较好的办法
- Acrobat 用别人的 print production - preflight 脚本好像可以
- Windows 可以虚拟打印机分割
- 福昕PDF编辑器
- PDF Guru，太长图片会下标溢出
- pdfToolbox Desktop，大杀器，Mac 好像无

### MRC
- ABBYY
- PDFgear，文件太大没法压

### 统一缩放 A4
- Acrobat 印前检查 > preflight > Acrobat DC 2015 profiles > scale page to a4
- 直接虚拟打印机打成 A4，mac 可以用 preview 打开然后再打印，横向纵向没法强制
- wps 统一纸张大小，会造成重复内容

 ## recommend reading
 - https://stackoverflow.com/questions/69973586/print-all-objects-inside-a-pdf-file-with-python
 - https://stackoverflow.com/questions/22675690/if-identifying-text-structure-in-pdf-documents-is-so-difficult-how-do-pdf-reade
 - https://github.com/pymupdf/PyMuPDF/issues/698#issue-726924547

## others awesome
 - https://github.com/py-pdf/awesome-pdf
 - https://github.com/abhi18av/awesome-pdf
