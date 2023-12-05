# remove pdf metadata SOP

1. 任何文件都要转成纯图片pdf
2. 用 Acrobat 对文件消毒（redact）
3. exiftool 再次清理 metadata 检查是否彻底（如果彻底会提示 unchanged）
4. 再次使用 pdf 补丁丁检查结构和 metadata 信息
