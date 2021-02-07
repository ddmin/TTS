# PDF 2 TTS

<sup>(because I hate reading)</sup>

## New Method
1. Read PDF with pdftotext
2. Split sentences at periods.
3. Feed sentences to gTTS

## Old Method
1. Convert PDF to PNG with pdftoppm
2. (Optional <sup>actually probably entirely obsolete</sup>) Rotate images 90° with imagemagick
3. Convert PNG to TXT with Tesseract OCR
4. Convert TXT to MP3 with gTTS (python)
5. Combine MP3 files with FFMPEG
