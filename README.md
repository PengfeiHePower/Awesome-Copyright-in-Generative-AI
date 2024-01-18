# Awesome Copyright in Generative AI [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome works in Copyright Protection for Deep Generative Models.

## Part 1. Image generative models. 
Including [Autoencoders](https://arxiv.org/abs/1312.6114), [GAN](https://arxiv.org/abs/1406.2661) and [Diffusion models](https://arxiv.org/abs/2006.11239).
### Source Data Owner Copyright Protection
Protect the copyright of data, and prevent unauthorized usage of these data in generative models.

#### Unrecognizable Examples
Add perturbations to the original data such that model will not learn important information from the protected data.
<details>

<summary> <i>UnGANable: Defending Against GAN-based Face Manipulation</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2210.00957)

&nbsp;&nbsp;&nbsp;Against GAN Inversion; create adversarial examples to maximize the discrepancy between adversarial examples and original samples in the latent space of the generator.

</details>

<details>

<summary> <i>Disrupting Deepfakes: Adversarial Attacks Against Conditional Image Translation Networks and Facial Manipulation Systems</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2003.01279)

&nbsp;&nbsp;&nbsp;Against Image-translation GAN; create adversarial examples for the generator.

</details>

<details>

<summary> <i>Disrupting Image-Translation-Based DeepFake Algorithms with Adversarial Attacks</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://openaccess.thecvf.com/content_WACVW_2020/papers/w4/Yeh_Disrupting_Image-Translation-Based_DeepFake_Algorithms_with_Adversarial_Attacks_WACVW_2020_paper.pdf)

&nbsp;&nbsp;&nbsp;Against DeepNude; defining Nullifying Attack and Distorting Attack. 

</details>

<details>

<summary> <i>Initiative defense against facial manipulation</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16254)

&nbsp;&nbsp;&nbsp;Grey-box and black-box adversarial examples.

</details>

<details>

<summary> <i>Adversarial example does good: Preventing painting imitation from diffusion models via adversarial examples</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2302.04578)

&nbsp;&nbsp;&nbsp;Adversarial examples generated via training loss of Diffusion models.

</details>

<details>

<summary> <i>Raising the cost of malicious ai-powered image editing</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2302.04578)

&nbsp;&nbsp;&nbsp; Encoder attack and Diffusion attack.

</details>

<details>

<summary> <i>Defending against gan-based deepfake attacks via transformation-aware ad- versarial faces</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2006.07421)

&nbsp;&nbsp;&nbsp; Utilize adversarial examples against Deepfake models in training.

</details>

<details>

<summary> <i>Anti-Forgery: Towards a Stealthy and Robust DeepFake Disruption Attack via Adversarial Perceptual-aware Perturbations</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2206.00477)

&nbsp;&nbsp;&nbsp; They observed that adversarial perturbations on the Lab color space are robust to input reconstruction. Therefore, they converted the input from RGB space to the Lab color space and added perceptual-aware adversarial perturbations to the color channel to maintain robustness against input transformations.

</details>

<details>

<summary> <i>Glaze: Protecting Artists from Style Mimicry by Text-to-Image Models</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2302.04222)

&nbsp;&nbsp;&nbsp; The core idea of GLAZE is to guide the diffusion model to learn an alternative target style T that is totally different from the style of protected images.

</details>

<details>

<summary> <i>Mist: Towards improved adversarial examples for diffusion models.</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.12683)

&nbsp;&nbsp;&nbsp; Improve the transferability of adversarial examples by combining different losses.

</details>

<details>

<summary> <i>Anti-dreambooth: Protecting users from personalized text-to-image synthesis.</i> </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.15433)

&nbsp;&nbsp;&nbsp; Against DreamBooth and generate poisons via a bi-level optimization problem.

</details>

<details>

<summary> <i>Towards prompt-robust face privacy protection via adversarial decoupling augmentation framework.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.03980)

&nbsp;&nbsp;&nbsp; Introduces multi-level text-related augmentations for defense stability against various attacker prompts

</details>


#### Watermarks
<details>

<summary> <i>Diffusionshield: A watermark for copyright protection against generative diffusion models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2306.04642)

&nbsp;&nbsp;&nbsp; "...blockwise watermarks, as exemplified in Figure 9, are engineered to convey a greater amount of
information...a joint optimization strategy is leveraged to optimize both the pixel values of watermark patches..."

</details>

<details>

<summary> <i>Generative Watermarking Against Unauthorized Subject-Driven Image Synthesis.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2306.07754)

&nbsp;&nbsp;&nbsp; "...Specifically, we propose GenWatermark, a novel watermark system based on jointly learning a watermark generator and a detector"

</details>

<details>

<summary> <i>How to detect unauthorized data usages in text-to-image diffusion models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2307.03108)

&nbsp;&nbsp;&nbsp; A model-agnoistic watermarking through image warpping transformation.

</details>

<details>

<summary> <i>Ft-shield: A watermark against unauthorized fine-tuning in text-to-image diffusion models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.02401)

&nbsp;&nbsp;&nbsp; A watermarking method against fine-tuning latent diffusion models.

</details>

#### Unlearning

Unlearn copyrighted data from the trained model.

<details>

<summary> <i>Forget-
me-not: Learning to forget in text-to-image diffusion
models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.17591)

</details>

<details>

<summary> <i>Data redaction from pre-trained gans.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2206.14389)

</details>

<details>

<summary> <i>Ablating concepts in text-to-image dif-
fusion models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.13516)

</details>

<details>

<summary> <i>Erasing Concepts from Diffusion Models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.07345)

</details>

#### Dataset De-duplication

<details>

<summary> <i>On the De-duplication of LAION-2B.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.12733)

</details>

<details>

<summary> <i>Understanding and mitigating copying
in diffusion models.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.20086)

</details>

### Model Copyright Protection
Protect the copyright of trained generative models, and avoid unauthorized usage of models.

#### Parameter-based
Embed  watermark information into the network’s internal weights or structural configurations.
<details>

<summary> <i>Protecting intellectual property of generative adversarial
networks from ambiguity attacks.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2102.04362)

</details>

<details>

<summary> <i>Protecting Intellectual Property of Generative Adversarial Networks from Ambiguity Attack.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2102.04362)

</details>

<details>

<summary> <i>Protecting Intellectual Property of Generative Adversarial Networks from Ambiguity Attack.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2102.04362)

</details>

#### Image-based

Embed watermark information into the images generated by generative models (post-watermark).

<details>

<summary> <i>Generative model watermarking based on
human visual system.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2209.15268)

</details>

<details>

<summary> <i>Supervised gan watermarking for intellectual property protection.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2209.03466)

</details>

<details>

<summary> <i>Supervised gan watermarking for intellectual property protection.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2209.03466)

</details>

<details>

<summary> <i>Responsible Disclosure of Generative Models Using Scalable Fingerprinting.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2012.08726)

</details>

#### Trigger-based

## Part 2. Text generative models.
Specifically on Large Language Models (LLMs).

### Data Copyright Protection

### Model Copyright Protection

## Part 3. Other domains.

### Code generation

### Graph generation

### Video generation

### Audio generation


