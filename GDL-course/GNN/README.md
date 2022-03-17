## General Bluprint for Learning on Graphs
![image](https://github.com/Chris33Hou/Geometric-Deep-Learning/blob/main/GDL-course/GNN/learning-on-graph.png)

## The Three "Flavours" of GNN Layers
![image](https://github.com/Chris33Hou/Geometric-Deep-Learning/blob/main/GDL-course/GNN/three-flavour.png)

* Convolutional GNN:
  * ChebyNet(Defferrardet al., NeurIPS’16)
  * GCN (Kipf& Welling, ICLR’17)
  * SGC (Wu et al., ICML’19)

* Attentional GNN:
  * MoNet(Monti et al., CVPR’17)
  * GAT (Veličkovićet al., ICLR’18)
  * GATv2 (Brody et al., 2021)

* Message-passing GNN:
  * Interaction Nets (Battaglia et al., NeurIPS’16)
  * MPNN (Gilmer et al., ICML’17)
  * GraphNets(Battaglia et al., 2018)


## Latent Graph Inference
* Option 1: Assume no edges [Deep Sets](https://arxiv.org/abs/1703.06114)
* Option 2: Assume all edges [Transformers are Graph Neural Networks (Joshi ,The Gradient; 2020)](https://thegradient.pub/transformers-are-graph-neural-networks/)
* Option 3: Infer edges to use 
  * 3a Variational  
    
    [Neural Relational Inference (Kipf, Fetaya, et al., ICML’18)](https://arxiv.org/abs/1802.04687): VAEs, Probabilistic
    
  * 3b No Learning
    
    [Dynamic Graph CNN (Wang et al., ACM TOG 2018)](https://arxiv.org/abs/1801.07829)
  * 3c Reinforcement Learning
    
    [Differentiable Graph Module (Kaziet al., 2020)](https://arxiv.org/abs/2002.04999)
  * 3d Supervised Learning
    
    [Pointer Graph Networks (Veličkovićet al., NeurIPS’20)](https://arxiv.org/abs/2006.06380)
    
    
## Power of GNNs & Graph Isomorphism Test
* Weisfeiler-Lehman Test (1-WL)
* Fixing "failure cases" of 1-WL yields classes of higher-order GNNs
  * Modifying features: 
  
    Augment nodes with randomisedfeatures (Sato et al., SDM’21)
    
    RP-GNN (Murphy et al., ICML’19)
    
    P-GNN (You et al., ICML’19)
    
    countinteresting subgraphs (Bouritsaset al., 2020)
  * Modifying Message passing rule:  DGN (Beainiet al., ICML’20)
  * Modifying graph sturcture: 1-2-3-GNNs (Morris et al., AAAI’19)
* Empirically powerfule combination of aggregators: PNA paper (Corso, Cavalleriet al., NeurIPS’20)








