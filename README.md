# 图片识别文字

## 安装相关库

* 安装 python 相关库
```bash
# 图像库
pip3 install pillow

# 可以使用python调用tesseract库
pip3 install pytesseract
```

### Tesseract

Tesseract是一个开源的OCR引擎，能识别100多种语。Optical Character Recognition，光学字符识别，是图片文字识别的官方学术名称。

* 安装

```
brew install tesseract
```

* 下载语言包

将文件 [chi_sim.traineddata](https://github.com/tesseract-ocr/tessdata/blob/master/chi_sim.traineddata) 拷贝到到：```/usr/local/Cellar/tesseract/{{version}}/share/tessdata``` 目录下




