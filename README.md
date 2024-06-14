## Neural Distributed Compressor Discovers Binning [arXiv](https://arxiv.org/abs/2310.16961) |  [IEEE Xplore](https://ieeexplore.ieee.org/document/10508220)

- This repo includes a Colab Notebook for the proposed neural distributed compressor, as featured in the [IEEE Journal on Selected Areas in Information Theory (JSAIT)'24](https://ieeexplore.ieee.org/document/10508220).

### TL;DR
As an alternative to the state-of-the-art neural compressors, which be collected under the banner of [nonlinear transform coding (NTC)](https://arxiv.org/abs/2007.03034), our work proposes a more generic learning-based algorithm, which represents the first *unstructured entropy-constrained vector quantizer* that makes use of side information. We demonstrate that our approach succeeds in recovering many-to-one mappings exploiting the side information and as a consequence, is able to learn interpretable *binning* (i.e., many-to-one mappings, groupings) in the source space -- whereas NTC fails!

## Abstract
We consider lossy compression of an information source when the decoder has lossless access to a correlated one. This setup, also known as the Wyner-Ziv problem, is a special case of distributed source coding. To this day, practical approaches for the Wyner-Ziv problem have neither been fully developed nor heavily investigated. We propose a data-driven method based on machine learning that leverages the universal function approximation capability of artificial neural networks. We find that our neural network-based compression scheme, based on variational vector quantization, recovers some principles of the optimum theoretical solution of the Wyner-Ziv setup, such as binning in the source space as well as optimal combination of the quantization index and side information, for exemplary sources. These behaviors emerge although no structure exploiting knowledge of the source distributions was imposed. Binning is a widely used tool in information theoretic proofs and methods, and to our knowledge, this is the first time it has been explicitly observed to emerge from data-driven learning.

## Citation
```bash
@ARTICLE{10508220,
  author={Ozyilkan, Ezgi and Ballé, Johannes and Erkip, Elza},
  journal={IEEE Journal on Selected Areas in Information Theory}, 
  title={Neural Distributed Compressor Discovers Binning}, 
  year={2024},
  volume={5},
  number={},
  pages={246-260},
  keywords={Quantization (signal);Decoding;Transforms;Source coding;Indexes;Image coding;Encoding;Distributed source coding;binning;
  Wyner-Ziv coding;learning;lossy compression;neural networks;rate-distortion theory},
  doi={10.1109/JSAIT.2024.3393429}}

```

### TODOs:
```[tasklist]
- [] Include more visual examples explaining the proposed neural distributed compressor.
- [] Explain the proposed method more in detail.
```
