# Paper-Writing-Sentence
Recording some elegant sentences of writing.

### Describe the issues
- While it is nearly effortless for humans to quickly assess the perceptual similarity between two images, the underlying processes are thought to be quite complex.
- 


### Describe the key point
- In stark contrast, BIQA relies preferentially on distortion-sensitive features to quantify the perceptual quality of images of various semantic content.
- From extensive experimental results, we arrive at a positive answer to the highlighted question: BIQA can indeed benefit from both scene classification and distortion type identification.
- Our method differs significantly from theirs [62] both conceptually and computationally.
- Our results suggest that perceptual similarity is an emergent property shared across deep visual representations.


### Describe what we do
- In this paper, we **go beyond** the conventional paradigms by exploring the rich visual language prior encapsulated in Contrastive Language-Image Pre-training (CLIP) models for assessing both the quality perception (look) and abstract perception (feel) of images without explicit taskspecific training.
- Inspired by the appealing property of CLIP, we hypothesize that CLIP could have captured the relationship between human language and visual perception for image assessment.
- We begin our exploration by delving into the selection of prompts so that potential vagueness due to linguistic ambiguity can be minimized.
- We systematically evaluate deep features across different architectures and tasks and compare them with classic metrics.

### Describe the experiment results
- As shown in Table 1, without the need of hand-crafted features, CLIP-IQA is **comparable** to BRISQUE and surpasses all other non-learning methods on all three benchmarks. In addition, even without task-specific training, CLIP-IQA outperforms CNNIQA, which requires training with annotations. The surprisingly good performance of CLIP-IQA verifies its potential in the task of NR-IQA.



## ScalableViT: Rethinking the Context-oriented Generalization of Vision Transformer
### Sentences
- To mitigate this issue, we propose ...
- XXX achieves state-of-the-art performance on XXX
- achieved comparable performance against their CNN counterparts because of the global receptive field
- to compensate (补偿) for ...
- It may attribute to ...
- The IWSA establishes information connections by re-merging independent value tokens and aggregating spatial information from adjacent windows.
- To achieve a more efficient backbone for general vision tasks, we adopt ...
- XXX instead of XXX
- Then, these initial tokens will **pass through** four stages which contain a series of Transformer blocks (描述整体结构，pass through)
- can be calculated as:
- XXXX are reported in Table
- ScalableViT-S with a two-layer head outperforms comparable models (1.4% better than Twins-SVT-S, and 1.8% better than Swin-T) (描述实验结果)
- Additionally, our ScalableViT outperforms the EfficientNet by 0.2%, 0.5%, and 0.4% under three magnitude receptively. (描述实验结果)
- Compared with XXXX, our XXX (Compared with the popular Swin and Twins Transformers, our ScalableViT performs 3.5-3.7 APb and 0.5-2.2 APb improvements, respectively.)
- Results demonstrate that
- LIM aims to bring global perception into the single Transformer block (描述一个模块消融的句子)

### Words
- unbinding (解绑), fetch, enhance, alternately, deficiencies (不足之处), entail (蕴含 v.), unaffordable, incline to (倾向于)
- simultaneously (同时), elastic (灵活的), redundant (冗余的),  Consequently (所以),  retain (保留 v.), barrier, confine (局限 v.)
- merit (优点 n.), migrate (迁移 v.), devise (设计 v.), vital (重要的 adj.), Notably (尤其 adv.), ascribe (归咎于 v.), integrated (整合的 adj.)
- implicit (隐含的 adj.), employ, exceed (超出 v.)

### Conjunction
- Furthermore, Moreover
- By XXXX, ...
- Subsequently (随后)
- Additionally

## Adaptive Patch Exiting for Scalable Single Image Super-Resolution
### Sentences
- we present XXXXX
- Inspired by the fact that XXXX
- Super-resolution aims to recover XXXX
- However, they rely on the pixel-wise sparse convolution, which is not hardware-friendly and achieves limited practical speedup
- the trade-off between performance and efficiency is still **under-explored** to the best of our knowledge.
- All the layers share the same regressor
- As for the efficiency of APE, Table 2 shows the XXXX
- Our method adds a lightweight regressor whose FLOPs is negligible (微不足道的 adj.).

### Words
- enable, cascading (级联 v.), layer-wise (逐层 adj.),  saturated (饱和的 adj.), optimal (最佳 adj.)
- analyze, use, explore, propose, present, build, exploit, design, extend, investigate, train (Related work)


### Conjunction
- To be more specific, 

## Restore Globally, Refine Locally: A Mask-Guided Scheme to Accelerate Super-Resolution Networks
### Sentences
- Instead of developing new SR networks, a recent trend is to reduce the parameter amount and/or FLOPs of existing ones while maintaining their SR capability.
- In this work, we aim to accelerate general SR networks while preserving their SR capability.
- However, handling different areas simply by multiple SR networks with adaptive depths still suffers from significant parameter growth.

### Words
- deploy (部署 v.), essential, incorporate (包含v.), employ (采用 v.)

### Conjunction
- To alleviate this problem
- To this end (为了达到此目的)

## Efficient Long-Range Attention Network for Image Super-resolution
### Sentences
- Recently, transformer-based methods have demonstrated impressive results in various vision tasks, including image super-resolution (SR), by exploiting the self-attention (SA) for feature extraction.
- Extensive experiments demonstrate that ELAN obtains even better results against the transformer-based SR models but with significantly less complexity.
- We therefore aim to build a highly neat and efficient SR model, where the LR to HR image mapping is simply built by stacking local feature extraction operations and SA sequentially.


### Words
- prevalent (流行的 adj.), fragmented (支离破碎的), 

### Conjunction
- Without bells and whistles (没有花里胡哨的)
- Generally speaking (通常来说)

## Metric Learning Based Interactive Modulation for Real-World Super-Resolution
### Sentences
-  Since then, motivated by the promising performance of CNN, several CNN-based SR methods have been proposed.
- Realizing the importance of the network depth, [17] designed a 20-layer network with residual blocks. [49] then combined residual learning and dense connection to extend the network depth to 100 layers.
- Before we delve into the details of the unsupervised degradation estimation module (UDEM), we first present the controllable dimensions for real-world interactive modulation. 

### Words
- complicated (复杂的 adj.), attain (达到 v.), delve into (钻研), explicit (明确的 adj.), corrupted (损坏的 adj.), artifacts are visually (视觉上 adv.) more like noise, 

### Conjunction
- Nevertheless (尽管如此), Concretely (具体地, )


## Blind Super-Resolution With Iterative Kernel Correction
### Sentences
- Our method stems from the observation that artifacts caused by kernel mismatch have regular patterns.
- A straightforward solution is to
- However, accurate estimation of k is impossible. As the inverse problem is ill-posed, there exists multiple candidates of k for a single input.
- The above phenomenon illustrates that the estimation error of k will be significantly magnified by the SR model, resulting in unnatural output images.
- Figure 8 shows the SISR results on real world image from the Historic dataset. For comparison, the A+ [31] and CARN [2] are used as the representative SR methods with bicubic downsampling, and ZSSR [27] is used as the representative blind SR method.
- Although defined as blind SR problem, our method focuses on a limited variety of kernels and noise. But the kernel estimated according to our assumptions can handle most of the real world images.
- The kernel settings are given in Table 1.
- It is worth noting that
- We claim that

### Words
- interference (干涉 n.)


### Conjunction
- For simplicity,


## Unfolding the Alternating Optimization for Blind Super Resolution
### Sentences
- It is a highly ill-posed problem due to this inverse property, and thus has always been a challenging task. (描述任务难度)
- Despite that CARN achieves remarkable results in the context of bicubic downsampling, it suffers severe performance drop when applied to images with unknown blur kernels.
- It can be mathematically expressed an optimization problem: (数学表达公式)
- where the former part is the reconstruction term
- Previous methods decompose this problem into two **sequential** steps:
- where M(·) denotes the function that estimates k from y (数学符号描述)

### Words
- be analytically expressed, 

### Conjunction
- Towards these issues, 


## Blind Image Super-resolution with Elaborate Degradation Modeling on Noise and Kernel
### Sentences


### Words
- rational(合理的 adj.), elaborately(精心地 adv.), explicit(明确的 adj.), concise(简洁的 adj.), substantiated(有根据的 adj.), 



### Conjunction

