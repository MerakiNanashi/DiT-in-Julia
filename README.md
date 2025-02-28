## Diffusion Transformer (DiT) in Julia
This repository offers an implementation of the Diffusion Transformer (DiT) model entirely in Julia, utilizing the [Flux.jl](https://fluxml.ai/Flux.jl/stable/) machine learning library. DiT is a novel class of diffusion models that replaces the traditional U-Net backbone with a transformer architecture, aiming to enhance performance and scalability in image generation tasks.

# Overview
Diffusion models have emerged as powerful generative models, particularly in image and video synthesis. The Diffusion Transformer (DiT) architecture builds upon this foundation by integrating transformer-based backbones into the diffusion process. This approach has demonstrated improved scalability and performance compared to conventional U-Net-based models.

# Implementation Details
The implementation is developed entirely in Julia, leveraging [Flux.jl](https://fluxml.ai/Flux.jl/stable/) for building and training the transformer-based DiT model. Flux.jl provides a flexible and efficient framework for machine learning tasks in Julia.

# Getting Started
Prerequisites
- Julia 1.6 or later
- Flux.jl
  
# Installation
To install the required package, execute the following command in the Julia REPL:

```julia
using Pkg
Pkg.add("Flux")
```

# Usage
Detailed usage instructions and examples are available in the examples directory. These examples demonstrate how to train and evaluate the DiT model on various datasets.

# Acknowledgments
This implementation draws inspiration from the original work on Diffusion Transformers by William Peebles and Saining Xie. Their research paper, ["Scalable Diffusion Models with Transformers"](https://arxiv.org/abs/2212.09748) provides the foundational concepts and methodologies upon which this project is built.

Gratitude is extended to the developers of [Flux.jl](https://fluxml.ai/Flux.jl/stable/) for their comprehensive Julia machine learning library, which significantly facilitated this project.

Additionally, acknowledgment is given to the [facebookresearch/DiT repository](https://github.com/facebookresearch/DiT/tree/main?tab=readme-ov-file) for providing the official PyTorch implementation of DiT, serving as a valuable reference during the development of this Julia version.

# References
- Peebles, W., & Xie, S. (2022). ["Scalable Diffusion Models with Transformers"](https://arxiv.org/abs/2212.09748)
- [Flux.jl](https://fluxml.ai/Flux.jl/stable/)
- [facebookresearch/DiT GitHub Repository](https://github.com/facebookresearch/DiT/tree/main?tab=readme-ov-file)

For further information and resources, please refer to the above references.

# License
MIT License. See [License]().
