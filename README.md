# Hi, I'm Yury 👋

### Applied AI & Computer Vision Engineer

I develop computer-vision systems and the supporting tools needed to take them from an experiment to a reliable workflow. My interests include image processing, dataset preparation, segmentation, synthetic-data generation, and reproducible model inference.

The repositories highlighted below grew out of a larger computer-vision project. I needed a practical way to prepare and expand its datasets, so I built several reusable utilities around segmentation, compositing, and controlled image generation. I published them separately because I thought they might be useful to other engineers facing similar problems.

## Featured projects

### [Image Harmonization Pipeline](https://github.com/georgesmirnoff1348/sdxl_glue)

A reusable pipeline for creating coherent training images from foreground objects and new scene backgrounds. It combines segmentation, compositing, inpainting, and structural guidance to reduce visible seams and domain mismatch.

- Foreground extraction with BiRefNet
- Configurable compositing and inpainting-mask strategies
- Automatic CUDA, MPS, and CPU selection
- Reproducible run metadata and model-free regression tests

### [Synthetic Dataset Generation Pipeline](https://github.com/georgesmirnoff1348/synthetic-dataset-toolkit)

A set of modular tools originally built to create and manage synthetic datasets for a computer-vision project.

- Unified interfaces for segmentation, generation, and guided inpainting
- Background replacement and dataset augmentation workflows
- Explicit VRAM/RAM lifecycle management
- Indexed dataset-file management and reproducible seeds

## Toolbox

`Python` · `PyTorch` · `OpenCV` · `ONNX Runtime` · `Pillow` · `Diffusers` · `SDXL` · `ControlNet` · `uv` · `Git`

## What I'm interested in

- Computer-vision engineering and applied machine learning
- Dataset design, preparation, and augmentation
- Image segmentation, processing, and analysis
- Reliable and reproducible inference pipelines

## Contact

I'm open to remote opportunities and collaborations.

- [LinkedIn](https://www.linkedin.com/in/yury-smirnoff-17787a423/)
- [Telegram: @georgesmirnoff1348](https://t.me/georgesmirnoff1348)
