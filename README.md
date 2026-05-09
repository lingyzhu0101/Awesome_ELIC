# 🚀 Awesome_GLC
Paper list of Generative Learned Compression (GLC). This includes topics such as Generative Image Compression (GIC), Generative Video Compression (GVC), Extreme Learned Image Compression (ELIC), and Extreme Learned Video Compression (ELVC) for human and machine vision perception. ELIC and ELVC, in particular, have emerged from advancements in generative models and could offer new insights into the relationship between generation ability and Shannon’s information theory. We also provide the test conditions for fair comparison.

**Maintained by:** [Lingyu Zhu](https://scholar.google.com/citations?user=IhyTEDkAAAAJ&hl=zh-CN) , [Langxi Huang]() and [Chengyan Jiang]()

**Generative Image Compression Report:** [Chinese version](src/超低码率生成式图像压缩技术报告.pdf) 

**Invited Talk:** [Chinese version](src/GIC_talk.pdf) 

# Overview
<p align="left">
<img src="src/framework.png" width=90% height=80% 
class="center">
</p>

# Notes
- If you find papers relevant to this topic, please share them as a discussion post.
- Some papers may simultaneously belong to multiple subfields, and we categorize them accordingly to reflect these overlaps.
- Looking forward to your kind contributions and discussions! Many thanks!


# Updated on 2026.05.09

This round prioritizes papers from **TPAMI, TMM, TCSVT, IJCV, CVPR, ICCV, ECCV** and closely related high-quality venues.  
For very recent work, we also include **arXiv / project pages** when the official venue version is not yet fully indexed or the code release is only announced there.

<details>
  <summary>Table of Contents</summary>

- [Generative Image Compression](#generative-image-compression)
- [Generative Video Compression](#generative-video-compression)
- [Extreme Learned Image Compression](#extreme-learned-image-compression)
- [Extreme Learned Video Compression](#extreme-learned-video-compression)
- [Dataset for Human Vision Perception](#dataset-for-human-vision-perception)
- [Dataset for Machine Vision Perception](#dataset-for-machine-vision-perception)
- [Test Conditions](#test-conditions)

</details>

> Some works naturally overlap multiple categories, and we intentionally duplicate them for easier lookup.

## Generative Image Compression

|Publish Date|Title|Authors (First Author)|PDF|Code|
|---|---|---|---|---|
|**2026.04**|**CoD-Lite: Real-Time Diffusion-Based Generative Image Compression**|Bin Li et al.|[2604.12525](https://arxiv.org/pdf/2604.12525)|[GitHub](https://github.com/microsoft/GenCodec/tree/main/CoD_Lite)|
|**2026.03**|**DiT-IC: Aligned Diffusion Transformer for Efficient Image Compression**|Junqi Shi et al.|[2603.13162](https://arxiv.org/pdf/2603.13162)|null|
|**2026.03**|**ProGIC: Progressive and Lightweight Generative Image Compression with Residual Vector Quantization**|Hao Cao et al.|[2603.02897](https://arxiv.org/pdf/2603.02897)|null|
|**2026.02**|**One-Step Diffusion for Perceptual Image Compression**|Yiwen Jia et al.|[2602.01570](https://arxiv.org/pdf/2602.01570)|[GitHub](https://github.com/cheesejiang/OSDiff)|
|**2025.06**|**Single-step Diffusion for Image Compression at Ultra-Low Bitrates**|Chanung Park et al.|[2506.16572](https://arxiv.org/pdf/2506.16572)|null|
|**2025.05**|**Semantics-Guided Generative Image Compression**|Cheng-Lin Wu et al.|[2505.24015](https://arxiv.org/pdf/2505.24015)|null|
|**2025.05**|**Generative Image Compression by Estimating Gradients of the Rate-variable Feature Distribution**|Minghao Han et al.|[2505.20984](https://arxiv.org/pdf/2505.20984)|null|
|**2025.06**|**Bridging the Gap between Gaussian Diffusion Models and Universal Quantization for Image Compression**|Lucas Relic et al.|[CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Relic_Bridging_the_Gap_between_Gaussian_Diffusion_Models_and_Universal_Quantization_CVPR_2025_paper.pdf)|null|
|**2025.06**|**Decouple Distortion from Perception: Region Adaptive Diffusion for Extreme-low Bitrate Perception Image Compression**|Jinchang Xu et al.|[CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Xu_Decouple_Distortion_from_Perception_Region_Adaptive_Diffusion_for_Extreme-low_Bitrate_CVPR_2025_paper.pdf)|null|
|**2025.04**|**Once-for-All: Controllable Generative Image Compression with Dynamic Granularity Adaptation**|Anqi Li et al.|[2406.00758](https://arxiv.org/pdf/2406.00758)|[GitHub](https://github.com/lianqi1008/Control-GIC)|
|**2024.09**|**Lossy Image Compression with Foundation Diffusion Models**|Lucas Relic et al.|[2404.08580](https://arxiv.org/pdf/2404.08580)|null|
|**2024.02**|**MISC: Ultra-low Bitrate Image Semantic Compression Driven by Large Multimodal Model**|Chunyi Li et al.|[2402.16749](https://arxiv.org/pdf/2402.16749)|[GitHub](https://github.com/lcysyzxdxc/MISC)|
|**2023.10**|**Towards Image Compression with Perfect Realism at Ultra-Low Bitrates**|Marlene Careil et al.|[2310.10325](https://arxiv.org/pdf/2310.10325)|null|

## Generative Video Compression

|Publish Date|Title|Authors (First Author)|PDF|Code|
|---|---|---|---|---|
|**2026.03**|**Generative Video Compression with One-Dimensional Latent Representation**|Zihan Zheng et al.|[2603.15302](https://arxiv.org/pdf/2603.15302)|[Project](https://gvc1d.github.io/)|
|**2026.03**|**ProGVC: Progressive-based Generative Video Compression via Auto-Regressive Context Modeling**|Daowen Li et al.|[2603.17546](https://arxiv.org/pdf/2603.17546)|null|
|**2026.03**|**Generative video compression: towards 0.01% compression rate for video transmission**|Xiangyu Chen et al.|[Springer PDF](https://link.springer.com/content/pdf/10.1007/s44336-026-00035-2.pdf)|null|
|**2026.01**|**YODA: Yet Another One-step Diffusion-based Video Compressor**|Xingchen Li et al.|[2601.01141](https://arxiv.org/pdf/2601.01141)|[GitHub](https://github.com/NJUVISION/YODA)|
|**2026.01**|**DiffVC-RT: Towards Practical Real-Time Diffusion-based Perceptual Neural Video Compression**|Wenzhuo Ma et al.|[2601.20564](https://arxiv.org/pdf/2601.20564)|null|
|**2025.10**|**GIViC: Generative Implicit Video Compression**|Ge Gao et al.|[ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/papers/Gao_GIViC_Generative_Implicit_Video_Compression_ICCV_2025_paper.pdf)|[Project](https://ge1-gao.github.io/GIViC/)|
|**2025.10**|**Diffusion Autoencoders are Foundation Video Compressors**|Niccolo Niccoli et al.|[ICCVW 2025](https://openaccess.thecvf.com/content/ICCV2025W/MIPI/papers/Niccoli_Diffusion_Autoencoders_are_Foundation_Video_Compressors_ICCVW_2025_paper.pdf)|null|
|**2025.05**|**Generative Latent Coding for Ultra-Low Bitrate Image and Video Compression**|Linfeng Qi et al.|[2505.16177](https://arxiv.org/pdf/2505.16177)|[GitHub](https://github.com/jzyustc/GLC)|
|**2025.06**|**Towards Practical Real-Time Neural Video Compression**|Zhaoyang Jia et al.|[CVPR 2025](https://openaccess.thecvf.com/content/CVPR2025/papers/Jia_Towards_Practical_Real-Time_Neural_Video_Compression_CVPR_2025_paper.pdf)|[GitHub](https://github.com/microsoft/DCVC)|
|**2019.10**|**Video Compression With Rate-Distortion Autoencoders**|Amirhossein Habibian et al.|[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/papers/Habibian_Video_Compression_With_Rate-Distortion_Autoencoders_ICCV_2019_paper.pdf)|null|
|**2019.10**|**Learned Video Compression**|Oren Rippel et al.|[ICCV 2019](https://openaccess.thecvf.com/content_ICCV_2019/papers/Rippel_Learned_Video_Compression_ICCV_2019_paper.pdf)|null|
|**2018.09**|**Video Compression through Image Interpolation**|Chao-Yuan Wu et al.|[ECCV 2018](https://openaccess.thecvf.com/content_ECCV_2018/papers/Chao-Yuan_Wu_Video_Compression_through_ECCV_2018_paper.pdf)|null|

## Extreme Learned Image Compression

|Publish Date|Title|Authors (First Author)|PDF|Code|
|---|---|---|---|---|
|**2026.04**|**CoD-Lite: Real-Time Diffusion-Based Generative Image Compression**|Bin Li et al.|[2604.12525](https://arxiv.org/pdf/2604.12525)|[GitHub](https://github.com/microsoft/GenCodec/tree/main/CoD_Lite)|
|**2026.02**|**One-Step Diffusion for Perceptual Image Compression**|Yiwen Jia et al.|[2602.01570](https://arxiv.org/pdf/2602.01570)|[GitHub](https://github.com/cheesejiang/OSDiff)|
|**2025.10**|**StableCodec: Taming One-Step Diffusion for Extreme Image Compression**|Tianyu Zhang et al.|[ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhang_StableCodec_Taming_One-Step_Diffusion_for_Extreme_Image_Compression_ICCV_2025_paper.pdf)|null|
|**2025.10**|**DLF: Extreme Image Compression with Dual-generative Latent Fusion**|Naifu Xue et al.|[ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/papers/Xue_DLF_Extreme_Image_Compression_with_Dual-generative_Latent_Fusion_ICCV_2025_paper.pdf)|[Project](https://dlfcodec.github.io/)|
|**2025.06**|**Single-step Diffusion for Image Compression at Ultra-Low Bitrates**|Chanung Park et al.|[2506.16572](https://arxiv.org/pdf/2506.16572)|null|
|**2025.05**|**Generative Latent Coding for Ultra-Low Bitrate Image and Video Compression**|Linfeng Qi et al.|[2505.16177](https://arxiv.org/pdf/2505.16177)|[GitHub](https://github.com/jzyustc/GLC)|
|**2025.01**|**Toward Extreme Image Compression with Latent Feature Guidance and Diffusion Prior**|Zhiyuan Li et al.|[2404.18820](https://arxiv.org/pdf/2404.18820)|[GitHub](https://github.com/huai-chang/DiffEIC)|
|**2024.06**|**Generative Latent Coding for Ultra-Low Bitrate Image Compression**|Zhaoyang Jia et al.|[CVPR 2024](https://openaccess.thecvf.com/content/CVPR2024/papers/Jia_Generative_Latent_Coding_for_Ultra-Low_Bitrate_Image_Compression_CVPR_2024_paper.pdf)|[GitHub](https://github.com/jzyustc/GLC)|
|**2024.06**|**Once-for-All: Controllable Generative Image Compression with Dynamic Granularity Adaptation**|Anqi Li et al.|[2406.00758](https://arxiv.org/pdf/2406.00758)|[GitHub](https://github.com/lianqi1008/Control-GIC)|
|**2024.02**|**MISC: Ultra-low Bitrate Image Semantic Compression Driven by Large Multimodal Model**|Chunyi Li et al.|[2402.16749](https://arxiv.org/pdf/2402.16749)|[GitHub](https://github.com/lcysyzxdxc/MISC)|
|**2023.10**|**Towards Image Compression with Perfect Realism at Ultra-Low Bitrates**|Marlene Careil et al.|[2310.10325](https://arxiv.org/pdf/2310.10325)|null|
|**2023.07**|**Extreme Image Compression using Fine-tuned VQGANs**|Qi Mao et al.|[2307.08265](https://arxiv.org/pdf/2307.08265)|[GitHub](https://github.com/CUC-MIPG/VQGAN-Compression)|

## Extreme Learned Video Compression

|Publish Date|Title|Authors (First Author)|PDF|Code|
|---|---|---|---|---|
|**2026.03**|**Generative video compression: towards 0.01% compression rate for video transmission**|Xiangyu Chen et al.|[Springer PDF](https://link.springer.com/content/pdf/10.1007/s44336-026-00035-2.pdf)|null|
|**2026.03**|**Generative Video Compression with One-Dimensional Latent Representation**|Zihan Zheng et al.|[2603.15302](https://arxiv.org/pdf/2603.15302)|[Project](https://gvc1d.github.io/)|
|**2026.03**|**ProGVC: Progressive-based Generative Video Compression via Auto-Regressive Context Modeling**|Daowen Li et al.|[2603.17546](https://arxiv.org/pdf/2603.17546)|null|
|**2026.01**|**DiffVC-RT: Towards Practical Real-Time Diffusion-based Perceptual Neural Video Compression**|Wenzhuo Ma et al.|[2601.20564](https://arxiv.org/pdf/2601.20564)|null|
|**2026.01**|**YODA: Yet Another One-step Diffusion-based Video Compressor**|Xingchen Li et al.|[2601.01141](https://arxiv.org/pdf/2601.01141)|[GitHub](https://github.com/NJUVISION/YODA)|
|**2025.10**|**Diffusion Autoencoders are Foundation Video Compressors**|Niccolo Niccoli et al.|[ICCVW 2025](https://openaccess.thecvf.com/content/ICCV2025W/MIPI/papers/Niccoli_Diffusion_Autoencoders_are_Foundation_Video_Compressors_ICCVW_2025_paper.pdf)|null|
|**2025.10**|**GIViC: Generative Implicit Video Compression**|Ge Gao et al.|[ICCV 2025](https://openaccess.thecvf.com/content/ICCV2025/papers/Gao_GIViC_Generative_Implicit_Video_Compression_ICCV_2025_paper.pdf)|[Project](https://ge1-gao.github.io/GIViC/)|
|**2025.05**|**Generative Latent Coding for Ultra-Low Bitrate Image and Video Compression**|Linfeng Qi et al.|[2505.16177](https://arxiv.org/pdf/2505.16177)|[GitHub](https://github.com/jzyustc/GLC)|

## Dataset for Human Vision Perception

|Publish Date|Title|Authors (First Author)|PDF|Code|
|---|---|---|---|---|
|**2023.10**|**EvalCrafter: Benchmarking and Evaluating Large Video Generation Models**|Yaofang Liu et al.|[2310.11440](https://arxiv.org/pdf/2310.11440)|[GitHub](https://github.com/evalcrafter/EvalCrafter)|
|**2023.07**|**AIGCIQA2023: A Large-scale Image Quality Assessment Database for AI Generated Images: from the Perspectives of Quality, Authenticity and Correspondence**|Jiarui Wang et al.|[2307.00211](https://arxiv.org/pdf/2307.00211)|[GitHub](https://github.com/wangjiarui153/aigciqa2023)|
|**2023.06**|**AGIQA-3K: An Open Database for AI-Generated Image Quality Assessment**|Chunyi Li et al.|[2306.04717](https://arxiv.org/pdf/2306.04717)|[GitHub](https://github.com/lcysyzxdxc/AGIQA-3k-Database)|
|**2019.10**|**KonIQ-10k: An ecologically valid database for deep learning of blind image quality assessment**|Vlad Hosu et al.|[1910.06180](https://arxiv.org/pdf/1910.06180)|[Dataset](https://database.mmsp-kn.de/koniq-10k-database.html)|
|**2019.06**|**KADID-10k: A Large-scale Artificially Distorted IQA Database**|Hanhe Lin et al.|[QoMEX 2019 PDF](https://www.researchgate.net/profile/Hanhe-Lin/publication/332567482_KADID-10k_A_Large-scale_Artificially_Distorted_IQA_Database/links/5cbd9785a6fdcc1d498e5e88/KADID-10k-A-Large-scale-Artificially-Distorted-IQA-Database.pdf)|[Dataset](https://database.mmsp-kn.de/kadid-10k-database.html)|
|**2016.09**|**MCL-JCV: A JND-based H.264/AVC Video Quality Assessment Dataset**|Haiqiang Wang et al.|[ICIP 2016](https://mcl.usc.edu/wp-content/uploads/2016/09/07532610.pdf)|[Dataset](https://mcl.usc.edu/mcl-jcv-dataset/)|
|**2015.01**|**Image database TID2013: Peculiarities, results and perspectives**|Nikolay Ponomarenko et al.|[Open PDF](https://www.sciencedirect.com/science/article/pii/S0923596514001490/pdfft)|[Dataset](http://www.ponomarenko.info/tid2013.htm)|
|**2013.06**|**Color image database TID2013: Peculiarities and preliminary results**|Nikolay Ponomarenko et al.|[EUVIP 2013 PDF](https://www.researchgate.net/profile/Nikolay-Ponomarenko/publication/261094981_Color_image_database_TID2013_Peculiarities_and_preliminary_results/links/0f3175326eaacc1df4000000/Color-image-database-TID2013-Peculiarities-and-preliminary-results.pdf)|[Dataset](http://www.ponomarenko.info/tid2013.htm)|

## Dataset for Machine Vision Perception

|Publish Date|Title|Authors (First Author)|PDF|Code|
|---|---|---|---|---|
|**2025.03**|**Image Quality Assessment: From Human to Machine Preference**|Chunyi Li et al.|[2503.10078](https://arxiv.org/pdf/2503.10078)|[GitHub](https://github.com/lcysyzxdxc/MPD)|
|**2017.06**|**Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering**|Yash Goyal et al.|[CVPR 2017](https://openaccess.thecvf.com/content_cvpr_2017/papers/Goyal_Making_the_V_CVPR_2017_paper.pdf)|[Dataset](https://visualqa.org/download.html)|
|**2017.07**|**Scene Parsing through ADE20K Dataset**|Bolei Zhou et al.|[1608.05442](https://arxiv.org/pdf/1608.05442)|[GitHub](https://github.com/CSAILVision/ADE20K)|
|**2017.01**|**Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations**|Ranjay Krishna et al.|[1602.07332](https://arxiv.org/pdf/1602.07332)|[Dataset](https://homes.cs.washington.edu/~ranjay/visualgenome/index.html)|
|**2016.04**|**The Cityscapes Dataset for Semantic Urban Scene Understanding**|Marius Cordts et al.|[1604.01685](https://arxiv.org/pdf/1604.01685)|[Dataset](https://www.cityscapes-dataset.com/)|
|**2015.12**|**ImageNet Large Scale Visual Recognition Challenge**|Olga Russakovsky et al.|[1409.0575](https://arxiv.org/pdf/1409.0575)|[Dataset](https://www.image-net.org/)|
|**2018.11**|**Open Images Dataset V4: Unified image classification, object detection, and visual relationship detection at scale**|Alina Kuznetsova et al.|[1811.00982](https://arxiv.org/pdf/1811.00982)|[Dataset](https://storage.googleapis.com/openimages/web/index.html)|
|**2014.05**|**Microsoft COCO: Common Objects in Context**|Tsung-Yi Lin et al.|[1405.0312](https://arxiv.org/pdf/1405.0312)|[Dataset](https://cocodataset.org/)|

## Test Conditions

- **Image benchmark recommendation:** `Kodak`, `CLIC2020/CLIC2021`, `DIV2K`, and optionally `MS-COCO-30K` for human preference or generative evaluation.
- **Video benchmark recommendation:** `UVG`, `HEVC Class B/C/E`, `MCL-JCV`, and clearly state `low-delay` or `random-access` settings.
- **Report bitrate consistently:** use `bpp` for images and `bpp / kbps` for videos; specify whether entropy coding is included.
- **Report color/setup explicitly:** resolution, crop policy, RGB vs. YUV, `4:4:4` vs. `4:2:0`, GOP size, intra period, and frame count.
- **Report both fidelity and perceptual metrics:** `PSNR`, `MS-SSIM`, `LPIPS`, `DISTS`, `FID`, `KID`, and for video also `FVD` if applicable.
- **Human/machine dual evaluation:** when the method targets joint perception, additionally report downstream task performance on `COCO`, `Cityscapes`, `ADE20K`, `VQA v2`, or task-specific benchmarks.
- **Runtime reporting:** GPU/CPU model, precision (`fp32/fp16/bf16`), encoding speed, decoding speed, and whether the numbers include entropy coding.
