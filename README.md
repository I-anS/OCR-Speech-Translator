# OCR-Speech-Translator

## Objective
This tool was created with the goal of surpassing the language barrier among people of different nationalities for a more seamless, limitless travel experience.

## Description
After uploading an image of the text the user wants to translate, this tool will first identify the characters on the image, and the language it is written in. After which, the user can specify the language the text is to be translated into.
<br>
Two output formats are available:
1. Modified image with bounding boxes with the corresponding translation.
2. Audio output in the translated language.

## Future Extensions
1. Real-time image capture and translation
2. Object recognition to serve as a visual impairment aid
3. Increased input filetype support (Audio, PDF)
4. Personalisation of speech components (Speaking volume, speed)

## References

### Optical Character Recognition
#### Key References
- https://nanonets.com/blog/ocr-with-tesseract/
- https://pyimagesearch.com/2021/09/20/language-translation-and-ocr-with-tesseract-and-python/
- https://www.geeksforgeeks.org/python-opencv-cv2-cvtcolor-method/
- https://docs.opencv.org/4.x/d7/d4d/tutorial_py_thresholding.html
- https://www.folkstalk.com/2022/10/display-cv2-image-in-jupyter-notebook-with-code-examples.html
- https://www.folkstalk.com/2022/10/matplotlib-pyplot-imshow-size-with-code-examples.html
#### Supplemental Readings
- https://builtin.com/data-science/python-ocr
- https://towardsdatascience.com/extract-text-written-in-different-languages-from-images-with-python-2348ff021fe5
- https://towardsdatascience.com/4-python-libraries-to-detect-english-and-non-english-language-c82ad3efd430
- https://www.analyticsvidhya.com/blog/2021/06/optical-character-recognitionocr-with-tesseract-opencv-and-python/
- https://medium.com/analytics-vidhya/scene-text-detection-recognition-and-translation-ad20c31e869e

### Translating the identified Text
#### Main References
- https://github.com/tesseract-ocr/tessdata/
- https://ocrmypdf.readthedocs.io/en/latest/languages.html
- https://towardsdatascience.com/language-translation-using-python-bd8020772ccc (For Translation)
- https://towardsdatascience.com/4-nlp-libraries-for-automatic-language-identification-of-text-data-in-python-cbc6bf664774 (For Language Detection)
- https://cloud.google.com/translate/docs/languages
- https://www.geeksforgeeks.org/convert-text-speech-python/
- https://detectlanguage.com/documentation
#### Supplementary Readings
- https://github.com/Mimino666/langdetect/issues/51
- https://polyglot.readthedocs.io/en/latest/Detection.html
- https://polyglot.readthedocs.io/en/latest/Installation.html
- https://www.thepythoncode.com/article/translate-text-in-python
- https://www.youtube.com/watch?v=1QwT2_-WEBQ
