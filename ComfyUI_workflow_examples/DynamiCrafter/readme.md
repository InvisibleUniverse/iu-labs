# DynamiCrafter Workflow

## Overview

This repository provides an open-source ComfyUI workflow for using DynamiCrafter, a tool for animating open-domain images using video diffusion priors. The workflow is designed to help other open-source users understand how to implement and use DynamiCrafter for various video generation tasks.

## About DynamiCrafter

DynamiCrafter leverages pre-trained video diffusion priors to animate still images based on text prompts. It supports high-resolution video generation, frame interpolation, and looping video creation. The tool is developed by researchers from CUHK and Tencent AI Lab.

## Features

- **Image-to-Video Generation**: Animate still images using text prompts.
- **Generative Frame Interpolation**: Generate intermediate frames between two images.
- **Looping Video Generation**: Create seamless looping videos.

## 🤝 Community Support

ComfyUI and pruned models (bf16): [ComfyUI-DynamiCrafterWrapper](https://github.com/kijai/ComfyUI-DynamiCrafterWrapper) (Thanks to [kijai](https://twitter.com/kijaidesign))

|Model|Resolution|GPU Mem. |Checkpoint|
|:---------|:---------|:--------|:--------|
|DynamiCrafter1024|576x1024|10GB |[Hugging Face](https://huggingface.co/Kijai/DynamiCrafter_pruned/blob/main/dynamicrafter_1024_v1_bf16.safetensors)|
|DynamiCrafter512_interp|320x512|8GB |[Hugging Face](https://huggingface.co/Kijai/DynamiCrafter_pruned/blob/main/dynamicrafter_512_interp_v1_bf16.safetensors)|

