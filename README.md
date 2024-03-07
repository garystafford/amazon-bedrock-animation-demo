# Amazon Bedrock and Stability.ai Stable Diffusion XL 1.0 Video Animation Demo

In this 3-part demonstration we will learn how to use the AWS SDK for Python (Boto3) to create Generative AI images and simple video animations using [Amazon Bedrock](https://aws.amazon.com/bedrock/) and [Stability.ai](https://stability.ai/stable-image) Stable Diffusion XL 1.0 model.

## Demonstration

1. Text-to-image
2. Image-to-image
3. Video-to-video (video-frame-frame-video)

All instructions for this project can be found in the [Jupyter Notebook](./bedrock_image_generation_demo.ipynb) and on the accompanying [YouTube video](https://youtu.be/94irLcJA9eA?si=po_xj-EHkbl_lfD2).

[![Video](./diagram/title-slide.png)](https://youtu.be/94irLcJA9eA?si=wgScZAdAJc3JTFZb "Generative AI Video Animations with Amazon Bedrock and Stable Diffusion XL")

## Technologies

- **Amazon Bedrock**: Amazon Bedrock is a fully managed service that offers a choice of high-performing foundation models (FMs) from leading AI companies like AI21 Labs, Anthropic, Cohere, Meta, Mistral AI, Stability AI, and Amazon via a single API
- **Stable Diffusion XL Model**: Stable Diffusion XL or SDXL is the latest image generation model that is tailored towards more photorealistic outputs with more detailed imagery and composition compared to previous SD models, including SD 2.1. Stable Diffusion XL is a significant advancement in image generation capabilities, offering enhanced image composition and face generation that results in stunning visuals and realistic aesthetics.

## References

- [Amazon Bedrock SDXL 1.0 Documentation](https://docs.aws.amazon.com/bedrock/latest/userguide/model-parameters-diffusion-1-0-image-image.html)
- [Stability.ai API Documentation](https://platform.stability.ai/docs/api-reference#tag/v1generation/operation/imageToImage)

## Sample Generated Images, Frames, and Videos

- [Sample generated text-to-image images](./content/generated_images/text_to_image_samples/)
- [Sample generated image-to-image images](./content/generated_images/image_to_image_samples/)
- [Sample generated video frames](./content/generated_frames/generated_frame_samples/)
- [Sample generated animated GIFs](./content/generated_videos/animated_gif_samples/)

### Part 1: Text-to-Images Samples

<table border="0px solid #FFFFFFF" cellspacing="10" cellpadding="10">
    <tr>
        <td>
            <img src="./content/generated_images/text_to_image_samples/phoenix_3.png" alt="Text-to-Image" width="256"/>
        </td>
        <td>
            <img src="./content/generated_images/text_to_image_samples/samuri.jpg" alt="Text-to-Image" width="256"/>
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_images/text_to_image_samples/batman_pixar.jpg" alt="Text-to-Image" width="256"/>
        </td>
        <td>
            <img src="./content/generated_images/text_to_image_samples/dragon.jpg" alt="Text-to-Image" width="256"/>
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_images/text_to_image_samples/girl_autumn_2.jpg" alt="Text-to-Image" width="256"/>
        </td>
        <td>
            <img src="./content/generated_images/text_to_image_samples/cat_fish.jpg" alt="Text-to-Image" width="256"/>
        </td>
    </tr>
</table>

### Part 2: Image-to-Images Samples

<table border="0px solid #FFFFFFF" cellspacing="10" cellpadding="10">
    <tr>
        <td>
            <img src="./content/source_images/image_samples/bird_cropped.jpg" alt="Image-to-Image" width="256"/><br/>Original Image
        </td>
        <td>
            <img src="./content/generated_images/image_to_image_samples/image_to_image_02.png" alt="Image-to-Image" width="256"/><br/>Variation #1
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_images/image_to_image_samples/image_to_image_07.png" alt="Image-to-Image" width="256"/><br/>Variation #2
        </td>
        <td>
            <img src="./content/generated_images/image_to_image_samples/image_to_image_05.png" alt="Image-to-Image" width="256"/><br/>Variation #3
        </td>
    </tr>
</table>

### Part 3: Video-to-Video Samples (Animated GIFs)

Original MP4 video files, created with FFPmpeg, converted to scaled down animated GIF files.

<table border="0px solid #FFFFFFF" cellspacing="10" cellpadding="10">
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/selfie_1_v1.gif" alt="Video-to-Image"  width="256"/><br/>Selfie Variation #1
        </td>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/selfie_1_v2.gif" alt="Video-to-Image"  width="256"/><br/>Selfie Variation #2
        </td>
    </tr>
</table>

<table border="0px solid #FFFFFFF" cellspacing="10" cellpadding="10">
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/male_2.gif" alt="Video-to-Image"  width="256"/><br/>Male 2 Variation #1
        </td>
    </tr>
</table>

<table border="0px solid #FFFFFFF" cellspacing="10" cellpadding="10">
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/bejeweled_owl.gif" alt="Video-to-Image"  width="448"/><br/>Owl Variation #1
        </td>
    </tr>
    <!-- <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/female_1_v1.gif" alt="Video-to-Image"  width="448"/><br/>Female 1 Variation #1
        </td>
    </tr> -->
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/female_1_v2.gif" alt="Video-to-Image"  width="448"/><br/>Female 1 Variation #2
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/female_2_v1.gif" alt="Video-to-Image"  width="448"/><br/>Female 2 Variation #1
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/female_2_v2.gif" alt="Video-to-Image"  width="448"/><br/>Female 2 Variation #2
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/male_1.gif" alt="Video-to-Image"  width="448"/><br/>Male 1 Variation #1
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/red_squirrel.gif" alt="Video-to-Image"  width="448"/><br/>Red Squirrel Variation #1
        </td>
    </tr>
    <tr>
        <td>
            <img src="./content/generated_videos/animated_gif_samples/dancer.gif" alt="Video-to-Image"   width="448"/><br/>Dancer Variation #1
        </td>
    </tr>
</table>

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
