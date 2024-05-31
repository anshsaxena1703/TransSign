# TransSign
This project demonstrates a machine learning model that automates the detection and translation of text on English signboards into German. The workflow leverages EasyOCR for Optical Character Recognition (OCR) to detect and extract text from images, uses the Hugging Face Transformers library for translation, and displays the OCR results using OpenCV. This comprehensive approach ensures accurate text recognition, seamless translation, and visual presentation of the results.

### Optical Character Recognition with EasyOCR
OCR, or Optical Character Recognition, is a technology that enables the recognition and extraction of text from various formats, such as images, PDFs, or tables. By leveraging OCR, one can easily digitize printed or handwritten text, making it available for further processing, natural language processing (NLP), or integration into workflows.

### Why EasyOCR?
EasyOCR is a powerful OCR tool that works seamlessly with Python. It is known for its high accuracy without the need for extensive fine-tuning. This allows for quick and efficient text extraction, enabling developers to focus more on subsequent processing and application development.

## The Process
### 1. Text Detection with EasyOCR
The first step in our pipeline involves detecting and extracting text from images of English signboards. Using EasyOCR, we can accurately recognize the text present in these images.
### 2. Translation with Hugging Face Transformers
Once the text is extracted, the next step is to translate it from English to German. For this, we use the 'transformers' library from Hugging Face, which provides pre-trained models for various NLP tasks, including translation. The pipeline API from Hugging Face makes this process straightforward.
### 3. Displaying Results with OpenCV
To visually display the OCR results, we use OpenCV. This step involves overlaying the translated text onto the original image.


## Integration and Workflow
- Loading the image of the signboard.
- Extracting the text from the image using EasyOCR.
- Translating the text from English to German using the Hugging Face Transformers pipeline.
- Overlaying the translated text onto the original image using OpenCV.
- Displaying the image with the translated text.

## Results 

<p align="center">
  <img src="https://github.com/anshsaxena1703/TransSign/assets/92105954/2bf53d92-f95a-40d6-953f-0c16fee58509" alt="Example Image 1" width="300" style="margin-right: 20px;">
  <img src="https://github.com/anshsaxena1703/TransSign/assets/92105954/53afc8c8-b4ae-4b88-a1fb-abe7f21ae88d" alt="Example Image 2" width="300">
  <br>
  <img src="https://github.com/anshsaxena1703/TransSign/assets/92105954/ac9704a2-9213-4cd6-bcc9-2fa2ce917a99" alt="Example Image 3" width="300">
</p>


<p align="center">
  <img src="https://github.com/anshsaxena1703/TransSign/assets/92105954/10ec650c-2d88-41d3-bbf6-2989bf78b11f" alt="Example Image 1" width="300" style="margin-right: 20px;">
  <img src="https://github.com/anshsaxena1703/TransSign/assets/92105954/4edb4c02-61f6-4223-818a-3efa02852813" alt="Example Image 2" width="300">
  <br>
  <img src="https://github.com/anshsaxena1703/TransSign/assets/92105954/9d14f94e-bfe4-4593-81b2-fde308d8375e" alt="Example Image 3" width="300">
</p>

## Conclusion
By leveraging the strengths of EasyOCR, Hugging Face Transformers, and OpenCV, this project offers an efficient and accurate solution for detecting and translating text on English signboards into German, while visually presenting the results. EasyOCR’s ease of use and accuracy allow quick text extraction, Hugging Face’s powerful translation capabilities ensure accurate translations, and OpenCV enables effective visualization. This combination significantly enhances the process of text extraction, translation, and presentation, making it applicable in various multilingual and OCR-based applications.
