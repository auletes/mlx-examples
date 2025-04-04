# MLX Examples

This repo contains a variety of standalone examples using the [MLX
framework](https://github.com/ml-explore/mlx).

The [MNIST](mnist) example is a good starting point to learn how to use MLX.
Some more useful examples are listed below. Check-out [MLX
LM](https://github.com/ml-explore/mlx-lm) for a more fully featured Python
package for LLMs with MLX.

### Text Models 

- [Transformer language model](transformer_lm) training.
- Minimal examples of large scale text generation with [LLaMA](llms/llama),
  [Mistral](llms/mistral), and more in the [LLMs](llms) directory.
- A mixture-of-experts (MoE) language model with [Mixtral 8x7B](llms/mixtral).
- Parameter efficient fine-tuning with [LoRA or QLoRA](lora).
- Text-to-text multi-task Transformers with [T5](t5).
- Bidirectional language understanding with [BERT](bert).

### Image Models 

- Generating images
  - [FLUX](flux)
  - [Stable Diffusion or SDXL](stable_diffusion)
- Image classification using [ResNets on CIFAR-10](cifar).
- Convolutional variational autoencoder [(CVAE) on MNIST](cvae).

### Audio Models

- Speech recognition with [OpenAI's Whisper](whisper).
- Audio compression and generation with [Meta's EnCodec](encodec).
- Music generation with [Meta's MusicGen](musicgen).

### Multimodal models

- Joint text and image embeddings with [CLIP](clip).
- Text generation from image and text inputs with [LLaVA](llava).
- Image segmentation with [Segment Anything (SAM)](segment_anything).

### Other Models 

- Semi-supervised learning on graph-structured data with [GCN](gcn).
- Real NVP [normalizing flow](normalizing_flow) for density estimation and
  sampling.

### Hugging Face

You can directly use or download converted checkpoints from the [MLX
Community](https://huggingface.co/mlx-community) organization on Hugging Face.
We encourage you to join the community and [contribute new
models](https://github.com/ml-explore/mlx-examples/issues/155).

## Contributing 

We are grateful for all of [our
contributors](ACKNOWLEDGMENTS.md#Individual-Contributors). If you contribute
to MLX Examples and wish to be acknowledged, please add your name to the list in your
pull request.

## Citing MLX Examples

The MLX software suite was initially developed with equal contribution by Awni
Hannun, Jagrit Digani, Angelos Katharopoulos, and Ronan Collobert. If you find
MLX Examples useful in your research and wish to cite it, please use the following
BibTex entry:

```
@software{mlx2023,
  author = {Awni Hannun and Jagrit Digani and Angelos Katharopoulos and Ronan Collobert},
  title = {{MLX}: Efficient and flexible machine learning on Apple silicon},
  url = {https://github.com/ml-explore},
  version = {0.0},
  year = {2023},
}
```
