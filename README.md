# Amazon Bedrock and Stability.ai Stable Diffusion XL 1.0 Video Animation Demo

In this 3-part demonstration we will learn how to use the AWS SDK for Python (Boto3) to create Generative AI images and simple video animations using [Amazon Bedrock](https://aws.amazon.com/bedrock/) and [Stability.ai](https://stability.ai/stable-image) Stable Diffusion XL 1.0 model.

## Demonstration

1. Text-to-image
2. Image-to-image
3. Video-to-video (video-frame-frame-video)

All instructions for this project can be found in the [Jupyter Notebook](./bedrock_image_generation_demo.ipynb).

## Technologies

- **Amazon Bedrock**: Amazon Bedrock is a fully managed service that offers a choice of high-performing foundation models (FMs) from leading AI companies like AI21 Labs, Anthropic, Cohere, Meta, Mistral AI, Stability AI, and Amazon via a single API
- **Stable Diffusion XL Model**: Stable Diffusion XL or SDXL is the latest image generation model that is tailored towards more photorealistic outputs with more detailed imagery and composition compared to previous SD models, including SD 2.1. Stable Diffusion XL is a significant advancement in image generation capabilities, offering enhanced image composition and face generation that results in stunning visuals and realistic aesthetics.

## References

- [Amazon Bedrock SDXL 1.0 Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/model-parameters-diffusion-1-0-image-image.html)
- [Stability.ai API Documentation](https://platform.stability.ai/docs/api-reference#tag/v1generation/operation/imageToImage)

## State-of-the-Art Generative AI Animation

This demonstration is very basic. If you are interested in state-of-the-art Generative AI video techniques, I would suggest looking at a combination of the AnimateDiff, ControlNet, A1111 or ComfyUI, and a custom fine-tuned SDXL model. Most high-quality animations are created with fine-tuned SDXL LoRAs (Low-Rank Adaptation of Large Language Models). These tools can all be used on AWS using a GPU-based [Amazon WorkSpaces](https://aws.amazon.com/pm/workspaces/) environment.

- [Automatic1111 (aka A1111) Stable Diffusion web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- [ComfyUI Stable Diffusion web UI](https://github.com/comfyanonymous/ComfyUI)
- [AnimateDiff](https://animatediff.github.io/)
- [ControlNet](https://github.com/lllyasviel/ControlNet)
- [AnimateDiff for Stable Diffusion WebU (A1111)](https://github.com/continue-revolution/sd-webui-animatediff)
- [ControlNet for Stable Diffusion WebUI (A1111)](https://github.com/Mikubill/sd-webui-controlnet)
- [Fine-tuned Stable Diffusion XL LoRAs](https://civitai.com/models)
- [Hugging Face: LoRA the Explorer](https://huggingface.co/spaces/multimodalart/LoraTheExplorer)

If you are looking for examples of state-of-the-art Generative AI-based animations, check out [Civitai](https://civitai.com/videos). << \***\* WARNING! HIGHLY INAPPROPRIATE CONTENT! \*\***
