# VIRTUAL_TRY_ON

> Anticloud offline package — upstream: minar09/awesome-virtual-try-on @ `master`.

## What This Project Does

A curated list of awesome research papers, projects, code, dataset, workshops etc. related to virtual try-on.

**Topics:** 2d-virtual-try-on, 3d-virtual-try-on, awesome-list, awesome-lists, cloth, collection, curated, curated-list, fashion, fashion-tech, garment, image, image-based, multi-pose, multi-pose-guided, try-on, video, video-virtual-try-on, virtual-try-on, vton

## Upstream README

# A Curated List of Awesome Virtual Try-on (VTON) Research! <img src='awesome.png' width='37'>
A curated list of awesome research papers, projects, code, datasets, workshops, etc. related to virtual try-on (VTON).

- [Prompt-based Virtual Try-on](#Prompt-based-Virtual-Try-on)
- [Image-based (2D) Virtual Try-on](#Image-based-2D-Virtual-Try-on)
- [3D Virtual Try-on](#3D-virtual-try-on)
- [Mix-and-match Virtual Try-On](#Mix-and-match-Virtual-Try-on)
- [In-the-wild Virtual Try-On](#In-the-wild-Virtual-Try-on)
- [Multi-Pose Guided Virtual Try-on](#Multi-Pose-Guided-Virtual-Try-on)
- [Video Virtual Try-on](#Video-Virtual-Try-on)
- [Non-clothing Virtual Try-on](#non-clothing-virtual-try-on)
- [Pose-Guided Human Synthesis](#pose-guided-human-synthesis)
- [Datasets for Virtual Try-on](#Datasets-for-Virtual-Try-on)
- [Safety and Moderation for Virtual Try-on](#Safety-and-Moderation-for-Virtual-Try-on)
- [Related Conference Workshops](#Related-Conference-Workshops)
- [Demos](#Demos)
- [Related Repositories](#Related-Repositories)


## Prompt-based Virtual Try-on
  #### ControlNet
  - [ControlNet](https://github.com/lllyasviel/ControlNet) - Hint: Use the clothing image as the image input and provide the human description in the text prompt or vice versa.
  - [EditAnything](https://github.com/sail-sg/EditAnything) - Hint: Use a reference fashion image as input and provide your desired changes in the text prompt.

  #### Stable-Diffusion
  - [Stable-DreamFusion](https://github.com/ashawkey/stable-dreamfusion) - Hint: Use the Image-conditioned 3D Generation option to edit your fashion images.
  - [ThreeStudio](https://github.com/threestudio-project/threestudio) - Hint: Use different models for generating output from the image-conditioned text prompts for fashion image editing.


## Image-based (2D) Virtual Try-on

  #### CVPR 2026
   - PG-VTON: Single-Pass Training-Free Virtual Try-On via Patch-Guided Reference Alignment - [Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Zhao_PG-VTON_Single-Pass_Training-Free_Virtual_Try-On_via_Patch-Guided_Reference_Alignment_CVPR_2026_paper.html)
   - Mobile-VTON: High-Fidelity On-Device Virtual Try-On - [Project/Paper](https://zhenchenwan.github.io/Mobile-VTON/)
   - MOFA-VTON: More Fashion Possibilities with Fine-Grained Adaptations in Virtual Try-On - [Paper](https://openaccess.thecvf.com/content/CVPR2026/papers/Han_MOFA-VTON_More_Fashion_Possibilities_with_Fine-Grained_Adaptations_in_Virtual_Try-On_CVPR_2026_paper.pdf)
   - Vanast: Virtual Try-On with Human Image Animation via Synthetic Triplet Supervision - [Project/Paper](https://hyunsoocha.github.io/vanast/)
   - Garments2Look: A Multi-Reference Dataset for High-Fidelity Outfit-Level Virtual Try-On with Clothing and Accessories - [Project](https://artmesciencelab.github.io/Garments2Look/)

  #### ECCV 2026
  - Layering Virtual Try-On - [Paper](https://doi.org/10.1007/978-3-032-37255-0_21)
  - Dress-ED: Instruction-Guided Editing for Virtual Try-On and Try-Of

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
