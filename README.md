I am creating this with LLama 3.1, Whisper, and MeloTTS. all of this model from hugging face.

Our program roadmap will look like this :

1. Generative AI generates sentences that the user must read, on this article I use Llama 3.1.
2. The user records while reading the generated sentences, and sends them to the speech-to-text model. In this article, I use whisper from openAI.
3. Output from whisper will be sent to Llama 3.1 for getting feedback.
4. The feedback will be read by the text-to-speech model, in this article, I use the MeloTTS model.

for an explanation step-by-step of this code, please read it on my medium at : https://medium.com/@ravionaldoraffel/learn-english-pronunciation-with-the-help-of-llama-whisper-and-melotts-on-google-colab-85a364347f37
