
# Eden AI
Enhance your apps and workflows with the power of Eden AI ! Integrate advanced AI features such as natural language processing, image recognition, document parsing, audio processing, generative AI and more.


## Prerequisites
You will need the following to proceed:
* Create your Eden AI account for free: https://app.edenai.run/user/login
* Get your API key from your account
![image](https://github.com/queSaDiLLaSS/try/assets/118369217/b72d6510-6a10-4047-9656-536823f4cba3)


## Create a connection
When you create a conenction to Eden AI, do not forget the keyword Bearer before your API key:
![image](https://github.com/queSaDiLLaSS/try/assets/118369217/7154fbab-0c90-4e7a-9fab-053a2c1b504f)


## Supported Operations
The connector supports the following operations:
[Image Generation](###image-generation)

### Convert Text into Speech
Converts normal language text into speech.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/audio_text_to_speech_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/audio_text_to_speech_create).
* `text`: Enter the text you want to convert into audio.
* `option`: Enter MALE or FEMALE to choose the voice gender.

### Detect Explicit Content in Images
Detects adult explicit content in images, that is generally inappropriate for people under the age of 18 and includes nudity, sexual activity and pornography...
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/image_explicit_content_create).
* `file`: Choose the file you want to analyze.

### Extract Named Entities in Text
Identifies named entities in a text and classifies them into predefined categories.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/text_named_entity_recognition_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/text_named_entity_recognition_create).
* `text`:Tap or paste the text you want to analyze.

### Detect Faces in Images
Identifies human faces in digital images: position, sex, age, smile, glasses, etc.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/image_face_detection_create).
* `file`: Choose the file you want to analyze.

### Image Generation
Generates compelling images based on a given prompt.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/image_generation_create).
* `text`: Tap or paste the text you want to analyze.
* `resolution`: Enter the resolution, it can only be 256x256, 512x512 or 1024x1024.
* `num_images`: Enter the number of images you want.

### Translate Text into another Language
Translates a text into another language using rules, statics or ML technics.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/translation_automatic_translation_create).
* `text`: Tap or paste the text you want to analyze.
* `source_language`: Enter the language of your text. Check languages supported [here](https://docs.edenai.co/reference/translation_automatic_translation_create).
* `target_language`: Enter the language of the output text. Check languages supported [here](https://docs.edenai.co/reference/translation_automatic_translation_create).

### Moderate Text
Moderates a text by detecting explicit content.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/text_moderation_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/text_moderation_create).
* `text`: Tap or paste the text you want to analyze.

### Summarize a Text
Extracts the most important sentences from a text in order to create a smaller version of the text.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/text_summarize_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/text_summarize_create).
* `text`: Tap or paste the text you want to analyze.
* `output_sentences`: Enter the sentence number of the summary.

### Detect Language of Text
Detects language of text.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/translation_language_detection_create).
* `text`: Tap or paste the text you want to analyze.

### Identify General Sentiment of a Text
Identifies general sentiment of a text and returns positive, negative or neutral.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/text_sentiment_analysis_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/text_sentiment_analysis_create).
* `text`: Tap or paste the text you want to analyze.

### Extract Information in Invoices
Extracts information in invoices.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/ocr_invoice_parser_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/ocr_invoice_parser_create).
* `file`: Choose the file you want to analyze.

### Extract Information in Resumes
Extracts information in resumes.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/ocr_resume_parser_create).
* `file`: Choose the file you want to analyze.

### Extract Informations in Identity Documents
Extracts structured information in identity documents (passports, identity cards, driver license, etc.).
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/ocr_identity_parser_create).
* `file`: Choose the file you want to analyze.

### <a name="tith"></a> Extract Information in Receipts
Extracts information in receipts.
* `providers`: Enter the selected providers seperated by a coma. Check the providers available [here](https://docs.edenai.co/reference/ocr_receipt_parser_create).
* `language`: Check languages supported [here](https://docs.edenai.co/reference/ocr_receipt_parser_create).
* `file`: Choose the file you want to analyze.





