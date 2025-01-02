# ****** Natural Language Generation Tasks (x2Text) ******

### 1. Image2Text i.e. Image Captioning
- Think of Text2Text task eg Machine Translation and now instead of conditioning it on text we condition it on Image

### 2. Audio2Text / Speech2Text eg audio transcription (also called Speech Recognition or Automatic Speech Recognition (ASR) System)
- Think of Text2Text task eg Machine Translation and now instead of conditioning it on text we condition it on Audio

### 3. Video2Text i.e. Video Captioning
- Think of Text2Text task eg Machine Translation and now instead of conditioning it on text we condition it on Video

# ****** Text2X Tasks ******

### 1. Text2Image (TTI) Task
- Think of Image2Image Task and then condition it on Text.
- Now we have seen Image2Image task [here](https://levelup.gitconnected.com/image-data-augmentation-techniques-d9323f22153f) and we saw all the generative models to do this i.e. Autoencoders / GAN / DDPMs / DDIMs but here during inference you won't have a input image you will only have an input text hence while training you will have to use a model which convert noise to image for the image2image task and hence we can only use models like GANs and Diffusion for Text2Image Task !!
- Inpainting
- Outpainting

### 2. Text2Speech Task (also called Speech Synthesis)
- Think of Speech2Speech Task and then condition it on texts, same as logic explained above we can here also only use models like GANs and Diffusion
- [AudioGen by Facebook](https://arxiv.org/pdf/2209.15352.pdf)
- [MusicGen by Facebook](https://arxiv.org/pdf/2306.05284.pdf)
- [MusicGen Playground on HuggingFace](https://huggingface.co/spaces/facebook/MusicGen)
  
### 3. Text2Video Task
- Think of Video2Video Task and then condition it on texts, same as logic explained above we can here also only use models like GANs and Diffusion
