# Face Morphing
This repository collects papers in the field of face morphing attacks and defense, including surveys, databases, generation models and detection methods.

Keep updating!!!

# Survey			

## 3D Morphing
* 2022		3D Face Morphing Attacks: Generation, Vulnerability and Detection	[[paper]](https://arxiv.org/abs/2201.03454)

## GAN
		
* 2022	State-of-the-Art in the Architecture, Methods and Applications of StyleGAN	[[paper]](https://arxiv.org/abs/2202.14020)
* 2021	Review on Generative Adversarial Network in Computer Vision: Methods and Metrics	[[paper]](https://ieeexplore.ieee.org/abstract/document/9696113)
* 2021	Review on Generative Adversarial Networks: Focusing on Computer Vision and Its Applications	[[paper]](https://www.mdpi.com/2079-9292/10/10/1216)
* 2022	GAN Inversion: A Survey	[[paper]](https://github.com/weihaox/awesome-gan-inversion)
		
## Transformer		
* 2022	Recent Advances in Vision Transformer: A Survey and Outlook of Recent Work	[[paper]](https://arxiv.org/abs/2203.01536)
* 2022	Three things everyone should know about Vision Transformers	[[paper]](https://arxiv.org/abs/2203.09795)
* 2022	Transformers in computational visual media: A survey	[[paper]](https://link.springer.com/article/10.1007/s41095-021-0247-3)

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
					
# others					
* Perceptual loss	2018	lpips:	https://pypi.org/project/lpips/		
		
