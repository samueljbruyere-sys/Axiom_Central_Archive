# Mixture of Contexts for Long Video Generation

“Minute-long context memory with short-video cost”

[Shengqu Cai](https://primecai.github.io/)1,* [Ceyuan Yang](https://ceyuan.me/)2,† [Lvmin Zhang](https://lllyasviel.github.io/lvmin_zhang/)1 [Yuwei Guo](https://guoyww.github.io/)4 [Junfei Xiao](https://lambert-x.github.io/)3 [Ziyan Yang](https://ziyanyang.github.io/)2 [Yinghao Xu](https://justimyhxu.github.io/)1 [Zhenheng Yang](https://zhenheny.github.io/)5 [Alan Yuille](https://www.cs.jhu.edu/~ayuille/)3 [Leonidas Guibas](https://profiles.stanford.edu/leonidas-guibas)1 [Maneesh Agrawala](https://graphics.stanford.edu/~maneesh/)1 [Lu Jiang](http://www.lujiang.info/)2 [Gordon Wetzstein](https://stanford.edu/~gordonwz/)1

1Stanford University 2ByteDance Seed 3Johns Hopkins University 4CUHK 5ByteDance

*Work done at ByteDance Seed   †Corresponding Author

[📄Research Paper](http://arxiv.org/abs/2508.21058)

Learnable Sparse Attention Routing

A non-parametric yet learnable router selects informative history chunks to calculate attention. The routing is implicitly differentiable and optimized end-to-end from large-scale long video data.

Multi-shot Long Video Generation

For 8-shot, minute-long videos (~180k tokens), MoC prunes ≈ 85 % of token pairs and cuts FLOPs by 7× while delivering minute-long context coherence.

_Some prompts are from Twitter artworks._

Single-shot Short Video Generation

On 8-second, 320×192 clips (~6.5k tokens), MoC routing prunes ≈ 83 % of token pairs, while maintaining or even improving video quality.

BibTeX

Copy

@inproceedings{cai2025moc,
        title={Mixture of Contexts for Long Video Generation},
        author={Cai, Shengqu and Yang, Ceyuan and Zhang, Lvmin and Guo, Yuwei and Xiao, Junfei and Yang, Ziyan and Xu, Yinghao and Yang, Zhenheng and Yuille, Alan and Guibas, Leonidas and Agrawala, Maneesh and Jiang, Lu and Wetzstein, Gordon},
        year={2025},
        booktitle={arXiv},
      }