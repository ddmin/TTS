Reading PDF with OCR

# Creating Text Files from PDF Using Tesseract
1. `pdftoppm -png TITLE.pdf TITLE`
2. `convert -rotate "90" in.jpg out.jpg` 
3. `for i in TITLE-??.png; do tesseract "$i" "text-$i" -l eng; done;`
4. `cat text-TITLE* > TITLE.txt`