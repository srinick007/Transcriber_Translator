# Transcriber_Translator

Transcriber_Translator is a project that uses OpenAI's whisper model for audio transcription and Facebook's No Language Left Behind model for language identification and translation. This project is built with Python and provides a user-friendly interface for audio transcription and translation.

Features
Audio transcription using OpenAI's whisper model
Language identification using Facebook's No Language Left Behind model
Translation into 96 different languages
User-friendly interface built with Gradio
Support for audio recording

Installation
To use Transcriber_Translator, you will need Python 3.9 as some dependencies are not supported in later versions. To install the required dependencies, you can use pip:

pip install -r requirements.txt

You will also need to install whisper and also download lid218e.bin and keep it the same directory as the notebook

!pip install git+https://github.com/openai/whisper.git 

!wget https://dl.fbaipublicfiles.com/nllb/lid/lid218e.bin

you can see the languages codes for NLLB here https://github.com/facebookresearch/flores/blob/main/flores200/README.md#languages-in-flores-200

and https://github.com/openai/whisper/blob/main/whisper/tokenizer.py for the languages supported by whisper

to run the gradio interface you just need the run the gradio cell

![image](https://user-images.githubusercontent.com/97779349/227277903-c0ec446c-b07b-4771-8776-0f798c5169e8.png)
