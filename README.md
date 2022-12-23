---
language:
- en
thumbnail: "https://huggingface.co/wavymulder/portraitplus/resolve/main/imgs/page1.jpg"
license: creativeml-openrail-m
tags:
- stable-diffusion
- stable-diffusion-diffusers
- text-to-image
- safetensors
- diffusers
inference: true
---



**Portrait+**
![Header](https://huggingface.co/wavymulder/portraitplus/resolve/main/imgs/page1.jpg)
[*CKPT DOWNLOAD LINK*](https://huggingface.co/wavymulder/portraitplus/resolve/main/portrait%2B1.0.ckpt) - this is a dreambooth model trained on a diverse set of close to medium range portraits of people. 

Use `portrait+ style` in your prompt (I recommend at the start)

The goal was to create a model with a consistent portrait composition and consistent eyes. See the batch example below for the consistency of the model's eyes. This model can do several styles, so you want to guide it along depending on your goals. Note below in the document that prompting celebrities works a bit differently than prompting generic characters, since real people have a more photoreal presence in the base 1.5 model. Also note that fantasy concepts, like cyberpunk people or wizards, will require more regid prompting for photoreal styles than something common like a person in a park.

Portrait+ works best at a 1:1 aspect ratio, though I've had success with tall aspect ratios as well.

Please see [this document where I share the parameters (prompt, sampler, seed, etc.) used for all example images above.](https://huggingface.co/wavymulder/portraitplus/resolve/main/parameters_for_samples.txt)


![Modification example](https://huggingface.co/wavymulder/portraitplus/resolve/main/imgs/page2.jpg)

![Batch example]( LINK )