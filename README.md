# awesome-conditional-content-generation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repository contains a collection of resources and papers on ***Conditional Content Generation***. Especially for human motion generation, image generation and video generation. This repo is maintained by [Haofan Wang](https://github.com/haofanwang).


## Contents
- Papers List
  - Conditional Human Motion Generation
    - [Music-Driven motion generation](#music-driven-motion-generation)
    - [Text-Driven motion generation](#text-driven-motion-generation)
    - [Audio-Driven motion generation](#audio-driven-motion-generation)
    - [Human Motion Prediction](#human-motion-prediction)
    - [Motion Applications](#motion-applications)
  - Conditional Image Generation
    - [Text-Image Generation](#text-image-generation)
    - [Text-3D Image Generation](#text-3d-image-generation)
  - Conditional Video Generation
    - [Text-Video Generation](#text-video-generation)

## Papers

### Music-Driven motion generation
[EDGE: Editable Dance Generation From Music](https://arxiv.org/abs/2211.10658) \
Stanford University, 19 Nov 2022

[GroupDancer: Music to Multi-People Dance Synthesis with Style Collaboration](https://dl.acm.org/doi/abs/10.1145/3503161.3548090) \
Tsinghua University, ACMMM'22

[A Brand New Dance Partner: Music-Conditioned Pluralistic Dancing Controlled by Multiple Dance Genres](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_A_Brand_New_Dance_Partner_Music-Conditioned_Pluralistic_Dancing_Controlled_by_CVPR_2022_paper.pdf) \
Yonsei University, CVPR 2022, [[Code]](https://github.com/jw09191/MNET)

[Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory](https://www.mmlab-ntu.com/project/bailando/index.html) \
NTU, CVPR 2022 (Oral), [[Code]](https://github.com/lisiyao21/Bailando)

[Dance Style Transfer with Cross-modal Transformer](https://arxiv.org/abs/2208.09406) \
KTH, 22 Aug 2022, [[Upcoming Code]](https://github.com/YIN95/cycledance-pytorch-lightning)

[Music-driven Dance Regeneration with Controllable Key Pose Constraints](https://arxiv.org/abs/2207.03682) \
Tencent, 8 July 2022

[AI Choreographer: Music Conditioned 3D Dance Generation with AIST++](https://google.github.io/aichoreographer/) \
USC, ICCV 2021, [[Code]](https://github.com/google-research/mint)

### Text-Driven motion generation
[MotionBERT: Unified Pretraining for Human Motion Analysis](https://motionbert.github.io/) \
SenseTime Research, 12 Oct 2022, [[Code]](https://github.com/Walter0807/MotionBERT)

[Human Motion Diffusion Model](https://guytevet.github.io/mdm-page) \
Tel Aviv University, 3 Oct 2022, [[Code]](https://github.com/GuyTevet/motion-diffusion-model)

[FLAME: Free-form Language-based Motion Synthesis & Editing](https://arxiv.org/abs/2209.00349) \
Korea University, 1 Sep 2022

[MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html) \
NTU, 22 Aug 2022, [[Code]](https://github.com/mingyuan-zhang/MotionDiffuse)

[MotionCLIP: Exposing Human Motion Generation to CLIP Space](https://guytevet.github.io/motionclip-page/) \
Tel Aviv University, ECCV 2022, [[Code]](https://github.com/GuyTevet/MotionCLIP)

[Generating Diverse and Natural 3D Human Motions from Text](https://ericguo5513.github.io/text-to-motion/) \
University of Alberta, CVPR 2022, [[Code]](https://github.com/EricGuo5513/text-to-motion)

[AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars](https://hongfz16.github.io/projects/AvatarCLIP.html) \
NTU, SIGGRAPH 2022, [[Code]](https://github.com/hongfz16/AvatarCLIP)

[Text2Gestures: A Transformer-Based Network for Generating Emotive Body Gestures for Virtual Agents](https://arxiv.org/abs/2101.11101) \
University of Maryland,, VR 2021, [[Code]](https://github.com/UttaranB127/Text2Gestures)

### Audio-Driven motion generation

For more recent paper, you can find from [here](https://github.com/YunjinPark/awesome_talking_face_generation)

[ZeroEGGS: Zero-shot Example-based Gesture Generation from Speech](https://arxiv.org/abs/2209.07556) \
York University, 23 Sep 2022, [[Code]](https://github.com/ubisoft/ubisoft-laforge-ZeroEGGS)

[EAMM: One-Shot Emotional Talking Face via Audio-Based Emotion-Aware Motion Model](https://jixinya.github.io/projects/EAMM/)\
Nanjing University, SIGGRAPH 2022, [[Code]](https://github.com/jixinya/EAMM/)

[Learning Hierarchical Cross-Modal Association for Co-Speech Gesture Generation](https://openaccess.thecvf.com/content/CVPR2022/papers/Liu_Learning_Hierarchical_Cross-Modal_Association_for_Co-Speech_Gesture_Generation_CVPR_2022_paper.pdf) \
The Chinese University of Hong Kong, CVPR 2022, [[Code]](https://github.com/alvinliu0/HA2G)

[SEEG: Semantic Energized Co-speech Gesture Generation](https://ffmpbgrnn.github.io/publications/pdf/seeg.pdf) \
Alibaba DAMO Academy, CVPR 2022, [[Code]](https://github.com/akira-l/SEEG)

[FaceFormer: Speech-Driven 3D Facial Animation with Transformers](https://evelynfan.github.io/audio2face/) \
The University of Hong Kong, CVPR 2022, [[Code]](https://github.com/EvelynFan/FaceFormer)

[Freeform Body Motion Generation from Speech](https://arxiv.org/abs/2203.02291) \
JD AI Research, 4 Mar 2022, [[Code]](https://github.com/TheTempAccount/Co-Speech-Motion-Generation)

[Audio2Gestures: Generating Diverse Gestures from Speech Audio with Conditional Variational Autoencoders](https://jingli513.github.io/audio2gestures/) \
Tencent AI Lab, ICCV 2021, [[Code]](https://github.com/JingLi513/Audio2Gestures)

[Learning Speech-driven 3D Conversational Gestures from Video](https://arxiv.org/abs/2102.06837) \
Max Planck Institute for Informatics, IVA 2021, [[Code]](http://gvv.mpi-inf.mpg.de/projects/3d_speech_driven_gesture/)

[Learning Individual Styles of Conversational Gesture](https://openaccess.thecvf.com/content_CVPR_2019/papers/Ginosar_Learning_Individual_Styles_of_Conversational_Gesture_CVPR_2019_paper.pdf) \
UC Berkeley, CVPR 2019, [[Code]](https://github.com/amirbar/speech2gesture)

### Human motion prediction

For more recent more, you can find from [here](https://github.com/aras62/vision-based-prediction/blob/master/papers/motion_papers.md)

[PoseGPT: Quantization-based 3D Human Motion Generation and Forecasting](https://europe.naverlabs.com/research/computer-vision/posegpt/) \
NAVER LABS, ECCV'2022, [[Code]](https://github.com/naver/PoseGPT)

[NeMF: Neural Motion Fields for Kinematic Animation](https://cs.yale.edu/homes/che/projects/nemf/) \
Yale University, NeurIPS 2022 (Spotlight), [[Code]](https://github.com/c-he/NeMF)

[Multi-Person Extreme Motion Prediction](https://openaccess.thecvf.com/content/CVPR2022/papers/Guo_Multi-Person_Extreme_Motion_Prediction_CVPR_2022_paper.pdf) \
Inria University, CVPR 2022, [[Code]](https://github.com/GUO-W/MultiMotion)

[MotionMixer: MLP-based 3D Human Body Pose Forecasting](https://arxiv.org/abs/2207.00499) \
Mercedes-Benz, IJCAI 2022 (Oral), [[Code]](https://github.com/MotionMLP/MotionMixer)

[Multi-Person 3D Motion Prediction with Multi-Range Transformers](https://arxiv.org/abs/2111.12073) \
UCSD, NeurIPS 2021

### Motion Applications
[Motion In-betweening via Two-stage Transformers](http://kunzhou.net/2022/motion-siga22.pdf) \
Zhejiang University, SIGGRAPH Asia 2022

[Skeleton2Humanoid: Animating Simulated Characters for Physically-plausible Motion In-betweening](https://dl.acm.org/doi/abs/10.1145/3503161.3548093) \
Shanghai Jiaotong University, ACMMM 2022, [[Upcoming Code]](https://github.com/michaelliyunhao/Skeleton2Humanoid)

[Conditional Motion In-betweening](https://arxiv.org/abs/2202.04307) \
Korea University, 6 Oct 2022, [[Code]](https://github.com/jihoonerd/Conditional-Motion-In-Betweening)

[SkeletonMAE: Spatial-Temporal Masked Autoencoders for Self-supervised Skeleton Action Recognition](https://arxiv.org/abs/2209.02399) \
University of North Carolina, 1 Sep 2022

[Transformer based Motion In-betweening](https://openaccess.thecvf.com/content/ACCV2022W/TCV/papers/Sridhar_Transformer_Based_Motion_In-Betweening_ACCVW_2022_paper.pdf) \
National Institute of Technology - Tiruchirappalli, ACCV 2022 Workshop, [[Code]](https://github.com/Pavi114/motion-completion-using-transformers)

[Generative Tweening: Long-term Inbetweening of 3D Human Motions](https://zhouyisjtu.github.io/project_tweening/GenerativeTweening.html) \
Adobe Research, 28 May 2020

### Text-Image Generation

For more recent paper, you can find from [here](https://github.com/heejkoo/Awesome-Diffusion-Models#text-to-image)

[Synthesizing Coherent Story with Auto-Regressive Latent Diffusion Models](https://arxiv.org/pdf/2211.10950.pdf) \
University of Waterloo, 20 Nov 2022, [[Upcoming Code]](https://github.com/Flash-321/ARLDM)

[InstructPix2Pix: Learning to Follow Image Editing Instructions](https://arxiv.org/abs/2211.09800) \
UC Berkeley, 17 Nov 2022

[Null-text Inversion for Editing Real Images using Guided Diffusion Models](https://arxiv.org/abs/2211.09794) \
Google Research, 17 Nov 2022

[HumanDiffusion: a Coarse-to-Fine Alignment Diffusion Framework for Controllable Text-Driven Person Image Generation](https://arxiv.org/abs/2211.06235) \
University of Chinese Academy of Sciences, 11 Nov 2022

[Imagic: Text-Based Real Image Editing with Diffusion Models](https://imagic-editing.github.io/) \
Google Research, 17 Oct 2022

[Self-Guided Diffusion Models](https://arxiv.org/abs/2210.06462) \
University of Amsterdam, 12 Oct 2022

[DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation](https://dreambooth.github.io/) \
Google Research, 25 Aug 2022, [[Code]](https://github.com/XavierXiao/Dreambooth-Stable-Diffusion)

[Prompt-to-Prompt Image Editing with Cross Attention Control](https://arxiv.org/abs/2208.01626) \
Google Research, 2 Aug 2022, [[Code]](https://github.com/bloc97/CrossAttentionControl)

[Improved Vector Quantized Diffusion Models](https://arxiv.org/abs/2205.16007) \
University of Science and Technology of China, 31 May 2022, [[Code]](https://github.com/cientgu/VQ-Diffusion)

[Diffusion Autoencoders: Toward a Meaningful and Decodable Representation](https://diff-ae.github.io/) \
Vidyasirimedhi Institute of Science and Technology, CVPR 2022 (Oral), [[Code]](https://github.com/phizaz/diffae)

[Vector Quantized Diffusion Model for Text-to-Image Synthesis](https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.pdf) \
University of Science and Technology of China, CVPR 2022, [[Code]](https://github.com/cientgu/VQ-Diffusion)

[High-Resolution Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf) \
Runway ML, CVPR 2022, [[Code]](https://github.com/CompVis/latent-diffusion)

### Text-Video Generation

[Latent Video Diffusion Models for High-Fidelity Video Generation with Arbitrary Lengths](https://yingqinghe.github.io/LVDM/) \
The Hong Kong University of Science and Technology, 23 Nov 2022, [[Upcoming Code]](https://github.com/YingqingHe/LVDM)

[MagicVideo: Efficient Video Generation With Latent Diffusion Models](https://magicvideo.github.io/) \
ByteDance Inc, 20 Nov 2022

[Text2LIVE: Text-Driven Layered Image and Video Editing](https://text2live.github.io/) \
NVIDIA Research, ECCV 2022 (Oral), [[Code]](https://github.com/omerbt/Text2LIVE)

### Text-3D Image Generation
[DreamFusion: Text-to-3D using 2D Diffusion](https://dreamfusion3d.github.io/) \
Google Research, 29 Sep 2022
