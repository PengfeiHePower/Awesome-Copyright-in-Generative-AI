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

<details>

<summary> <i>The Stable Signature: Rooting Watermarks in Latent Diffusion Models
.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.15435)

</details>

<details>

<summary> <i>Artificial Fingerprinting for Generative Models: Rooting Deepfake Attribution in Training Data
.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2007.08457)

</details>

<details>

<summary> <i>A recipe for watermarking diffusion models.
.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2303.10137)

</details>

<details>

<summary> <i>Tree-ring watermarks: Fingerprints for diffusion
images that are invisible and robust.
.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.20030)

</details>

<details>

<summary> <i>Attributing image
generative models using latent fingerprints.
</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2304.09752)

</details>

#### Trigger-based
Secretly incorporates a trigger to the protected model
such that an image with copyright information will be
generated once the trigger is activated

<details>

<summary> <i>Protecting intellectual property of generative adversarial
networks from ambiguity attacks.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2102.04362)

</details>

<details>

<summary> <i>A novel model watermarking for protecting
generative adversarial network.</i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://www.sciencedirect.com/science/article/pii/S0167404823000123)

</details>

<details>

<summary> <i>Watermarking diffusion model. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.12502)

</details>

<details>

<summary> <i>Protecting the
intellectual property of diffusion models by the water-
mark diffusion process. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2306.03436)

</details>


## Part 2. Text generative models.
Specifically on Large Language Models (LLMs).

### Data Copyright Protection
<details>

<summary> <i>Deduplicating Training Data Makes Language Models Better. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2107.06499)

</details>

<details>

<summary> <i>Deduplicating
training data mitigates privacy risks in language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2202.06539)

</details>

<details>

<summary> <i>How to protect copyright
data in optimization of large language models? </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2308.12247)

</details>

<details>

<summary> <i>Preventing Verbatim Memorization in Language Models Gives a False Sense of Privacy. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://aclanthology.org/2023.inlg-main.3/)

</details>

<details>

<summary> <i>Preserving Privacy Through Dememorization: An Unlearning Technique For Mitigating Memorization Risks In Language Models
. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://aclanthology.org/2023.emnlp-main.265/)

</details>

<details>

<summary> <i>Who’s harry potter? approximate unlearning in llms. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.02238)

</details>

<details>

<summary> <i>Unlearn What You Want to Forget: Efficient Unlearning for LLMs. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://aclanthology.org/2023.emnlp-main.738.pdf)

</details>

<details>

<summary> <i>Large language model unlearning. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/pdf/2310.10683.pdf)

</details>

<details>

<summary> <i>In-context unlearning: Language models as few shot unlearners. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.07579)

</details>

<details>

<summary> <i>In-context unlearning: Language models as few shot unlearners. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.07579)

</details>

### Model Copyright Protection

<details>

<summary> <i>A Watermark for Large Language Models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2301.10226)

</details>

<details>

<summary> <i>Watermarking text generated by black-box language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/pdf/2305.08883.pdf)

</details>

<details>

<summary> <i>Undetectable
watermarks for language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/pdf/2306.09194.pdf)

</details>

<details>

<summary> <i>Advancing beyond identification: Multi-bit watermark for language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2308.00221)

</details>

<details>

<summary> <i>On the reliability of watermarks for
large language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2306.04634)

</details>

<details>

<summary> <i>Provable
robust watermarking for ai-generated text. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2306.17439)

</details>

<details>

<summary> <i>A robust semantics-based watermark for large
language model against paraphrasing. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2311.08721)

</details>

<details>

<summary> <i>Watermarking Conditional Text Generation for AI Detection: Unveiling Challenges and a Semantic-Aware Watermark Remedy. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2307.13808)

</details>

<details>

<summary> <i>A private watermark for large language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2307.16230)

</details>

<details>

<summary> <i>Robust distortion-free watermarks for language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2307.15593)

</details>

<details>

<summary> <i>Unbiased watermark for large language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/pdf/2310.10669.pdf)

</details>

<details>

<summary> <i>Embarrassingly Simple Text Watermarks. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.08920?ref=upstract.com#:~:text=We%20propose%20Easymark%2C%20a%20family,distinguished%20from%20human%2Dwritten%20texts.)

</details>

<details>

<summary> <i>Necessary and sufficient watermark for large language
models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.00833)

</details>

<details>

<summary> <i>Model leeching: An extraction attack targeting llms. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://ui.adsabs.harvard.edu/abs/2023arXiv230910544B/abstract)

</details>

<details>

<summary> <i>Are you copying my
model? protecting the copyright of large language mod-
els for eaas via backdoor watermark. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.10036)

</details>

<details>

<summary> <i>Fate-llm: A industrial grade federated learning
framework for large language models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2310.10049)

</details>

<details>

<summary> <i>Cater: Intellectual property protection on text generation
apis via conditional watermarks. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2209.08773)

</details>

## Part 3. Other domains.

### Code generation

<details>

<summary> <i>StarCoder: may the source be with you! </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.06161)

</details>

<details>

<summary> <i>Whygen: explaining ml-powered code
generation by referring to training examples. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2204.07940)

</details>

<details>

<summary> <i>Who wrote this code? watermarking
for code generation. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.15060)

</details>

<details>

<summary> <i>Unlearnable examples: Protect-
ing open-source software from unauthorized neural code
learning. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://ksiresearch.org/seke/seke22paper/paper066.pdf)

</details>

<details>

<summary> <i>The "code'' of Ethics:A Holistic Audit of AI Code Generators. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2305.12747)

</details>


### Audio generation

<details>

<summary> <i>WavMark: Watermarking for Audio Generation. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2308.12770)

</details>

<details>

<summary> <i>Invisible Watermarking for Audio Generation Diffusion Models. </i>  </summary>

&nbsp;&nbsp;&nbsp;[[paper]](https://arxiv.org/abs/2309.13166)

</details>




