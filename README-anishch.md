## Projects

### 3D MRI Reconstruction with Implicit Neural Representations
- Built coordinate-based neural fields mapping continuous (x, y, z) locations to grayscale MRI intensity values
- Implemented NeRF-style architectures including GA-Planes and MiniTriplane, comparing feature-grid interpolation against MLP-only INRs
- Applied FiLM-based conditioning using per-slice image encoders and analyzed conditioning collapse and representation averaging
- Designed training regimes using full-slice supervision, curriculum learning, and stratified sampling
- Evaluated reconstruction quality using SSIM and PSNR, studying perceptual vs pixel-level convergence behavior
- Adapted diffusion and flow-matching objectives (HyperDiffusion-style) to generate and model neural field parameters rather than data  
**Tech:** PyTorch, NeRF, GA-Planes, MiniTriplane, FiLM, Diffusion, Flow Matching, SSIM, PSNR

---

### Bayesian Structure Learning with Deep Generative Models
- Integrated NO-TEARS acyclicity constraints into neural and flow-based structure learning pipelines
- Investigated GNN-based and continuous optimization approaches to DAG discovery
- Analyzed identifiability limits, failure modes, and inductive biases in learned causal graphs
- Implemented experimental benchmarks for structure recovery under noise and latent confounding  
**Tech:** GNNs, DAG Learning, NO-TEARS, Flow Matching, Optimization

---

### Morphology-Aware Tokenization and Linguistic Modeling
- Designed a tokenizer based on lemma- and edit-level transformations rather than subword frequency heuristics
- Built cross-lingual affix tables and POS-aware alignment mechanisms using dynamic programming
- Evaluated tokenization quality across typologically diverse languages using precision/recall metrics
- Studied tradeoffs between compression, interpretability, and generalization in multilingual tokenization  
**Tech:** NLP, Linguistic Typology, Dynamic Programming, Python

---

### Video Steganography with 3D Convolutional Networks (V-HiDDeN)
- Extended image-based steganography models to video using spatiotemporal 3D convolutions
- Implemented SparseHidden and InterspersedHiDDeN variants to improve robustness under compression and noise
- Split ownership across encoding, perturbation, and decoding components within a multi-person research project
- Evaluated robustness under temporal distortions and adversarial perturbations  
**Tech:** PyTorch, 3D CNNs, Video Models

---

### GUI Navigation with Vision-Language Models (CS231N)
- Built an LLM-driven agent to navigate desktop GUIs using screen coordinates and visual context
- Curated a dataset of selectable UI elements annotated with bounding boxes, labels, and action targets
- Mapped natural language instructions to action sequences (click, scroll, type) via coordinate-based supervision
- Executed actions on live desktop applications using PyAutoGUI, closing the perception–action loop
- Analyzed failure modes related to layout shifts, latency, and visual ambiguity  
**Tech:** Vision-Language Models, LLMs, PyAutoGUI, Computer Vision, Python
