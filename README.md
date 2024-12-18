# Measuring Patch Importance in ViT's (Vanilla & Attention Rollout)
Developed methods to analyze patch importance in Vision Transformers (ViTs) by leveraging attention scores of the [CLS] token across attention matrices in multi-head self-attention (MHSA) blocks. Visualized the distribution of top-k patch tokens with respect to the [CLS] token, highlighting critical regions contributing to model predictions. 

Additionally, implemented Attention Rollout to recursively propagate attention scores across layers, producing interpretable visualizations of information flow in self-attention mechanisms. This approach enhances understanding of attention-based models and their decision-making processes.
