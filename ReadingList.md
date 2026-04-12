
### Reading List

paper lists:

https://github.com/AspirinCode/papers-for-molecular-design-using-DL 

https://github.com/amorehead/awesome-molecular-generation 

https://github.com/lmqfly/Geometry-Deep-Learning-for-Drug-Discovery?tab=readme-ov-file#molecular-design

https://github.com/Peldom/papers_for_protein_design_using_DL?tab=readme-ov-file#2-model-based-design

#### Diffusion

Lilian’s blog: https://lilianweng.github.io/posts/2021-07-11-diffusion-models/

Yang Song’s blog: https://yang-song.net/blog/2021/score/

Sohl-Dickstein, Jascha, et al. "Deep unsupervised learning using nonequilibrium thermodynamics." International conference on machine learning. PMLR, 2015.

Song, Yang, and Stefano Ermon. "Generative modeling by estimating gradients of the data distribution." Advances in neural information processing systems 32 (2019).

Ho, Jonathan, Ajay Jain, and Pieter Abbeel. "Denoising diffusion probabilistic models." Advances in neural information processing systems 33 (2020): 6840-6851.

Ho, Jonathan, and Tim Salimans. "Classifier-free diffusion guidance." arXiv preprint arXiv:2207.12598 (2022).

Dhariwal, Prafulla, and Alexander Nichol. "Diffusion models beat gans on image synthesis." Advances in neural information processing systems 34 (2021): 8780-8794.

#### Flow Models

tutorial: https://neurips.cc/virtual/2024/tutorial/99531

Rezende, Danilo, and Shakir Mohamed. "Variational inference with normalizing flows." International conference on machine learning. PMLR, 2015.

Chen, Ricky TQ, et al. "Neural ordinary differential equations." Advances in neural information processing systems 31 (2018).

Lipman, Yaron, et al. "Flow Matching for Generative Modeling." The Eleventh International Conference on Learning Representations.

Liu, Xingchao, and Chengyue Gong. "Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow." The Eleventh International Conference on Learning Representations.

Chen, Ricky TQ, and Yaron Lipman. "Riemannian flow matching on general geometries." arXiv preprint arXiv:2302.03660 (2023).

Gat, Itai, et al. "Discrete Flow Matching." The Thirty-eighth Annual Conference on Neural Information Processing Systems.

Stark, Hannes, et al. "Dirichlet Flow Matching with Applications to DNA Sequence Design." Forty-first International Conference on Machine Learning.

Campbell, Andrew, et al. "Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design." Forty-first International Conference on Machine Learning.

#### Latent Diffusion / VAE

Lilian’s blog https://lilianweng.github.io/posts/2018-08-12-vae/

tutorial: https://nips.cc/virtual/2023/tutorial/73957

Rombach, Robin, et al. "High-resolution image synthesis with latent diffusion models." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022.

Kingma, Diederik P. "Auto-encoding variational bayes." arXiv preprint arXiv:1312.6114 (2013).

Van Den Oord, Aaron, and Oriol Vinyals. "Neural discrete representation learning." Advances in neural information processing systems 30 (2017).

Razavi, Ali, Aaron Van den Oord, and Oriol Vinyals. "Generating diverse high-fidelity images with vq-vae-2." Advances in neural information processing systems 32 (2019).

#### Language model in biomedicine

**lecture1: Protein and Genome Language Models**
- Simon E, Zou J. InterPLM: discovering interpretable features in protein language models via sparse autoencoders[J]. Nature methods, 2025, 22(10): 2107-2117.
- Su J, Han C, Zhou Y, et al. Saprot: Protein language modeling with structure-aware vocabulary[J]. BioRxiv, 2023: 2023.10. 01.560349.
- Wang, Xinyou, et al. "Dplm-2: A multimodal diffusion protein language model." *arXiv preprint arXiv:2410.13782* (2024).
- Brixi G, Durrant M G, Ku J, et al. Genome modeling and design across all domains of life with Evo 2[J]. BioRxiv, 2025: 2025.02. 18.638918.


**lecture2: Scientific LLMs**
- Schwaller P, Probst D, Vaucher A C, et al. Mapping the space of chemical reactions using attention-based neural networks[J]. Nature machine intelligence, 2021, 3(2): 144-152.
- Ross J, Belgodere B, Chenthamarakshan V, et al. Large-scale chemical language representations capture molecular structure and properties[J]. Nature Machine Intelligence, 2022, 4(12): 1256-1264.
- Chang J, Ye J C. Bidirectional generation of structure and properties through a single molecular foundation model[J]. Nature Communications, 2024, 15(1): 2323.
- Edwards C, Han C, Lee G, et al. mCLM: A Modular Chemical Language Model that Generates Functional and Makeable Molecules[J]. arXiv preprint arXiv:2505.12565, 2025.

#### Molecule Generation

**lecture3: 2d & 3d generation**
- Vignac, Clement, et al. "DiGress: Discrete Denoising diffusion for graph generation." *The Eleventh International Conference on Learning Representations*.
- Xu, Minkai, et al. "GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation." *International Conference on Learning Representations*.
- Hoogeboom, Emiel, et al. "Equivariant diffusion for molecule generation in 3d." *International conference on machine learning*. PMLR, 2022.
- Eijkelboom, Floor, et al. "Variational Flow Matching for Graph Generation." *arXiv preprint arXiv:2406.04843* (2024).

**lecture4: Structure-based drug design**
- Li, Jiahan, et al. "Full-Atom Peptide Design based on Multi-modal Flow Matching." Forty-first International Conference on Machine Learning.
- Peng, Xingang, et al. "Pocket2mol: Efficient molecular sampling based on 3d protein pockets." International Conference on Machine Learning. PMLR, 2022.
- Guan, Jiaqi, et al. "3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction." The Eleventh International Conference on Learning Representations.
- Corso, Gabriele, et al. "DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking." The Eleventh International Conference on Learning Representations.

#### Protein Generation

**lecture5: Protein Folding**
- Abramson, Josh, et al. "Accurate structure prediction of biomolecular interactions with AlphaFold 3." *Nature* (2024): 1-3.
- Lin Z, Akin H, Rao R, et al. Language models of protein sequences at the scale of evolution enable accurate structure prediction[J]. BioRxiv, 2022, 2022: 500902.
- Passaro S, Corso G, Wohlwend J, et al. Boltz-2: Towards accurate and efficient binding affinity prediction[J]. BioRxiv, 2025.
- Wang Y, Lu J, Jaitly N, et al. Simplefold: Folding proteins is simpler than you think[J]. arXiv preprint arXiv:2509.18480, 2025.

**lecture6: Structure Design**
- Yim, Jason, et al. "Fast protein backbone generation with SE (3) flow matching." *arXiv preprint arXiv:2310.05297* (2023).
- Ahern W, Yim J, Tischer D, et al. Atom-level enzyme active site scaffolding using RFdiffusion2[J]. Nature Methods, 2025: 1-10.
- Geffner T, Didi K, Zhang Z, et al. Proteina: Scaling flow-based protein structure generative models[J]. arXiv preprint arXiv:2503.00710, 2025.
- Lin H, Zhang O, Zhao H, et al. Ppflow: Target-aware peptide design with torsional flow matching[J]. arXiv preprint arXiv:2405.06642, 2024.


**lecture7: Co-design**
- Geffner T, Didi K, Cao Z, et al. La-proteina: Atomistic protein generation via partially latent flow matching[J]. arXiv preprint arXiv:2507.09466, 2025.
- Cho Y, Pacesa M, Zhang Z, et al. Boltzdesign1: Inverting all-atom structure prediction model for generalized biomolecular binder design[J]. BioRxiv, 2025: 2025.04. 06.647261.
- Li J, Cheng C, Wu Z, et al. Full-atom peptide design based on multi-modal flow matching[J]. arXiv preprint arXiv:2406.00735, 2024.
- Qu W, Ma Y, Ye F, et al. SeedProteo: Accurate De Novo All-Atom Design of Protein Binders[J]. arXiv preprint arXiv:2512.24192, 2025.

#### Agentic AI and RL-finetuning

**lecture8: RL-finetuing**
- Park, Ryan, et al. "Improving Inverse Folding for Peptide Design with Diversity-regularized Direct Preference Optimization." arXiv preprint arXiv:2410.19471 (2024).
- Wang, Chenyu, et al. "Fine-Tuning Discrete Diffusion Models via Reward Optimization with Applications to DNA and Protein Design." NeurIPS 2024 Workshop on AI for New Drug Modalities.
- Zhou, Xiangxin, et al. "Antigen-Specific Antibody Design via Direct Energy-based Preference Optimization." arXiv preprint arXiv:2403.16576 (2024).
- Ren, Milong, ZaiKai He, and Haicang Zhang. "Multi-objective antibody design with constrained preference optimization." *The Thirteenth International Conference on Learning Representations*. 2025.

**lecture9: LLM agent for autonomous science discovery**
- Swanson, Kyle, et al. "The Virtual Lab of AI agents designs new SARS-CoV-2 nanobodies." *Nature* 646.8085 (2025): 716-723.
- Ghafarollahi, Alireza, and Markus J. Buehler. "Sparks: Multi-agent artificial intelligence model discovers protein design principles." *arXiv preprint arXiv:2504.19017* (2025).
- Novikov, Alexander, et al. "Alphaevolve: A coding agent for scientific and algorithmic discovery." *arXiv preprint arXiv:2506.13131* (2025).
- Huang, Kexin, et al. "Biomni: A general-purpose biomedical ai agent." *biorxiv* (2025).

