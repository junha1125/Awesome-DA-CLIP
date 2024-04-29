# Awesome-DA-CLIP

1. Measuring CLIP capability
   1. **C-TPT: Calibrated Test-Time Prompt Tuning for Vision-Language Models via Text Feature Dispersion. ICLR, 2024.** 
   2. **DSG:Davidsonian scene graph: Improving reliability in fine-grained evaluation for textimage generation. ICLR, 2024.**
   3. Decomposed CLIPScore: Improving Text-to-Image Consistency via Automatic Prompt Optimization. Meta, 2024.
2. CLIP Finetuning
   1. Fine-tuned CLIP Models are Efficient Video Learners. CVPR, 2023. 55.
   2. Fine-tuning CLIP Text Encoders with Two-step Paraphrasing. EACL, 2024. 0.
   3. Improving CLIP Fine-tuning Performance. ICCV, 2023. 2.
   4. 🍀 CLIP Itself is a Strong Fine-tuner: Achieving 85.7% and 88.0% Top-1 Accuracy with ViT-B and ViT-L on ImageNet. arXiv, 2022. 17.
   5. 🍀 ELEVATER: A Benchmark and Toolkit for Evaluating Language-Augmented Visual Models. NeurIPS, 2022. 92.
   6. 🍀 Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs. CVPR 2024.
   7. Tip-Adapter: Training-free Adaption of CLIP for Few-shot Classification. ECCV, 2022. 139.
   8. CLIP-Adapter: Better Vision-Language Models with Feature Adapters. IJCV, 2024. 480.
   9. 🍀 A Closer Look at the Few-Shot Adaptation of Large Vision-Language Models. CVPR, 2024. 2.
   10. Feature Adaptation with CLIP for Few-shot Classification. ACM, 2023. 0.
   11. Multimodality helps unimodality: Cross-modal few-shot learning with multimodal models. CVPR, 2023. 53. 
   12. Multimodal Adaptation of CLIP for Few-Shot Action Recognition. CVPR, 2023. 6.
   13. Not all features matter: Enhancing few-shot clip with adaptive prior refinement. ICCV, 2023.
   14. 🍀 A Hard-to-Beat Baseline for Training-free CLIP-based Adaptation. ICLR, 2024.0.
   15. Task Residual for Tuning Vision-Language Models. CVPR, 2023. 32.
   16. Towards Calibrated Robust Fine-Tuning of Vision-Language Models. NeurIPS_W 2023. 3.
   17. Robust Cross-Modal Representation Learning with Progressive Self-Distillation. CVPR, 2022. 36.(contrastive learning with noise data)
   18. CoOp: Learning to Prompt for Vision-Language Models. IJCV. 2022. 1316.
3. CLIP pretraining & Analyzing
   1. Long-CLIP: Long-CLIP: Unlocking the Long-Text Capability of CLIP, Mar 2024.
   2. DreamLIP: Language-Image Pre-training with Long Captions ([project](https://zyf0619sjtu.github.io/dream-lip/)). arXiv, 2024.
   3. Scaling (Down) CLIP: A Comprehensive Analysis of Data, Architecture, and Training Strategies. arXiv. Arp 2024.
   4. Vision-Language Pre-Training: Basics, Recent Advances, and Future Trends. 122. (survey from MS)
   5. Interpreting CLIP's Image Representation via Text-Based Decomposition. ICLR 2024.
   6. SigCLIP
   7. MetaCLIP
4. CLIP adaptation
   1. Domain Adaptation via Prompt Learning. arXiv 2022.
   2. Prompt Switch: Efficient CLIP Adaptation for Text-Video Retrieval. ICCV, 2023. 5. 
   3. AD-CLIP: Adapting Domains in Prompt Space Using CLIP. ICCV workshop, 2023. 13.
   4. AutoLabel: CLIP-based framework for Open-set Video Domain Adaptation. CVPR, 2023. 6.
   5. PromptStyler: Prompt-driven Style Generation  for Source-free Domain Generalization. ICCV, 2023. 18.
   6. POUF: Prompt-oriented unsupervised fine-tuning for large pre-trained models. ICML 2023. 18. (SFDA)
   7. Sus-x: Training-free name-only transfer of vision-language models. ICCV, 2023. 28. (training-free)
   8. Improving zero-shot generalization and robustness of multi-modal models. CVPR, 2023. 15 (training-free)
   9. 🍀 TPT: Test-time prompt tuning for zero-shot generalization in vision language models. NeurIPS, 2022. 141.
   10. Robust Multi-Task Learning and Online Refinement for Spacecraft Pose Estimation across Domain Gap. Advances in Space Research. 2022. 34.
   11. 🍀 SwapPrompt: Test-Time Prompt Adaptation for Vision-Language Models. NeurIPS, 2023. 3.
   12. 🍀 DiffTPT: Diverse data augmentation with diffusions for effective test-time prompt tuning. ICCV, 2023. 15.
   13. BaFTA: Backprop-Free Test-Time Adaptation for Zero-shot Vision Language Models. ICLR 2024 rejected (but good scores)
   14. 🍀 Empowering Unsupervised Domain Adaptation with Large-scale Pre-trained Vision-Language Models. WACV, 2024. 1.
   15. 🍀 TDA: Efficient Test-Time Adaptation of Vision-Language Models. CVPR, 2024.
   16. 🍀 Source-Free Domain Adaptation with Frozen Multimodal Foundation Model CVPR 2024.
   17. 🍀 ReCLIP Refine Contrastive Language Image Pre-Training with Source Free Domain Adaptation. WACV oral, 2024.
5. Retrival augmented methods in computer vision.
   1. [linkedin post1](https://www.linkedin.com/posts/aurimas-griciunas_llm-genai-llmops-activity-7185911719003582464-81pX?utm_source=share&utm_medium=member_desktop), [linkedin post2](https://www.linkedin.com/feed/update/urn:li:activity:7178583071540080641/?utm_source=share&utm_medium=member_desktop)
   2. Retrieval augmented classiﬁcation for long-tail visual recognition. CPVR, 2022. 67.
   3. 🍀 Improving Image Recognition by Retrieving from Web-Scale Image-Text Data. CVPR, 2023. 10.
   4. 🍀 REACT: Learning Customized Visual Models with Retrieval-Augmented Knowledge. CVPR, 2023. 10.
   5. 🍀 Retrieval-Augmented Multimodal Language Modeling. ICML, 2023. 44.
   6. Check Your Facts and Try Again: Improving Large Language Models with External Knowledge and Automated Feedback. MS. 2023. 234.
   7. K-lite: Learning transferable visual models with external knowledge. NeurIPS, 2022. 64
6. SAM + Domain adaptation
   1. 🍀 SAM-DA: UAV Tracks Anything at Night with SAM-Powered Domain Adaptation. arXiv, 2024. 7 ([github](https://github.com/vision4robotics/SAM-DA))
   2. 🍀 SAM4UDASS: When SAM Meets Unsupervised Domain Adaptive Semantic Segmentation in Intelligent Vehicles. arXiv, 2024.
   3. SAM-guided Unsupervised Domain Adaptation for 3D Segmentation. arXiv(ICLR2024 submitted), 2024. 
7. Utilizing text-image alignment. 
   1. SPAE: Semantic Pyramid AutoEncoder for Multimodal Generation with Frozen LLMs. NeurIPS 2023 spotlight. 14.
   2. Using Language to Extend to Unseen Domains. ICLR, 2023. 20.
   3. StyleGAN-NADA: CLIP-Guided Domain Adaptation of Image Generators. ACM, 2021. 471.
   4. Diagnosing and Rectifying Vision Models using Language. ICLR, 2023. 27.
   5. TextManiA: Enriching Visual Feature by Text-driven Manifold Augmentation. ICCV, 2023. 2.
   6. Using Language to Entend to Unseen Domains. ICLR, 2023. 20.
   7. Embedding Arithmetic of Multimodal Queries for Image Retrieval. CVPRW, 2022. 17.
8. Distillation
   1. NVIDIA-AI-IOT/CLIP-distillation ([github](https://github.com/NVIDIA-AI-IOT/clip-distillation))
   2. CLIP-KD: An Empirical Study of Distilling CLIP Models. CVPR 2024. 3.
   3. TinyCLIP: CLIP Distillation via Affinity Mimicking and Weight Inheritance. ICCV 2023. 10.
   4. CLIPPING: Distilling CLIP-Based Models with a Student Base for Video-Language Retrieval. CVPR 2024. 18.
   5. Multimodal Adaptive Distillation for Leveraging Unimodal Encoders for Vision-Language Tasks. MS, 2022. (CLIP-TD: CLIP Targeted Distillation). 5.
   6. EfficientSAM: Leveraged Masked Image Pretraining for Efficient Segment Anything. CVPR 2024. 15.
      - MIC: Masked Image Consistency for Context-Enhanced Domain Adaptation. CVPR, 2023. 141.
   7. dd
9. Generalize/Distill and Adapt
   1. Generalize then Adapt: Source-Free Domain Adaptive Semantic Segmentation. ICCV 2021. 102.
   2. DiGA: Distil to Generalize and then Adapt for Domain Adaptive Semantic Segmentation. CVPR 2023. 8.
