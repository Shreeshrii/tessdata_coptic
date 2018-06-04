# tessdata_coptic
## Traineddata files for Tesseract 4.0.0 for Coptic OCR

These traineddata files were created in response to a request in [tesseract-ocr forum](https://groups.google.com/forum/?utm_medium=email&utm_source=footer#!msg/tesseract-ocr/LXIxi4KxmNQ/unoOhL9yAAAJ)

* These are 'float' models similar to files in tessdata_best and can be used to `continue from` for further training.

* They can be converted to `integer` models similar to files in tessdata_fast to speed up the recognition. 

## Fonts used for training

  'Antinoou' \
  'FreeSerif' \
  'FreeSerifAthanasius' \
  'FreeSerifAvvaShenouda' \
  'FreeSerifCopt' \
  'FreeSerifPishoi' \
  'IFAO-Grec Unicode' \
  'Symbola Semi-Condensed' \
  
  ## [Image used for testing with v1 cop.traineddata](https://imgur.com/a/ILRw6vm)
  
  ![coptic](https://user-images.githubusercontent.com/5095331/40931402-926f5702-6848-11e8-8a7c-413213b090db.png)
  
  ## Recognized text with v1 cop.traineddata

```
ⲁⲩⲱ ⲟⲛ ⲁⲓ̈ⲧⲣⲉⲩ ⲣ̄ ⲥⲟⲟⲩ ⲛ̄ ⲉⲃⲟⲧ ⲉⲩⲕⲏⲧ ⲉ ϩⲃⲟⲩⲣ
ⲉⲩⲉⲓⲣⲉ ⲛ̄ ⲛⲉ ϩⲃⲏⲩⲉ ⲛ̄ ⲛⲉⲩⲁⲡⲟⲧⲉⲗⲉⲥⲙⲁ ⲙⲛ̄ ⲛⲉⲩ–
ⲥⲭⲕⲁⲙⲁ ⲧⲏⲣⲟⲩ· ϫⲉ ⲕⲁⲥ ϩⲛ̄ ⲟⲩ ϩⲃⲁ ⲉⲩⲉⲣ̄ ϩⲃⲁ·
ⲁⲩⲱ ϩⲛ̄ ⲟⲩ ⲡⲗⲁⲛⲏ ⲉⲩⲉⲡⲗⲁⲛⲁ ⲛ̄ϭⲓ ⲛ ⲁⲣⲭⲱ̄ ⲉⲧ
ϣⲟⲟⲡ ϩⲛ̄ ⲛ ⲁⲓⲱ̄ ⲁⲩⲱ ϩⲛ̄ ⲛⲉⲩⲥⲫⲁⲓⲣⲁ ⲁⲩⲱ ϩⲛ̄ 5
ⲛⲉⲩⲙ̄ⲡⲏⲩⲉ· ⲁⲩⲱ ϩⲛ̄ ⲛⲉⲩⲧⲟⲡⲟⲥ ⲧⲏⲣⲟⲩ· ϫⲉ ⲕⲁⲥ ⲛ̄
ⲛⲉⲩⲛⲟⲓ̈ ⲛ̄ ⲧⲉⲩϭⲓⲛⲙⲟⲟϣⲉ ⲙ̄ⲙⲙⲓ ⲙ̅ⲙⲟ‐
ⲅ ⲟⲩ; ⲁⲥϣⲱⲡⲉ ϭⲉ ⲛ̄ⲧⲉⲣⲉ ⲓ̄ⲥ̄ ⲟⲩⲱ ⲉϥϫⲱ ⲛ̄
ⲡⲉⲓ̈ ϣⲁϫⲉ ⲉⲣⲉ ⲫⲓⲗⲓⲡⲡⲟⲥ ϩⲙⲟⲟⲥ ⲉϥⲥϩⲁⲓ̈ ⲛ̄ ϣⲁϫⲉ
ⲗϫ. ⲁ. ⲛⲓⲙ ⲉⲧ ⲉⲣⲉ ⲓ̄ⲥ̄ ϫⲱ ⲙ̄ⲙⲟⲟⲩ; ⲁⲥϣⲱⲡⲉ ϭⲉ ⲙⲛ̄ⲛⲥⲁ 10
```

 ## Image used for testing with v2 cop.traineddata
 
 ![sophia_0154](https://user-images.githubusercontent.com/5095331/40931444-bc57275c-6848-11e8-8f48-b036698ceac7.png)
 
   ## Recognized text with v2 cop.traineddata (--oem 1 --psm 6)

```   
   135
ⲥⲟⲫⲓⲁ· ⲁⲩⲱ ⲛ̄ⲧⲉⲣⲉⲥⲧⲟⲣⲡⲟⲩ ⲛ̄ ⲧⲟⲟⲧⲟⲩ ⲛ̄ ⲛⲉ ⲡⲣⲟ–
ⲃⲟⲗⲟⲟⲩⲉ ⲙ̅ ⲡⲁⲩⲑⲁⲧⲏⲥ. ⲁⲥⲛⲟϫⲟⲩ ⲉ ϩⲟⲩⲛ ⲉ ⲧⲡⲓⲥ–
ⲧⲓⲥ ⲥⲟⲫⲓⲁ· ⲁⲩⲱ ⲁⲥⲕⲟⲧⲥ̅ ⲁⲥⲉⲓ̅ ⲉⲃⲟⲗ ϩⲙ̅ ⲡⲉ ⲭⲁⲟⲥ·
ⲁⲥⲉⲓ̅ ⲉ ϩⲣⲁⲓ̈ ⲉ ϫⲱⲕ· ⲉⲧⲉ ⲛ̅ⲧⲟⲕ ⲡⲉ ⲡⲉⲣⲡⲉ ⲡⲁⲓ̈
5 ⲡⲉ ⲡⲃⲱⲗ ⲛ̅ ⲛ̄ ϣⲁϫⲉ ⲧⲏⲣⲟⲩ ⲛⲁⲓ̈ ⲛ̅ⲧ ⲁⲥϫⲟⲟⲩ ⲛ̄ϭⲓ
ⲧⲉⲏϭⲟⲙ ⲛ̄ ⲟⲩⲟⲉⲓⲛ ϩⲓⲧⲛ̅ ⲧⲱⲇⲏ ⲛ̄ ⲥⲟⲗⲟⲙⲱⲛ· ⲁⲥ–
ϣⲱⲡⲉ ϭⲉ ⲛ̄ⲧⲉⲣⲉ ⲡⲓ ϣⲟⲣⲡ̅ ⲙ̅ ⲙⲩⲥⲧⲏⲣⲓⲟⲛ ⲥⲱⲧⲙ̅
ⲉ ⲛⲉⲓ̈ ϣⲁϫⲉ ⲉϥϫⲱ ⲙ̅ⲙⲟⲟⲩ ⲛ̄ϭⲓ ⲡⲉⲧⲣⲟⲥ ⲡⲉϫⲁϥ
ⲛⲁϥ· ϫⲉ ⲉⲩⲥⲉ ⲡⲙⲁⲕⲁⲣⲓⲟⲥ ⲡⲉⲧⲣⲉ ⲡⲁⲓ̈ ⲡⲉ ⲃⲱⲗ
ⲟ ⲛ̅ ⲛ̅ ϣⲁϫⲉ ⲉⲛⲧ ⲁⲩϫⲟⲟⲩ· ⲁϥⲟⲩⲱϩ ⲁⲉ ⲟⲛ ⲉ ⲧⲟ–
ⲟⲧϥ̅ ϩⲙ̅ ⲡϣⲁϫⲉ ⲛ̄ϭⲓ ⲡⲓ ϣⲟⲣⲡ̅ ⲙ̅ ⲙⲩⲥⲧⲏⲣⲓⲟⲛ ⲡⲉ–
ϫⲁϥ ϫⲉ ⲁⲥϣⲱⲡⲉ ϭⲉ ⲉⲙⲡⲁⲩ̀ ⲛ̅ ⲧⲡⲓⲥⲧⲓⲥ ⲥⲟⲫⲓⲁ
ⲉ ϩⲣⲁⲓ̈ ϩⲙ̅ ⲡⲉ ⲭⲁⲟⲥ· ⲉⲃⲟⲗ ϫⲉ ⲙ̅ⲡⲁⲧⲟⲩⲕⲉⲗⲉⲩⲉ
ⲛⲁⲓ̈ ϩⲓⲧⲙ̅ ⲡⲁⲓ̈ⲱⲧ· ⲡⲓ ϣⲟⲣⲛ̅ ⲙ̅ ⲙⲩⲥⲧⲏⲣⲓⲟⲛ ⲉⲧ ⲣⲛ̅ⲁ̅. ⲃ.
15 ϭⲱϣⲧ̅ ⲉ ϩⲟⲩⲛ· ⲧⲟⲧⲉ ϭⲉ ⲙⲛ̅ⲛ̅ⲥⲁⲓ̈ ⲛ̅ⲧⲉⲣⲟⲩⲉⲓⲙⲉ ⲛ̅‐
ϭⲓ ⲛⲉ ⲡⲣⲟⲃⲟⲗⲟⲟⲩⲉ ⲙ̅ ⲡⲁⲩⲑⲁⲧⲏⲥ ϫⲉ ⲁ ⲧⲁⲁⲡⲟϩ–
ⲣⲟⲓⲁ ⲛ̅ ⲟⲩⲟⲉⲓⲛ ϥⲓ ⲛ̄ ϭⲟⲙ ⲛ̄ ⲟⲩⲟⲉⲓⲛ ⲛ̅ ϩⲏⲧⲟⲩ ⲛⲁⲓ̈
ⲛ̅ⲧ ⲁⲩϥⲓⲧⲟⲩ ϩⲛ̄ ⲧⲡⲓⲥⲧⲓⲥ ⲥⲟⲫⲓⲁ· ⲁⲩⲱ ⲁⲥⲛⲟϫⲟⲩ
ⲉ ϩⲟⲩⲛ ⲛ̄ϭⲓ ϯ ⲁⲡⲟϩⲣⲟⲓⲁ ⲛ̅ ⲟⲩⲟⲓ̈ⲛ· ⲁⲥⲛⲟϫⲟⲩ ⲉ
ϩ ϩⲟⲩⲛ ⲉ ⲧⲡⲓⲥⲧⲓⲥ ⲥⲟⲫⲓⲁ· ⲁⲩⲱ ⲟⲛ ⲁⲩⲛⲁⲩ ⲉ ⲧⲡⲓⲥ‐
ⲧⲓⲥ ⲥⲟⲫⲓⲁ ⲉⲥⲟ ⲛ̄ ⲟⲩⲟⲓ̈ⲛ ⲡ̅ ⲑⲉ ⲉ ⲛⲉⲥⲟ ⲙ̅ⲙⲟⲥ ϫⲓⲛ
ⲛ̅ ϣⲟⲣⲡ̅ ⲁⲧϭⲱⲛ̅ⲧ̅ ⲉ ⲧⲡⲓⲥⲧⲓⲥ ⲥⲟⲫⲓⲁ· ⲁⲩⲱ ⲟⲛ ⲁⲩ–
ⲱϣ ⲉ ϩⲣⲁⲓ̈ ⲟⲩⲃⲉ ⲡⲉⲩⲁⲩⲑⲁⲧⲏⲥ ⲉ ⲧⲣⲉϥ ⲉⲓ̅ ⲛϥ̅ⲃⲟ–
ⲏⲑⲓ ⲉ ⲣⲟⲟⲩ ⲛ̄ⲥⲉϥⲓ ⲛ̄ ⲛ̅ ϭⲟⲙ ⲉⲧ ϩⲛ̅ ⲧⲥⲟⲫⲓⲁ ⲛ̄ ⲕⲉ
2, ⲥⲟⲡ· ⲁⲩⲱ ⲁ ⲡⲁⲩⲑⲁⲇⲏⲥ ⲧⲛ̅ⲛⲟⲟⲩ ⲉⲃⲟⲗ ϩⲙ̅ ⲡϫⲓⲥⲉ
ϩⲙ̅ ⲡⲙⲉϩ ⲙ̅ⲛ̅ⲧ̅ϣⲟⲙⲧⲉ ⲛ̅ ⲁⲓⲱⲛ ⲁϥⲧⲛ̅ⲛⲟⲟⲩ ⲛ̄ ⲕⲉ
ⲛⲟϭ ⲛ̄ ϭⲟⲙ ⲛ̄ ⲟⲩⲟⲉⲓⲛ ⲁⲥⲉⲓ̅ ⲉ ⲡⲉⲥⲏⲧ ⲉ ⲡⲉ ⲭⲁⲟⲥ
15. ⲙⲛ̅ⲛ̅ⲥⲁ. ⲓⲥ ⲡ Ⲙ̅ⲃ. ⲣⲓⲟ ⲙⲛ̅ⲛ̅ⲥⲁ ⲇⲁ.

 ```
