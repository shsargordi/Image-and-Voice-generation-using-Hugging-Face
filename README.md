# Image and Voice Generation using Hugging Face

This project is a Google Colab notebook for testing image and voice generation using Hugging Face models.

The notebook demonstrates:

* Image generation with **SDXL Turbo**
* Image generation with **Stable Diffusion XL**
* Image refinement with **Stable Diffusion XL Refiner**
* Voice generation / text-to-speech with **Microsoft SpeechT5**
* Optional image generation with **FLUX.1-schnell** on a stronger GPU such as A100

## Hugging Face Setup

To use the models, create a free account on [Hugging Face](https://huggingface.co).

Then create an access token:

1. Go to your Hugging Face profile
2. Open **Settings**
3. Go to **Access Tokens**
4. Click **Create new token**
5. Choose **WRITE** permission
6. Copy the token

Example:

![Hugging Face Access Token Page](HuggingFace.png)

In Google Colab, save the token in **Secrets** using the same name used in the notebook, for example:

```text
HF-token
```
![Click on Secrets in Google Colab](ColabSecretspng) 

Never write your Hugging Face token directly inside the notebook or upload it to GitHub.
