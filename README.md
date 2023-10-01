# Face Morphing and De-morphing
This repository collects papers in the field of face morphing attacks and defense, including surveys, databases, generation models and detection methods.

Keep updating!!!

# Survey			
## Face Morphing
* 2022	A Comprehensive Review of Face Morph Generation and Detection of Fraudulent Identities	[[paper]](https://www.mdpi.com/2076-3417/12/24/12545)
* 2022	Morphing Attack Detection-State of the Art and Challenges [[report]](https://www.christoph-busch.de/files/Busch-MAD-220607.pdf)
* 2022	Face Morphing Attack Detection Methods		
* 2022	A Systematic Literature Review on Face Morphing Attack Detection (MAD)		
* 2021	Face Morphing, a Modern Threat to Border Security: Recent Advances and Open Challenges	attack	[[paper]](https://www.mdpi.com/2076-3417/11/7/3207)
* 2021	Face Recognition Systems Under Morphing Attacks: A Survey	attack	[[paper]](https://ieeexplore.ieee.org/abstract/document/8642312)
* 2021	Face morphing attack generation and detection: A comprehensive survey		
	


## 3D Morphing
* 2022	3D Face Morphing Attacks: Generation, Vulnerability and Detection	[[paper]](https://arxiv.org/abs/2201.03454)
* 2022	Cross-Species 3D Face Morphing via Alignment-Aware Controller	[[paper]](https://www.aaai.org/AAAI22Papers/AAAI-2209.YanX.pdf)






## GAN
* 2022	State-of-the-Art in the Architecture, Methods and Applications of StyleGAN	[[paper]](https://arxiv.org/abs/2202.14020)
* 2021	Review on Generative Adversarial Network in Computer Vision: Methods and Metrics	[[paper]](https://ieeexplore.ieee.org/abstract/document/9696113)
* 2021	Review on Generative Adversarial Networks: Focusing on Computer Vision and Its Applications	[[paper]](https://www.mdpi.com/2079-9292/10/10/1216)
* 2022	GAN Inversion: A Survey	[[paper]](https://github.com/weihaox/awesome-gan-inversion)
		
## Transformer		
* 2022	Recent Advances in Vision Transformer: A Survey and Outlook of Recent Work	[[paper]](https://arxiv.org/abs/2203.01536)
* 2022	Three things everyone should know about Vision Transformers	[[paper]](https://arxiv.org/abs/2203.09795)
* 2022	Transformers in computational visual media: A survey	[[paper]](https://link.springer.com/article/10.1007/s41095-021-0247-3)

# Databases
* 2021	A Benchmark Database for the Comparison of Face Morphing Detection Methods	DB




# Face Morphing Attacks
* 2021	Vulnerability Analysis of Face Morphing Attacks from Landmarks and Generative Adversarial Networks	[[paper]](https://arxiv.org/abs/2012.05344)
* 2023	MorDIFF: Recognition Vulnerability and Attack Detectability of Face Morphing Attacks Created by Diffusion Autoencoders	[[paper]](https://arxiv.org/abs/2302.01843)
* 2021	ReGenMorph: Visibly Realistic GAN Generated Face Morphing Attacks by Attack Re-generation	[[paper]](http://128.84.21.203/abs/2108.09130)
* 2021	Deep Composite Face Image Attacks: Generation, Vulnerability and Detection	[[paper]](https://arxiv.org/abs/2211.11039)
* 2023	Diffusion Models For Stronger Face Morphing Attacks	[[paper]](https://arxiv.org/abs/2301.04218)
* 2022	3D Face Morphing Attacks: Generation, Vulnerability and Detection	[[paper]](https://arxiv.org/abs/2201.03454)




# Generation Models
## Tools
* 2021	StyleSwin: https://github.com/yqGANs/StyleSwin	1024x1024	Swin-Transformer  Pure-Transformer
*	2021	HiT-B:	https://github.com/google-research/hit-gan	1024x1024	  Pure-Transformer
*	2021	GANformer:	https://github.com/dorarad/gansformer	256x256	
*	2021	GANformer2:	https://github.com/dorarad/gansformer	256x256	
*	2021	TransGAN:	https://github.com/VITA-Group/TransGAN	256x256	  Pure-Transformer
* 2021	Diffusion:	https://github.com/openai/guided-diffusion		GAN
* 2021	StyleGAN3:	https://nvlabs.github.io/stylegan3/		 GAN

## GAN-based
* 2021	StyleGAN3	Alias-Free Generative Adversarial Networks	[[paper]](https://arxiv.org/abs/2106.12423),	[[code]](https://github.com/NVlabs/stylegan3),	[[project]](https://nvlabs.github.io/stylegan3/)
* 2019	StyleGAN	A Style-Based Generator Architecture for Generative Adversarial Networks [[paper]](https://arxiv.org/abs/1812.04948),	[[code]](https://github.com/NVlabs/stylegan),	[[FFHQ]](https://github.com/NVlabs/ffhq-dataset),	[[video]](https://youtu.be/kSLJriaOumA)
* 2019	Image2StyleGAN	Image2StyleGAN: How to Embed Images Into the StyleGAN Latent Space?	[[paper]](https://arxiv.org/abs/1904.03189),	[[code]](https://github.com/zaidbhat1234/Image2StyleGAN)
* 2020	Image2StyleGAN++	How to Edit the Embedded Images?	[[paper]](https://arxiv.org/abs/1911.11544),	[[code]](https://github.com/pacifinapacific/StyleGAN_LatentEditor),	[[project]](https://paperswithcode.com/paper/image2stylegan-how-to-edit-the-embedded)			
* 2018	FastPhotoStyle	A Closed-form Solution to Photorealistic Image Stylization	[[paper]](https://arxiv.org/abs/1802.06474),	[[code]](https://github.com/NVIDIA/FastPhotoStyle),		[[tutorial]](https://github.com/NVIDIA/FastPhotoStyle/blob/master/TUTORIAL.md),	Image Transformation	
* 2021	TrGAN	Unsupervised Image Transformation Learning via Generative Adversarial Networks	[[paper]](https://arxiv.org/pdf/2103.07751.pdf),	[[code]](https://github.com/genforce/trgan),	[[project]](https://genforce.github.io/trgan/),	[[video]](https://www.youtube.com/watch?v=ZTYLihZYwYM),	Image Transformation	
* 2022	StyleFusion	StyleFusion: Disentangling Spatial Segments in StyleGAN-Generated Images	[[paper]](https://dl.acm.org/doi/abs/10.1145/3527168?casa_token=lM-oR1gueGoAAAAA:Ba0-Lkj2TM5EI8KOs7UsTH_xKV54Tprqqkn9GD9Xp_8Hrk2tbY-tSRQopsimUEOZ_72398kdwfrS)					
* 2022	GuidedStyle	GuidedStyle: Attribute knowledge guided style manipulation for semantic face editing	[[paper]](https://reader.elsevier.com/reader/sd/pii/S0893608021004081?token=76D73A0D8961B63532327C224B39CD9E81C332A92C6F958D9DD88315672FD5C39C23DF798DC26E27DE92E361BEE15391&originRegion=us-east-1&originCreation=20220502204600), Face Editing	
* 2022	E2Style	E2Style: Improve the Efficiency and Effectiveness of StyleGAN Inversion	[[paper]](https://ieeexplore.ieee.org/abstract/document/9760266), image inversion	
* 2022		Region-Based Semantic Factorization in GANs	[[paper]](https://arxiv.org/abs/2202.09649),	[[code]](https://github.com/zhujiapeng/resefa/), Local Face Editing	
* 2022		Iterative facial image inpainting based on an encoder-generator architecture	[[paper]](https://arxiv.org/abs/2101.07036),	[[code]](https://github.com/yahyadogan72/iterative_facial_image_inpainting), Facial Image Inpainting	
* 2022	CtlGAN	CtlGAN: Few-shot Artistic Portraits Generation with Contrastive Transfer Learning	[[paper]](https://arxiv.org/abs/2203.08612), artistic portraits generation	
* 2022		Style Transformer for Image Inversion and Editing	[[paper]](https://arxiv.org/abs/2203.07932),	[[code]](https://github.com/sapphire497/style-transformer), image inversion and editing	
* 2022		High-Fidelity Portrait Editing Via Exploring Differentiable Guided Sketches from the Latent Space	[[paper]](https://ieeexplore.ieee.org/abstract/document/9747428?casa_token=PsGhi63-gxEAAAAA:xxyQ6KY6yYbPhh9FQQZgCzJ8K6GTKgEoCyknP7GEZrTh-VarYZmEHk2kcch4DRLs5pz4Z5yRYg), sketch-guided portrait editing	
* 2022	EXE-GAN	Diverse facial inpainting guided by exemplars	[[paper]](https://arxiv.org/abs/2202.06358), facial inpainting	
* 2022	Panini-Net	Panini-Net: GAN Prior based Degradation-Aware Feature Interpolation for Face Restoration	[[paper]](https://www.aaai.org/AAAI22Papers/AAAI-4252.WangY.pdf),	[[code]](https://github.com/jianzhangcs/panini),  Face Restoration	
* 2022		Expanding the Latent Space of StyleGAN for Real Face Editing	[[paper]](https://arxiv.org/abs/2204.12530), face editing	
* 2022	LELSD	Optimizing Latent Space Directions for Gan-Based Local Image Editing	[[paper]](https://ieeexplore.ieee.org/abstract/document/9747326?casa_token=OPLa6aQp2EYAAAAA:lW3PGF1GUk4OZsYFRH1ebQGu7kBz0yZt1FFLKBENIABEWxrOk0gdnhHxual8QJhCUe_UQ49UnA), Local Image Editing	
* 2022		Towards High-Fidelity Face Self-occlusion Recovery via Multi-view Residual-based GAN Inversion	[[paper]](https://www.aaai.org/AAAI22Papers/AAAI-2208.ChenJ.pdf), Face Self-occlusion Recovery	
* 2022	AE-StyleGAN	AE-StyleGAN: Improved Training of Style-Based Auto-Encoders	[[paper]](https://openaccess.thecvf.com/content/WACV2022/html/Han_AE-StyleGAN_Improved_Training_of_Style-Based_Auto-Encoders_WACV_2022_paper.html), [[code]](https://github.com/phymhan/stylegan2-pytorch)

## Transformer-based:
* 2021	Improving Visual Quality of Image Synthesis by A Token-based Generator with Transformers	[[paper]](https://proceedings.neurips.cc/paper/2021/hash/b056eb1587586b71e2da9acfe4fbd19e-Abstract.html)		
* 2022	PixelFolder	PixelFolder: An Efficient Progressive Pixel Synthesis Network for Image Generation	[[paper]](https://arxiv.org/abs/2204.00833),	[[code]](https://github.com/BlingHe/PixelFolder)	
* 2022	EdiBERT	EdiBERT, a generative model for image editing	[[paper]](https://arxiv.org/abs/2111.15264),	[[code]](http://code/)	
* 2021	GANformer2	Compositional Transformers for Scene Generation	[[paper]](https://proceedings.neurips.cc/paper/2021/hash/4eff0720836a198b6174eecf02cbfdbf-Abstract.html),	[[code]](https://github.com/dorarad/gansformer)	
* 2021	VQGAN	Taming Transformers for High-Resolution Image Synthesis	[[paper]](https://arxiv.org/abs/2012.09841),	[[code]](https://github.com/CompVis/taming-transformers),	[[project]](https://compvis.github.io/taming-transformers/)
					
## video-based generators
* 2022	StyleHEAT	StyleHEAT: One-Shot High-Resolution Editable Talking Face Generation via Pre-trained StyleGAN	[[paper]](https://arxiv.org/abs/2203.04036),	[[code]](https://github.com/FeiiYin/StyleHEAT),	[[project]](https://feiiyin.github.io/StyleHEAT/), video generation
2022	LIA	Latent Image Animator: Learning to Animate Images via Latent Space Navigation	[[paper]](https://arxiv.org/abs/2203.09043), [[project]](https://wyhsirius.github.io/LIA-project/), 	animating images

## 3D generators
* 2022		3D GAN Inversion for Controllable Portrait Image Animation	[[paper]](https://arxiv.org/abs/2203.13441), Portrait image animation and attribute editing	


# Face Morphing Attacks Detection (MAD)
## Single-based MAD


## Differential MAD
* 2020	Deep Face Representations for Differential Morphing Attack Detection	[[paper]](https://arxiv.org/abs/2001.01202)
* 2021	A Double Siamese Framework for Differential Morphing Attack Detection	[[paper]](https://www.mdpi.com/1424-8220/21/10/3466)








# Face De-morphing Methods
* 2022-IJCB		Facial De-morphing: Extracting Component Faces from a Single Morph	GAN	DAD as backbone		[[paper]](https://arxiv.org/abs/2209.02933)
* 2020		Border Control Morphing Attack Detection With a Convolutional Neural Network De-Morphing Approach	AutoEncoder			[[paper]](https://ieeexplore.ieee.org/abstract/document/9091520)
* 2019		FD-GAN: Face De-Morphing Generative Adversarial Network for Restoring Accomplice’s Facial Image	GAN [[paper]](https://ieeexplore.ieee.org/abstract/document/8730323)
* 2018		Face demorphing in the presence of facial appearance variations	[[paper]](https://ieeexplore.ieee.org/abstract/document/8553430?casa_token=WBeRdqDeJNoAAAAA:9-mV0MSfPm95HK-WQdh10JId5-gVMr8BqgFemUK9oLiEA9aLqteeEDlnGsBZIHPmaX-D3pjQcg)
* 2021		Conditional Identity Disentanglement for Differential Face Morph Detection [[paper]](https://arxiv.org/abs/2107.02162)


  
# De-compose Methods
* 2020	DAD	Deep Adversarial Decomposition: A Unified Framework for Separating Superimposed Images	[[code]](https://github.com/jiupinjia/Deep-adversarial-decomposition),	[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Zou_Deep_Adversarial_Decomposition_A_Unified_Framework_for_Separating_Superimposed_Images_CVPR_2020_paper.html),
* [[pathGAN]](https://github.com/He-jerry/PatchGAN)		
* 2017	CycleGAN	Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks	[[code]](https://github.com/junyanz/CycleGAN),	[[project]](https://junyanz.github.io/CycleGAN/),[[paper]](https://arxiv.org/pdf/1703.10593.pdf)	
* 2015	U-Net	U-Net: Convolutional Networks for Biomedical Image Segmentation		[[project]](https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/)	



# others					
* Perceptual loss	2018	lpips:	https://pypi.org/project/lpips/		
		
