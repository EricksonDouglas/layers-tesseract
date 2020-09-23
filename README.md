# layers-tesseract

AWS Lambda

```
mkdir -p layers/tesseract/tessdata
wget https://github.com/EricksonDouglas/layers-tesseract/archive/master.zip
unzip -o master.zip && rm -rf master.zip
mv layers-tesseract-master/tesseract layers/tesseract
unzip -o layers-tesseract-master/lib.zip -d layers/tesseract && rm -rf layers-tesseract-master
wget https://github.com/tesseract-ocr/tessdata/raw/master/por.traineddata
mv por.traineddata layers/tesseract/tessdata
```
