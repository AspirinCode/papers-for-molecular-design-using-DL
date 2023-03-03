
# List of molecular design using Generative AI and Deep Learning 
![contributing-image](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

related to  **Generative AI** and **Deep Learning** for  **molecular/drug design**.

**Updating ...**  

## Molecular Optimization
[Molecular Optimization](https://github.com/AspirinCode/papers-for-molecular-design-using-DL/blob/main/Molecular_Optimization.md) will welcome ！！！


## Recommendations and References

**List of papers about Proteins Design using Deep Learning**

https://github.com/Peldom/papers_for_protein_design_using_DL

**Awesome Generative AI**

https://github.com/steven2358/awesome-generative-ai

**awesome-molecular-generation**

https://github.com/amorehead/awesome-molecular-generation

**A Survey of Artificial Intelligence in Drug Discovery**  

https://github.com/dengjianyuan/Survey_AI_Drug_Discovery

## Menu

  - [ Reviews](#reviews)

  - [ Datasets and Benchmarks](#Datasets-and-Benchmarks)
    - [Datasets](#Datasets)
    - [Benchmarks](#Benchmarks)

  - [ Drug-likeness and Evaluation metrics](#Drug-likeness-and-Evaluation-metrics)
    - [QED](#QED)
    - [QEPPI](#QEPPI)
    - [SAscore](#SAscore)
    - [RAscore](#RAscore)
    - [Evaluation metrics](#Evaluation-metrics)
  - [Deep Learning-based design](#Deep-Learning-based-design)
    - [RNN-based](#RNN-based)
    - [LSTM-based](#LSTM-based)
    - [Autoregressive-models](#Autoregressive-models)
    - [Transformer-based](#Transformer-based)
    - [VAE-based](#VAE-based)
    - [GAN-based](#GAN-based)
    - [Flow-based](#Flow-based)
    - [Score-Based](#Score-Based)
    - [Energy-based](#Energy-based)
    - [Diffusion-based](#Diffusion-based)
    - [RL-based](#RL-based)
    - [Multi-task DMGs](#Multi-task-DMGs)


  - [Multi-Target based deep molecular generative models](#Multi-Target-based-deep-molecular-generative-models)
  - [Ligand-based deep molecular generative models](#Ligand-based-deep-molecular-generative-models)
  - [Pharmacophore-based deep molecular generative models](#Pharmacophore-based-deep-molecular-generative-models)
  - [Structure-based deep molecular generative models](#Structure-based-deep-molecular-generative-models)

  - [Fragment-based deep molecular generative models](#Fragment-based-deep-molecular-generative-models)
    - [Scaffold-based DMGs](#Scaffold-based-DMGs)
    - [Fragment-based DMGs](#Fragment-based-DMGs)
    - [Motifs-based DMGs](#Motifs-based-DMGs)
    - [Linkers-based DMGs](#Linkers-based-DMGs)

## Reviews

* **Open data and algorithms for open science in AI-driven molecular informatics**[2023]  
[[Paper]](https://doi.org/10.1016/j.sbi.2023.102542)

* **Structure-based drug design with geometric deep learning**[2023]  
[[Paper]](https://doi.org/10.1016/j.sbi.2023.102548)

* **MolGenSurvey: A Systematic Survey in Machine Learning Models for Molecule Design**[2022]  
[[Paper]](https://arxiv.org/abs/2203.14500)

* **Structure-based drug discovery with deep learning**[2022]  
[[Paper]](https://arxiv.org/abs/2212.13295)

* **Generative models for molecular discovery: Recent advances and challenges**[2022]  
[[Paper]](https://doi.org/10.1002/wcms.1608)

* **Generative machine learning for de novo drug discovery: A systematic review**[2022]  
[[Paper]](https://doi.org/10.1016/j.compbiomed.2022.105403)

* **Docking-based generative approaches in the search for new drug candidates**[2022]  
[[Paper]](https://doi.org/10.1016/j.drudis.2022.103439)

* **Advances and Challenges in De Novo Drug Design Using Three-Dimensional Deep Generative Models**[2022]  
[[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00042)

* **Deep learning to catalyze inverse molecular design**[2022]  
[[Paper]](https://doi.org/10.1016/j.cej.2022.136669)

* **AI in 3D compound design**[2022]  
[[Paper]](https://doi.org/10.1016/j.sbi.2021.102326)

* **Deep learning approaches for de novo drug design: An overview**[2021]  
[[Paper]](https://doi.org/10.1016/j.sbi.2021.10.001)

* **Generative chemistry: drug discovery with deep learning generative models**[2021]  
[[Paper]](https://link.springer.com/article/10.1007/s00894-021-04674-8)

* **Generative Deep Learning for Targeted Compound Design**[2021]  
[[Paper]](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01496)

* **Generative Models for De Novo Drug Design**[2021]  
[[Paper]](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c00927)

* **Molecular design in drug discovery: a comprehensive review of deep generative models**[2021]  
[[Paper]](https://doi.org/10.1093/bib/bbab344)

* **De novo molecular design and generative models**[2021]  
[[Paper]](https://doi.org/10.1016/j.drudis.2021.05.019)

* **Deep learning for molecular design—a review of the state of the art**[2019]  
[[Paper]](https://pubs.rsc.org/en/content/articlelanding/2019/me/c9me00039a)

* **Inverse molecular design using machine learning: Generative models for matter engineering**[2018]  
[[Paper]](https://www.science.org/doi/10.1126/science.aat2663)

## Datasets and Benchmarks

### Datasets

**DrugBank**

https://go.drugbank.com/

**ZINC**

https://zinc15.docking.org/
https://zinc20.docking.org/

**PubChem**

https://pubchem.ncbi.nlm.nih.gov/

**ChEMBL**

https://www.ebi.ac.uk/chembl/

**GDB Databases**

https://gdb.unibe.ch/downloads/

**QM Dataset**

http://quantum-machine.org/datasets/

**ChemSpider**

http://www.chemspider.com/

**COCONUT**  
Collection of Open Natural Products database

https://coconut.naturalproducts.net/

### Benchmarks

**Molecular Sets (MOSES): A benchmarking platform for molecular generation models**

https://github.com/molecularsets/moses


**GuacaMol: Benchmarking Models for de Novo Molecular Design**

https://github.com/BenevolentAI/guacamol


## Drug-likeness and Evaluation metrics

**Drug-likeness** may be defined as a complex balance of various molecular properties and structure features which determine whether particular molecule is similar to the known drugs. These properties, mainly hydrophobicity, electronic distribution, hydrogen bonding characteristics, molecule size and flexibility and of course presence of various pharmacophoric features influence the behavior of molecule in a living organism, including bioavailability, transport properties, affinity to proteins, reactivity, toxicity, metabolic stability and many others.

https://github.com/AspirinCode/DrugAI_Drug-Likeness

### QED
quantitative estimation of drug-likeness

Bickerton, G., Paolini, G., Besnard, J. et al. Quantifying the chemical beauty of drugs. Nature Chem 4, 90–98 (2012). https://doi.org/10.1038/nchem.1243

### QEPPI
quantitative estimate of protein-protein interaction targeting drug-likeness

https://github.com/ohuelab/QEPPI

### SAscore
**Estimation of synthetic accessibility score of drug-like molecules based on molecular complexity and fragment contributions**  
[Paper](http://www.jcheminf.com/content/1/1/8) |  [code](https://github.com/rdkit/rdkit/tree/master/Contrib/SA_Score) 

### RAscore
**Retrosynthetic accessibility score (RAscore) – rapid machine learned synthesizability classification from AI driven retrosynthetic planning**  
[Paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d0sc05401a) |  [code](https://github.com/reymond-group/RAscore) 

### Evaluation metrics

**FCD : Fréchet ChemNet Distance**
Fréchet ChemNet Distance: A Metric for Generative Models for Molecules in Drug Discovery

https://github.com/bioinf-jku/FCD

* **Perplexity-Based Molecule Ranking and Bias Estimation of Chemical Language Models** [2022]  
Moret, M., Grisoni, F., Katzberger, P. and Schneider, G.  
[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00079) |  [code](https://github.com/ETHmodlab/CLM_perplexity) 

## Deep Learning-based design


### RNN-based


* **Augmented Hill-Climb increases reinforcement learning efficiency for language-based de novo molecule generation** [2022]  
Thomas, M., O’Boyle, N.M., Bender, A. et al.  
[Paper](https://doi.org/10.1186/s13321-022-00646-z) |  [code](https://github.com/MorganCThomas/SMILES-RNN) 

* **De novo molecule design with chemical language models** [2022]  
Grisoni, F., Schneider, G.  
[Paper](https://doi.org/10.1007/978-1-0716-1787-8_9) |  [code](https://github.com/grisoniFr/de_novo_design_RNN) 

* **Optimizing Recurrent Neural Network Architectures for De Novo Drug Design** [2021]  
Santos, B. P., Abbasi, M., Pereira, T., Ribeiro, B., & Arrais, J. P.  
[Paper](https://ieeexplore.ieee.org/document/9474742) |  [code](https://github.com/larngroup/RNN-Drug-Generation) 

* **A recurrent neural network (RNN) that generates drug-like molecules for drug discovery** [2021]  
[code](https://github.com/shiwentao00/Molecule-RNN) 

* **A molecule generative model used interaction fingerprint (docking pose) as constraints** [2021]  
[code](https://github.com/jeah-z/IFP-RNN) 

* **Bidirectional Molecule Generation with Recurrent Neural Networks** [2020]  
Grisoni, F., Moret, M., Lingwood, R., & Schneider, G.  
[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00943) |  [code](https://github.com/robinlingwood/BIMODAL) 

* **Direct steering of de novo molecular generation with descriptor conditional recurrent neural networks** [2019]  
Kotsias, PC., Arús-Pous, J., Chen, H. *et al.*  
[Paper](https://www.nature.com/articles/s42256-020-0174-5) |  [code](https://github.com/pcko1/Deep-Drug-Coder) 

* **ChemTS: An Efficient Python Library for de novo Molecular Generation** [2017]  
Yang, X., Zhang, J., Yoshizoe, K., Terayama, K., & Tsuda, K.  
[Paper](https://arxiv.org/abs/1710.00616) |  [code](https://github.com/tsudalab/ChemTS) 




### LSTM-based

* **Leveraging molecular structure and bioactivity with chemical language models for de novo drug design** [2023]  
  Kotsias, PC., Arús-Pous, J., Chen, H. *et al.*  
  [Paper](https://www.nature.com/articles/s41467-022-35692-6) |  [code](https://github.com/ETHmodlab/hybridCLMs/tree/v1.0) 

* **SMILES-based CharLSTM with finetuning and goal-directed generation via policy gradient** [2022]  

  [code](https://github.com/gmattedi/Smiles-LSTM) 

* **DeLA-Drug: A Deep Learning Algorithm for Automated Design of Druglike Analogues** [2022]  
  Creanza, T. M., Lamanna, G., Delre, P., Contino, M., Corriero, N., Saviano, M., ... & Ancona, N.   
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00205) |  [Web](http://www.ba.ic.cnr.it/softwareic/deladrugportal/) 

* **De novo design and bioactivity prediction of SARS-CoV-2 main protease inhibitors using recurrent neural network-based transfer learning** [2021]  
Santana, M.V.S., Silva-Jr, F.P.  
  [Paper](https://bmcchem.biomedcentral.com/articles/10.1186/s13065-021-00737-2) |  [code](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2) 

* **Generative Recurrent Networks for De Novo Drug Design** [2018]  
  Gupta, A., Müller, A. T., Huisman, B. J., Fuchs, J. A., Schneider, P., & Schneider, G.   
  [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5836943/) |  [code](https://github.com/topazape/LSTM_Chem) 

* **Generative Recurrent Neural Networks for De Novo Drug Design** [2017]  
  Gupta, Anvita, et al.   
  [Paper](https://onlinelibrary.wiley.com/doi/10.1002/minf.201700111) |  [code](https://github.com/SilviaAmAm/MolBot) 


### Autoregressive-models


* **GraphAF: a Flow-based Autoregressive Model for Molecular Graph Generation** [2020]  
  Shi, C., Xu, M., Zhu, Z., Zhang, W., Zhang, M., & Tang, J.   
  [Paper](https://arxiv.org/abs/2001.09382) |  [code](https://github.com/DeepGraphLearning/GraphAF) 




###  Transformer-based


* **DrugEx v3: scaffold-constrained drug design with graph transformer-based reinforcement learning** [2023]  
  Liu, X., Ye, K., van Vlijmen, H.W.T. et al.   
  [Paper](https://doi.org/10.1186/s13321-023-00694-z) |  [code](https://github.com/CDDLeiden/DrugEx) 

* **Explore drug-like space with deep generative models** [2023]  
  Wang, Jianmin, et al.  
  [Paper](https://doi.org/10.1016/j.ymeth.2023.01.004) |  [code](https://github.com/AspirinCode/drug-likeness_space) 

* **Large-scale chemical language representations capture molecular structure and properties** [2022]  
  Ross, J., Belgodere, B., Chenthamarakshan, V., Padhi, I., Mroueh, Y., & Das, P.   
  [Paper](https://www.nature.com/articles/s42256-022-00580-7) |  [code](https://github.com/IBM/molformer) 

* **AlphaDrug: protein target specific de novo molecular generation** [2022]  
  Qian, Hao, Cheng Lin, Dengwei Zhao, Shikui Tu, and Lei Xu.  
  [Paper](https://academic.oup.com/pnasnexus/article/1/4/pgac227/6751929) |  [code](https://github.com/CMACH508/AlphaDrug) 

* **Can We Quickly Learn to “Translate” Bioactive Molecules with Transformer Models?** [2022]  
  Bagal, V., Aggarwal, R., Vinod, P. K., & Priyakumar, U. D.  
  [Paper](https://doi.org/10.26434/chemrxiv-2022-gln27)

* **MolGPT: Molecular Generation Using a Transformer-Decoder Model** [2022]  
  Bagal, V., Aggarwal, R., Vinod, P. K., & Priyakumar, U. D.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) |  [code](https://github.com/devalab/molgpt) 
  
* **Tailoring Molecules for Protein Pockets: a Transformer-based Generative Solution for Structured-based Drug Design** [2022]  
  Wu, K., Xia, Y., Fan, Y., Deng, P., Liu, H., Wu, L., ... & Liu, T. Y.  
  [Paper](https://arxiv.org/abs/2209.06158) |  [code](https://github.com/HankerWu/TamGent) 
  
* **A Transformer-based Generative Model for De Novo Molecular Design** [2022]  
  Wang, Wenlu, et al.  
  [Paper](https://arxiv.org/abs/2210.08749)

* **Translation between Molecules and Natural Language** [2022]  
  Edwards, C., Lai, T., Ros, K., Honke, G., & Ji, H.  
  [Paper](https://arxiv.org/abs/2204.11817) |  [code](https://github.com/blender-nlp/MolT5) 

* **Regression Transformer enables concurrent sequence regression and generation for molecular language modeling** [2022]  
  Born, Jannis and Manica, Matteo  
  [Paper](https://arxiv.org/abs/2202.01338) |  [code](https://github.com/IBM/regression-transformer) 

* **Generative Pre-Training from Molecules** [2021]  
  Adilov, Sanjar.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) |  [code](https://github.com/sanjaradylov/smiles-gpt) 

* **Transformers for Molecular Graph Generation** [2021]  
  Cofala, Tim, and Oliver Kramer.  
  [Paper](https://web.archive.org/web/20211019010336id_/https://www.esann.org/sites/default/files/proceedings/2021/ES2021-112.pdf) |  [code](https://gitlab.uni-oldenburg.de/gies6280/molegent) 

* **Spatial Generation of Molecules with Transformers** [2021]  
  Cofala, Tim, and Oliver Kramer.  
  [Paper](https://ieeexplore.ieee.org/abstract/document/9533439) |  [code](https://gitlab.uni-oldenburg.de/gies6280/molegent) 

* **Generative Chemical Transformer: Neural Machine Learning of Molecular Geometric Structures from Chemical Language via Attentio** [2021]  
  Hyunseung Kim, Jonggeol Na*, and Won Bo Lee*.  
  [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.1c01289) |  [code](https://github.com/Hyunseung-Kim/molGCT) 

* **C5T5: Controllable Generation of Organic Molecules with Transformer** [2021]  
  Rothchild, D., Tamkin, A., Yu, J., Misra, U., & Gonzalez, J.  
  [Paper](https://arxiv.org/abs/2108.10307) |  [code](https://github.com/dhroth/c5t5) 

* **Molecular optimization by capturing chemist’s intuition using deep neural networks** [2021]  
  He, J., You, H., Sandström, E. et al.   
  [Paper](https://doi.org/10.1186/s13321-021-00497-0) |  [code](https://github.com/MolecularAI/deep-molecular-optimization) 

* **Transformer neural network for protein-specific de novo drug generation as a machine translation problem** [2021]  
  Grechishnikova, Daria.   
  [Paper](https://www.nature.com/articles/s41598-020-79682-4) |  [code](https://github.com/dariagrechishnikova/molecule_structure_generation) 

* **Transmol: repurposing a language model for molecular generation** [2021]  
  Grechishnikova, Daria.   
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2021/ra/d1ra03086h) |  [code](https://gitlab.com/cheml.io/public/transmol) 

* **Attention-based generative models for de novo molecular design** [2021]  
  Dollar, O., Joshi, N., Beck, D.A. and Pfaendtner, J.,  
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc01050f) |  [code](https://github.com/oriondollar/TransVAE) 



### VAE-based

* **COMA: efficient structure-constrained molecular generation using contractive and margin losses** [2023]  
 Choi, J., Seo, S. & Park, S.     
  [Paper](https://doi.org/10.1186/s13321-023-00679-y) |  [code](https://github.com/mathcom/COMA) 

* **Design of potent antimalarials with generative chemistry** [2022]   
  Godinez, W.J., Ma, E.J., Chao, A.T. et al.  
  [Paper](https://doi.org/10.1038/s42256-022-00448-w)  |  [code](https://github.com/Novartis/JAEGER) 

* **Accelerating Bayesian Optimization for Biological Sequence Design with Denoising Autoencoders** [2022]  
  Stanton, S., Maddox, W., Gruver, N., Maffettone, P., Delaney, E., Greenside, P., & Wilson, A. G.   
  [Paper](https://arxiv.org/abs/2203.12742) 

* **Conditional β-VAE for De Novo Molecular Generation** [2022]  
  Richards, Ryan J., and Austen M. Groener.   
  [Paper](https://arxiv.org/abs/2205.01592) 

* **MGCVAE: Multi-Objective Inverse Design via Molecular Graph Conditional Variational Autoencoder** [2022]  
  Lee, Myeonghun, and Kyoungmin Min.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00487) |  [code](https://github.com/mhlee216/MGCVAE) 

* **RELATION: A Deep Generative Model for Structure-Based De Novo Drug Design** [2022]  
  Wang, M., Hsieh, C.Y., Wang, J., Wang, D., Weng, G., Shen, C., Yao, X., Bing, Z., Li, H., Cao, D. and Hou, T.,  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00732) |  [code](https://github.com/micahwang/RELATION) 

* **3DLinker: An E(3) Equivariant Variational Autoencoder for Molecular Linker Design** [2022]  
  Huang, Yinan, Xingang Peng, Jianzhu Ma, and Muhan Zhang.   
  [Paper]https://arxiv.org/abs/2205.07309) |  [code](https://github.com/GraphPKU/3DLinker) 

* **Molecule Generation by Principal Subgraph Mining and Assembling** [2022]  
  Kong, X., Huang, W., Tan, Z., & Liu, Y.  
  [Paper](https://arxiv.org/abs/2106.15098) |  [code](https://github.com/THUNLP-MT/PS-VAE) 
  
* **LIMO: Latent Inceptionism for Targeted Molecule Generation** [2022]  
  Eckmann, Peter, Kunyang Sun, Bo Zhao, Mudong Feng, Michael K. Gilson, and Rose Yu.  
  [Paper](https://arxiv.org/abs/2206.09010) |  [code](https://github.com/rose-stl-lab/limo) 

* **Predicting chemical structure using reinforcement learning with a stack-augmented conditional variational autoencoder** [2022]  
  Kim, H., Ko, S., Kim, B.J. *et al.*  
  [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00666-9) |  [code](https://github.com/HwanheeKim813/stack_CVAE) 

* **Geometry-Based Molecular Generation With Deep Constrained Variational Autoencoder** [2022]   
  Li, Chunyan, Junfeng Yao, Wei Wei, Zhangming Niu, Xiangxiang Zeng, Jin Li, and Jianmin Wang.   
  [Paper](https://ieeexplore.ieee.org/abstract/document/9714718) |  [code](https://github.com/anny0316/GEOM-CVAE) 

* **Inverse design of nanoporous crystalline reticular materials with deep generative models.** [2021]  
  Yao, Z., Sánchez-Lengeling, B., Bobbitt, N.S. et al.  
  [Paper](https://doi.org/10.1038/s42256-020-00271-1) |  [code](https://github.com/zhenpengyao/Supramolecular_VAE) 

* **Attention-based generative models for de novo molecular design** [2021]  
  Dollar, O., Joshi, N., Beck, D.A. and Pfaendtner, J.,  
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc01050f) |  [code](https://github.com/oriondollar/TransVAE) 

* **Toward efficient generation, correction, and properties control of unique drug-like structures** [2021]  
  Druchok, Maksym, Dzvenymyra Yarish, Oleksandr Gurbych, and Mykola Maksymenko.  
  [Paper](https://onlinelibrary.wiley.com/doi/10.1002/jcc.26494) |  [code](https://github.com/SoftServeInc/novel-molecule-generation) 

* **Compressed graph representation for scalable molecular graph generation** [2020]  
  Kwon, Youngchun, Dongseon Lee, Youn-Suk Choi, Kyoham Shin, and Seokho Kang.  
  [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00463-2) |  [code](https://github.com/seokhokang/graphvae_compress) 

* **Fragment Graphical Variational AutoEncoding for Screening Molecules with Small Data** [2019]  
  Armitage, John, Leszek J. Spalek, Malgorzata Nguyen, Mark Nikolka, Ian E. Jacobs, Lorena Marañón, Iyad Nasrallah et al.  
  [Paper](https://arxiv.org/abs/1910.13325) |  [code](https://github.com/OE-FET/FraGVAE) 

* **Molecular generative model based on conditional variational autoencoder for de novo molecular design** [2018]  
  Lim, J., Ryu, S., Kim, J. W., & Kim, W. Y.   
  [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0286-7) |  [code](https://github.com/jaechanglim/CVAE) 

* **Automatic chemical design using a data-driven continuous representation of molecules** [2017]  
  Gómez-Bombarelli, R., Wei, J. N., Duvenaud, D., Hernández-Lobato, J. M., Sánchez-Lengeling, B., Sheberla, D., ... & Aspuru-Guzik, A.   
  [Paper](https://arxiv.org/abs/1610.02415) |  [code](https://github.com/tuantla80/VAE-Molecular-Generation) 




### GAN-based

* **Cell morphology-guided de novo hit design by conditioning GANs on phenotypic image features** [2022]  
Zapata, Paula A. Marin, Oscar Méndez-Lucio, Tuan Le, Carsten Jörn Beese, Jörg Wichard, David Rouquié, and Djork-Arné Clevert.  
[Paper](https://doi.org/10.1039/D2DD00081D) |  [code](https://github.com/Bayer-Group/CPMolGAN) 

* **Generating 3D molecules conditional on receptor binding sites with deep generative models** [2022]  
Ragoza, Matthew, Tomohide Masuda, and David Ryan Koes.  
[Paper](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc05976a) |  [code](https://github.com/mattragoza/liGAN) 

* **Designing optimized drug candidates with Generative Adversarial Network** [2022]  
Abbasi, M., Santos, B.P., Pereira, T.C. et al.  
[Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00623-6) |  [code](https://github.com/larngroup/GAN-Drug-Generator) 

* **De novo molecular design with deep molecular generative models for PPI inhibitors** [2022]  
Jianmin Wang, Yanyi Chu, Jiashun Mao, Hyeon-Nae Jeon, Haiyan Jin, Amir Zeb, Yuil Jang, Kwang-Hwi Cho, Tao Song, Kyoung Tai No.  
[Paper](https://doi.org/10.1093/bib/bbac285) |  [code](https://github.com/AspirinCode/iPPIGAN) 

* **Improvement on Generative Adversarial Network for Targeted Drug Design** [2021]  
Santos, B. P., Abbasi, M., Pereira, T., Ribeiro, B., & Arrais, J.  
[Paper](https://www.cisuc.uc.pt/download-file/16987/IR5glkL7JLe3EZrI59BI) 

* **Generative Adversarial Networks for De Novo Molecular Design** [2021]  
Lee, Y.J., Kahng, H. and Kim, S.B.,  
[Paper](https://doi.org/10.1002/minf.202100045) |  [code](https://github.com/dudwojae/SMILES-MaskGAN) 

* **Mol-CycleGAN: a generative model for molecular optimization** [2020]  
Maziarka, Łukasz, Agnieszka Pocha, Jan Kaczmarczyk, Krzysztof Rataj, Tomasz Danel, and Michał Warchoł  
[Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0404-1) |  [code](https://github.com/ardigen/mol-cycle-gan) 

* **MolGAN: An implicit generative model for small molecular graph** [2018]  
De Cao, N. and Kipf, T.,  
[Paper](https://arxiv.org/abs/1805.11973) |  [code](https://github.com/yongqyu/MolGAN-pytorch) 

* **Objective-Reinforced Generative Adversarial Networks (ORGAN) for Sequence Generation Models** [2017]  
Guimaraes, G.L., Sanchez-Lengeling, B., Outeiral, C., Farias, P.L.C. and Aspuru-Guzik, A.,  
[Paper](https://arxiv.org/abs/1705.10843) |  [code](https://github.com/gablg1/ORGAN) 



### Flow-based


* **Multi-view deep learning based molecule design and structural optimization accelerates the SARS-CoV-2 inhibitor discovery** [2022]  
Chao Pang , Yu Wang , Yi Jiang , Ruheng Wang , Ran Su  , and Leyi Wei.  
[Paper](https://arxiv.org/abs/2212.01575) |  [code](https://github.com/Pang-chao/MEDICO) 

* **Biological Sequence Design with GFlowNets** [2022]  
Jain, M., Bengio, E., Hernandez-Garcia, A., Rector-Brooks, J., Dossou, B.F., Ekbote, C.A., Fu, J., Zhang, T., Kilgour, M., Zhang, D. and Simine, L.  
[Paper](https://arxiv.org/abs/2203.04115) |  [code](https://github.com/MJ10/BioSeq-GFN-AL) 

* **FastFlows: Flow-Based Models for Molecular Graph Generation** [2022]  
Frey, N.C., Gadepally, V. and Ramsundar, B.  
[Paper](https://arxiv.org/abs/2201.12419)

* **Flow Network based Generative Models for Non-Iterative Diverse Candidate Generation** [2021]  
Bengio, E., Jain, M., Korablyov, M., Precup, D. and Bengio, Y.  
[Paper](https://arxiv.org/abs/2106.04399) |  [code](https://github.com/GFNOrg/gflownet) 

* **MoFlow: An Invertible Flow Model for Generating Molecular Graphs** [2020]  
Zang, Chengxi, and Fei Wang.  
[Paper](https://arxiv.org/abs/2006.10137) |  [code](https://github.com/calvin-zcx/moflow) 

* **GraphNVP: an Invertible Flow-based Model for Generating Molecular Graphs** [2020]   
Madhawa, K., Ishiguro, K., Nakago, K. and Abe, M.  
[Paper](https://openreview.net/forum?id=ryxQ6T4YwB)

### Score-Based


* **Score-Based Generative Models for Molecule Generation** [2022]  
Gnaneshwar, Dwaraknath, et al.  
[Paper](https://arxiv.org/abs/2203.04698) 




### Energy-based

* **Energy-based Generative Models for Target-specific Drug Discovery** [2022]  
Li, Junde, Collin Beaudoin, and Swaroop Ghosh.  
[Paper](https://arxiv.org/abs/2212.02404) |  [code](https://github.com/jundeli/TagMol) 

* **MOG: Molecular Out-of-distribution Generation with Energy-based Models** [2021]  
Lee, Seul, Dong Bok Lee, and Sung Ju Hwang.  
[Paper](https://openreview.net/forum?id=qkTEaJ9orc1) 


### Diffusion-based

* **Structure-based Drug Design with Equivariant Diffusion Models** [2023]  
Schneuing, A., Du, Y., Harris, C., Jamasb, A., Igashov, I., Du, W., ... & Correia, B.   
[Paper](https://openreview.net/forum?id=uKmuzIuVl8z) |  [code](https://github.com/arneschneuing/DiffSBDD) 

* **Equivariant 3D-Conditional Diffusion Models for Molecular Linker Desig** [2023]  
Igashov, I., Stärk, H., Vignac, C., Satorras, V.G., Frossard, P., Welling, M., Bronstein, M. and Correia, B.,   
[Paper](https://openreview.net/forum?id=cnsHSSLnHVV) |  [code](https://github.com/igashov/DiffLinker) 

* **MiDi: Mixed Graph and 3D Denoising Diffusion for Molecule Generation** [2023]  
Vignac, Clement, Nagham Osman, Laura Toni, and Pascal Frossard.  
[Paper](https://arxiv.org/abs/2302.09048) |  [code](https://github.com/cvignac/MiDi) 

* **Geometry-Complete Diffusion for 3D Molecule Generation** [2023]  
Morehead, Alex, and Jianlin Cheng.  
[Paper](https://arxiv.org/abs/2302.04313) |  [code](https://github.com/BioinfoMachineLearning/bio-diffusion) 

* **MDM: Molecular Diffusion Model for 3D Molecule Generation** [2022]  
Huang, Lei, Hengtong Zhang, Tingyang Xu, and Ka-Chun Wong.  
[Paper](https://arxiv.org/abs/2209.05710)

* **Diffusion-based Molecule Generation with Informative Prior Bridges** [2022]  
Lemeng Wu, Chengyue Gong, Xingchao Liu, Mao Ye, Qiang Liu  
[Paper](https://arxiv.org/abs/2209.00865)

* **Equivariant Diffusion for Molecule Generation in 3D** [2022]  
Hoogeboom, Emiel, Vıctor Garcia Satorras, Clément Vignac, and Max Welling.  
[Paper](https://arxiv.org/abs/2203.17003) |  [code](https://github.com/ehoogeboom/e3_diffusion_for_molecules) 



### RL-based

* **DrugEx v3: scaffold-constrained drug design with graph transformer-based reinforcement learning** [2023]  
  Liu, X., Ye, K., van Vlijmen, H.W.T. et al.   
  [Paper](https://doi.org/10.1186/s13321-023-00694-z) |  [code](https://github.com/CDDLeiden/DrugEx) 

* **COMA: efficient structure-constrained molecular generation using contractive and margin losses** [2023]  
 Choi, J., Seo, S. & Park, S.     
  [Paper](https://doi.org/10.1186/s13321-023-00679-y) |  [code](https://github.com/mathcom/COMA) 

* **Generative and reinforcement learning approaches for the automated de novo design of bioactive compounds** [2022]  
Korshunova, M., Huang, N., Capuzzi, S. et al.  
[Paper](https://doi.org/10.1038/s42004-022-00733-0) |  [code](https://github.com/isayevlab/rl_experiments) 

* **Augmented Hill-Climb increases reinforcement learning efficiency for language-based de novo molecule generation** [2022]  
Thomas, M., O’Boyle, N.M., Bender, A. et al.  
[Paper](https://doi.org/10.1186/s13321-022-00646-z) |  [code](https://github.com/MorganCThomas/SMILES-RNN) 


* **Predicting chemical structure using reinforcement learning with a stack-augmented conditional variational autoencoder** [2022]  
  Kim, H., Ko, S., Kim, B.J. *et al.*  
  [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00666-9) |  [code](https://github.com/HwanheeKim813/stack_CVAE) 

* **De Novo Drug Design Using Reinforcement Learning with Graph-Based Deep Generative Models** [2022]  
Atance, S.R., Diez, J.V., Engkvist, O., Olsson, S. and Mercado, R.  
[Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00838) |  [code](https://github.com/olsson-group/RL-GraphINVENT) 

* **DRlinker: Deep Reinforcement Learning for Optimization in Fragment Linking Design** [2022]
  Tan, Y., Dai, L., Huang, W., Guo, Y., Zheng, S., Lei, J., ... & Yang, Y. 
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00982) |  [code](https://github.com/biomed-AI/DRlinker) 

* **Widely Used and Fast De Novo Drug Design by a Protein Sequence-Based Reinforcement Learning Model** [2022]  
Li, Yaqin, Lingli Li, Yongjin Xu, and Yi Yu.
[Paper](https://arxiv.org/abs/2209.07405) 

* **Molecular Design Method Using a Reversible Tree Representation of Chemical Compounds and Deep Reinforcement Learning** [2022]  
  Ishitani, R., Kataoka, T. and Rikimaru, K.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00366) |  [code](https://github.com/pfnet-research/RJT-RL) 

* **Accelerated rational PROTAC design via deep learning and molecular simulations** [2022]  
  Zheng, S., Tan, Y., Wang, Z. et al.  
  [Paper](https://www.nature.com/articles/s42256-022-00527-y) |  [code](https://github.com/biomed-AI/PROTAC-RL) 
  
* **Improving de novo molecular design with curriculum learning** [2022]  
  Guo, J., Fialková, V., Arango, J.D. et al.  
  [Paper](https://doi.org/10.1038/s42256-022-00494-4) |  [code](https://github.com/MolecularAI/ReinventCommunity/blob/master/notebooks/Automated_Curriculum_Learning_Demo.ipynb)  
 
* **De novo design of protein target specific scaffold-based Inhibitors via Reinforcement Learning** [2022]  
  Bontha M, McNaughton A, Knutson C, Pope J, Kumar N.  
  [Paper](https://openreview.net/forum?id=k-ES3OH7eqp)

* **Autonomous molecule generation using reinforcement learning and docking to develop potential novel inhibitors** [2022]  
  Jeon, W., Kim, D.  
  [Paper](https://doi.org/10.1038/s41598-020-78537-2) |  [code](https://github.com/wsjeon92/morld) 

* **Scalable Fragment-Based 3D Molecular Design with Reinforcement Learning** [2022]  
  Flam-Shepherd, Daniel, Alexander Zhigalin, and Alán Aspuru-Guzik.  
  [Paper](https://arxiv.org/abs/2202.00658) 

* **Hit and Lead Discovery with Explorative RL and Fragment-based Molecule Generation** [2021]  
  Yang, S., Hwang, D., Lee, S., Ryu, S., & Hwang, S. J.  
  [Paper](https://arxiv.org/abs/2110.01219) |  [code](https://github.com/AITRICS/FREED) 

* **Unlocking reinforcement learning for drug design** [2021]  
 
  [code](https://github.com/DarkMatterAI/mrl) 

* **MoleGuLAR: Molecule Generation Using Reinforcement Learning with Alternating Rewards** [2021]  
Goel, Manan, Shampa Raghunathan, Siddhartha Laghuvarapu, and U. Deva Priyakumar.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01341) |  [code](https://github.com/devalab/MoleGuLAR) 

* **Memory-Assisted Reinforcement Learning for Diverse Molecular De Novo Design** [2020]  
Blaschke T, Engkvist O, Bajorath J, Chen H.  
  [Paper](https://doi.org/10.26434/chemrxiv.12693152.v1) |  [code](https://github.com/tblaschke/reinvent-memory) 

* **Reinforcement Learning for Molecular Design Guided by Quantum Mechanics** [2020]  
Simm, G., Pinsler, R. and Hernández-Lobato, J.M.,  
  [Paper](http://proceedings.mlr.press/v119/simm20b/simm20b.pdf) |  [code](https://github.com/gncs/molgym) 

* **Molecular de-novo design through deep reinforcement learning** [2017]  
Olivecrona, M., Blaschke, T., Engkvist, O. et al.  
  [Paper](https://doi.org/10.1186/s13321-017-0235-x) |  [code](https://github.com/tblaschke/reinvent) 


### Multi-task DMGs

* **Molecular Language Model as Multi-task Generator** [2023]  
 Fang, Y., Zhang, N., Chen, Z., Fan, X. and Chen, H.    
  [Paper](https://arxiv.org/abs/2301.11259) |  [code](https://github.com/zjunlp/MolGen) 


## Multi-Target based deep molecular generative models


* **De novo generation of dual-target ligands using adversarial training and reinforcement learning** [2021]  
 Lu, Fengqing, Mufei Li, Xiaoping Min, Chunyan Li, and Xiangxiang Zeng.    
  [Paper](https://doi.org/10.1093/bib/bbab333) | [code](https://github.com/lllfq/DLGN) 

* **Compound dataset and custom code for deep generative multi-target compound design** [2021]  
 Blaschke, Thomas, and Jürgen Bajorath.    
  [Paper](https://doi.org/10.2144/fsoa-2021-0033) |  [code](https://github.com/tblaschke/reinvent-multi-target) 


## Ligand-based deep molecular generative models

* **Leveraging molecular structure and bioactivity with chemical language models for de novo drug design** [2023]  
  Kotsias, PC., Arús-Pous, J., Chen, H. *et al.*  
  [Paper](https://www.nature.com/articles/s41467-022-35692-6) |  [code](https://github.com/ETHmodlab/hybridCLMs/tree/v1.0) 

* **Explore drug-like space with deep generative models** [2023]  
Wang, Jianmin, et al.   
[Paper](https://doi.org/10.1016/j.ymeth.2023.01.004) |  [code](https://github.com/AspirinCode/drug-likeness_space) 

* **De novo molecular design with deep molecular generative models for PPI inhibitors** [2022]  
  Jianmin Wang, Yanyi Chu, Jiashun Mao, Hyeon-Nae Jeon, Haiyan Jin, Amir Zeb, Yuil Jang, Kwang-Hwi Cho, Tao Song, Kyoung Tai No.  
  [Paper](https://doi.org/10.1093/bib/bbac285) |  [code](https://github.com/AspirinCode/iPPIGAN) 

* **DeLA-Drug: A Deep Learning Algorithm for Automated Design of Druglike Analogues** [2022]  
  Creanza, T. M., Lamanna, G., Delre, P., Contino, M., Corriero, N., Saviano, M., ... & Ancona, N.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00205) |  [Web](http://www.ba.ic.cnr.it/softwareic/deladrugportal/) 

* **SMILES-based CharLSTM with finetuning and goal-directed generation via policy gradient** [2022]  

  [code](https://github.com/gmattedi/Smiles-LSTM) 

* **Large-scale chemical language representations capture molecular structure and properties** [2022]  
Ross, J., Belgodere, B., Chenthamarakshan, V., Padhi, I., Mroueh, Y., & Das, P.   
[Paper](https://www.nature.com/articles/s42256-022-00580-7) |  [code](https://github.com/IBM/molformer) 

* **Augmented Hill-Climb increases reinforcement learning efficiency for language-based de novo molecule generation** [2022]  
  Thomas, M., O’Boyle, N.M., Bender, A. et al.  
  [Paper](https://doi.org/10.1186/s13321-022-00646-z) |  [code](https://github.com/MorganCThomas/SMILES-RNN) 

* **De novo molecule design with chemical language models** [2022]  
  Grisoni, F., Schneider, G.  
  [Paper](https://doi.org/10.1007/978-1-0716-1787-8_9) |  [code](https://github.com/grisoniFr/de_novo_design_RNN) 

* **Can We Quickly Learn to “Translate” Bioactive Molecules with Transformer Models?** [2022]  
  Bagal, V., Aggarwal, R., Vinod, P. K., & Priyakumar, U. D.  
  [Paper](https://doi.org/10.26434/chemrxiv-2022-gln27)

* **MolGPT: Molecular Generation Using a Transformer-Decoder Model** [2022]   
  Bagal, V., Aggarwal, R., Vinod, P. K., & Priyakumar, U. D.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) |  [code](https://github.com/devalab/molgpt) 

* **A Transformer-based Generative Model for De Novo Molecular Design** [2022]  
  Wang, Wenlu, et al.  
  [Paper](https://arxiv.org/abs/2210.08749) 

* **Translation between Molecules and Natural Language** [2022]  
  Edwards, C., Lai, T., Ros, K., Honke, G., & Ji, H.  
  [Paper](https://arxiv.org/abs/2204.11817) |  [code](https://github.com/blender-nlp/MolT5) 

* **Regression Transformer enables concurrent sequence regression and generation for molecular language modeling** [2022]  
  Born, Jannis and Manica, Matteo  
  [Paper](https://arxiv.org/abs/2202.01338) |  [code](https://github.com/IBM/regression-transformer) 

* **Optimizing Recurrent Neural Network Architectures for De Novo Drug Design** [2021]  
  Santos, B. P., Abbasi, M., Pereira, T., Ribeiro, B., & Arrais, J. P.  
  [Paper](https://ieeexplore.ieee.org/document/9474742) |  [code](https://github.com/larngroup/RNN-Drug-Generation) 

* **A recurrent neural network (RNN) that generates drug-like molecules for drug discovery** [2021]  

  [code](https://github.com/shiwentao00/Molecule-RNN) 

* **A molecule generative model used interaction fingerprint (docking pose) as constraints** [2021]  
  [code](https://github.com/jeah-z/IFP-RNN) 

* **De novo design and bioactivity prediction of SARS-CoV-2 main protease inhibitors using recurrent neural network-based transfer learning** [2021]
  Santana, M.V.S., Silva-Jr, F.P. 
  [Paper](https://bmcchem.biomedcentral.com/articles/10.1186/s13065-021-00737-2) |  [code](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2) 

* **Generative Pre-Training from Molecules** [2021]  
  Adilov, Sanjar.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00600) |  [code](https://github.com/sanjaradylov/smiles-gpt) 

* **Transformers for Molecular Graph Generation** [2021]  
  Cofala, Tim, and Oliver Kramer.  
  [Paper](https://web.archive.org/web/20211019010336id_/https://www.esann.org/sites/default/files/proceedings/2021/ES2021-112.pdf) |  [code](https://gitlab.uni-oldenburg.de/gies6280/molegent) 

* **Spatial Generation of Molecules with Transformers** [2021]  
  Cofala, Tim, and Oliver Kramer.  
  [Paper](https://ieeexplore.ieee.org/abstract/document/9533439) |  [code](https://gitlab.uni-oldenburg.de/gies6280/molegent) 

* **Generative Chemical Transformer: Neural Machine Learning of Molecular Geometric Structures from Chemical Language via Attention** [2021]  
  Hyunseung Kim, Jonggeol Na*, and Won Bo Lee*.  
  [Paper](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.1c01289) |  [code](https://github.com/Hyunseung-Kim/molGCT) 

* **C5T5: Controllable Generation of Organic Molecules with Transformers** [2021]  
  Rothchild, D., Tamkin, A., Yu, J., Misra, U., & Gonzalez, J.  
  [Paper](https://arxiv.org/abs/2108.10307) |  [code](https://github.com/dhroth/c5t5) 

* **Molecular optimization by capturing chemist’s intuition using deep neural networks** [2021]  
  He, J., You, H., Sandström, E. et al.   
  [Paper](https://doi.org/10.1186/s13321-021-00497-0) |  [code](https://github.com/MolecularAI/deep-molecular-optimization) 

* **Transmol: repurposing a language model for molecular generation** [2021]  
  Grechishnikova, Daria.   
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2021/ra/d1ra03086h) |  [code](https://gitlab.com/cheml.io/public/transmol) 

* **Attention-based generative models for de novo molecular design** [2021]  
  Dollar, O., Joshi, N., Beck, D.A. and Pfaendtner, J.,  
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2021/sc/d1sc01050f) |  [code](https://github.com/oriondollar/TransVAE) 

* **Bidirectional Molecule Generation with Recurrent Neural Networks** [2020]  
  Grisoni, F., Moret, M., Lingwood, R., & Schneider, G.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00943) |  [code](https://github.com/robinlingwood/BIMODAL) 

* **GraphAF: a Flow-based Autoregressive Model for Molecular Graph Generation** [2020]  
Shi, C., Xu, M., Zhu, Z., Zhang, W., Zhang, M., & Tang, J.   
[Paper](https://arxiv.org/abs/2001.09382) |  [code](https://github.com/DeepGraphLearning/GraphAF) 

* **Direct steering of de novo molecular generation with descriptor conditional recurrent neural networks** [2019]
  Kotsias, PC., Arús-Pous, J., Chen, H. *et al.*
  [Paper](https://www.nature.com/articles/s42256-020-0174-5) |  [code](https://github.com/pcko1/Deep-Drug-Coder) 

* **Generative Recurrent Networks for De Novo Drug Design** [2018]  
  Gupta, A., Müller, A. T., Huisman, B. J., Fuchs, J. A., Schneider, P., & Schneider, G.   
  [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5836943/) |  [code](https://github.com/topazape/LSTM_Chem) 

* **Generative Recurrent Neural Networks for De Novo Drug Design** [2017]  
  Gupta, Anvita, et al.   
  [Paper](https://onlinelibrary.wiley.com/doi/10.1002/minf.201700111) |  [code](https://github.com/SilviaAmAm/MolBot) 

* **ChemTS: An Efficient Python Library for de novo Molecular Generation** [2017]  
  Yang, X., Zhang, J., Yoshizoe, K., Terayama, K., & Tsuda, K.  
  [Paper](https://arxiv.org/abs/1710.00616) |  [code](https://github.com/tsudalab/ChemTS) 


## Pharmacophore-based deep molecular generative models

* **PGMG: A Pharmacophore-Guided Deep Learning Approach for Bioactive Molecular Generation** [2022]  
  Zhu, Huimin, Renyi Zhou, Jing Tang, and Min Li.  
  [Paper](https://arxiv.org/abs/2207.00821) |  [code](https://github.com/CSUBioGroup/PGMG) 

* **Deep generative design with 3D pharmacophoric constraints** [2021]  
  mrie, Fergus and Hadfield, Thomas E and Bradley, Anthony R and Deane, Charlotte M.  
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2021/SC/D1SC02436A) |  [code](https://github.com/XiaotanYu/DEVELOP-ZYH) 



## Structure-based deep molecular generative models


* **RELATION: A Deep Generative Model for Structure-Based De Novo Drug Design** [2022]  
  Wang, M., Hsieh, C.Y., Wang, J., Wang, D., Weng, G., Shen, C., Yao, X., Bing, Z., Li, H., Cao, D. and Hou, T.,  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00732) |  [code](https://github.com/micahwang/RELATION) 

* **Tailoring Molecules for Protein Pockets: a Transformer-based Generative Solution for Structured-based Drug Design** [2022]  
  Wu, K., Xia, Y., Fan, Y., Deng, P., Liu, H., Wu, L., ... & Liu, T. Y.  
  [Paper](https://arxiv.org/abs/2209.06158) |  [code](https://github.com/HankerWu/TamGent) 

* **De novo design of protein target specific scaffold-based Inhibitors via Reinforcement Learning** [2022]  
  Bontha M, McNaughton A, Knutson C, Pope J, Kumar N.  
  [Paper](https://openreview.net/forum?id=k-ES3OH7eqp)

* **AlphaDrug: protein target specific de novo molecular generation** [2022]  
  Qian, Hao, Cheng Lin, Dengwei Zhao, Shikui Tu, and Lei Xu.  
  [Paper](https://academic.oup.com/pnasnexus/article/1/4/pgac227/6751929) |  [code](https://github.com/CMACH508/AlphaDrug) 

* **LIMO: Latent Inceptionism for Targeted Molecule Generation** [2022]  
  Eckmann, Peter, Kunyang Sun, Bo Zhao, Mudong Feng, Michael K. Gilson, and Rose Yu.  
  [Paper](https://arxiv.org/abs/2206.09010) |  [code](https://github.com/rose-stl-lab/limo) 

* **Pocket2Mol: Efficient Molecular Sampling Based on 3D Protein Pockets** [2022]  
 Peng, Xingang, Shitong Luo, Jiaqi Guan, Qi Xie, Jian Peng, and Jianzhu Ma.  
  [Paper](https://proceedings.mlr.press/v162/peng22b.html) |  [code](https://github.com/pengxingang/Pocket2Mol) 

* **Autonomous molecule generation using reinforcement learning and docking to develop potential novel inhibitors** [2022]  
  Jeon, W., Kim, D.  
  [Paper](https://doi.org/10.1038/s41598-020-78537-2) |  [code](https://github.com/wsjeon92/morld) 

* **Target-Focused Library Design by Pocket-Applied Computer Vision and Fragment Deep Generative Linking** [2022]  
  Eguida, Merveille, Christel Schmitt-Valencia, Marcel Hibert, Pascal Villa, and Didier Rognan.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00931) |  [code](https://github.com/kimeguida/POEM) 

* **Incorporating Target-Specific Pharmacophoric Information into Deep Generative Models for Fragment Elaboration** [2022]  
  Hadfield, Thomas E., Fergus Imrie, Andy Merritt, Kristian Birchall, and Charlotte M. Deane.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01311) |  [code](https://github.com/tomhadfield95/STRIFE) 

* **Fragment-Based Ligand Generation Guided By Geometric Deep Learning On Protein-Ligand Structure** [2022]  
  Powers, Alexander S., Helen H. Yu, Patricia Suriana, and Ron O. Dror.  
  [Paper](https://www.biorxiv.org/content/10.1101/2022.03.17.484653v2) 

* **Zero-Shot 3D Drug Design by Sketching and Generating** [2022]  
  Long, Siyu, Yi Zhou, Xinyu Dai, and Hao Zhou.   
  [Paper](https://nips.cc/media/neurips-2022/Slides/54457.pdf) |  [code](https://github.com/longlongman/DESERT) 

* **Transformer neural network for protein-specific de novo drug generation as a machine translation proble** [2021]  
  Grechishnikova, Daria.   
  [Paper](https://www.nature.com/articles/s41598-020-79682-4) |  [code](https://github.com/dariagrechishnikova/molecule_structure_generation) 

* **Structure-aware generation of drug-like molecules** [2021]  
  Drotár, P., Jamasb, A.R., Day, B., Cangea, C. and Liò, P.,   
  [Paper](https://arxiv.org/abs/2111.04107) 

* **A 3D Generative Model for Structure-Based Drug Design** [2021]  
  Luo, S., Guan, J., Ma, J., & Peng, J.   
  [Paper](https://openreview.net/forum?id=yDwfVD_odRo) |  [code](https://github.com/luost26/3D-Generative-SBDD) 

* **Structure-Based de Novo Molecular Generator Combined with Artificial Intelligence and Docking Simulations** [2021]  
  Ma, B., Terayama, K., Matsumoto, S., Isaka, Y., Sasakura, Y., Iwata, H., Araki, M. and Okuno, Y.   
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00679) |  [code](https://github.com/clinfo/SBMolGen) 







## Fragment-based deep molecular generative models


### Scaffold-based DMGs


* **DrugEx v3: scaffold-constrained drug design with graph transformer-based reinforcement learning** [2023]  
  Liu, X., Ye, K., van Vlijmen, H.W.T. et al.    
  [Paper](https://doi.org/10.1186/s13321-023-00694-z) |  [code](https://github.com/CDDLeiden/DrugEx) 

* **Sc2Mol: a scaffold-based two-step molecule generator with variational autoencoder and transformer** [2023]  
  Zhirui Liao, Lei Xie, Hiroshi Mamitsuka, Shanfeng Zhu.  
  [Paper](https://doi.org/10.1093/bioinformatics/btac814) |  [code](https://github.com/zhiruiliao/Sc2Mol) 

* **De novo design of protein target specific scaffold-based Inhibitors via Reinforcement Learning** [2022]  
  Bontha M, McNaughton A, Knutson C, Pope J, Kumar N.  
  [Paper](https://openreview.net/forum?id=k-ES3OH7eqp)

* **LibINVENT: Reaction-based Generative Scaffold Decoration for in Silico Library Design** [2022]  
  Fialková, V., Zhao, J., Papadopoulos, K., Engkvist, O., Bjerrum, E.J., Kogej, T. and Patronov, A   
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00469) |  [code](https://github.com/MolecularAI/Lib-INVENT) 

* **Learning to Extend Molecular Scaffolds with Structural Motifs** [2022]  
  Maziarz, Krzysztof, Henry Jackson-Flux, Pashmina Cameron, Finton Sirockin, Nadine Schneider, Nikolaus Stiefl, Marwin Segler, and Marc Brockschmidt.   
  [Paper](https://openreview.net/forum?id=ZTsoE8G3GG)

* **Deep scaffold hopping with multimodal transformer neural networks** [2021]  
Zheng, Shuangjia, Zengrong Lei, Haitao Ai, Hongming Chen, Daiguo Deng, and Yuedong Yang.  
  [Paper](https://doi.org/10.1186/s13321-021-00565-5) |  [code](https://github.com/prokia/deepHops) 

* **Kinase Inhibitor Scaffold Hopping with Deep Learning Approaches** [2021]  
Hu, Lizhao, Yuyao Yang, Shuangjia Zheng, Jun Xu, Ting Ran, and Hongming Chen.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00608) |  [code](https://github.com/YuYaoYang2333/SyntaLinker) 

* **3D-Scaffold: A Deep Learning Framework to Generate 3D Coordinates of Drug-like Molecules with Desired Scaffolds** [2021]  
Joshi, Rajendra P., Niklas WA Gebauer, Mridula Bontha, Mercedeh Khazaieli, Rhema M. James, James B. Brown, and Neeraj Kumar.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jpcb.1c06437) |  [code](https://github.com/PNNL-CompBio/3D_Scaffold) 

* **SMILES-Based Deep Generative Scaffold Decorator for De-Novo Drug Design** [2020]  
Arús-Pous, Josep, Atanas Patronov, Esben Jannik Bjerrum, Christian Tyrchan, Jean-Louis Reymond, Hongming Chen, and Ola Engkvist.  
  [Paper](https://doi.org/10.26434/chemrxiv.11638383.v1) |  [code](https://github.com/undeadpixel/reinvent-scaffold-decorator) 

* **Scaffold-based molecular design with a graph generative model** [2019]  
Lim, Jaechang, Sang-Yeon Hwang, Seokhyun Moon, Seungsu Kim, and Woo Youn Kim.  
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2020/SC/C9SC04503A) |  [code](https://github.com/jaechanglim/GGM) 


### Motifs-based DMGs


* **Learning to Extend Molecular Scaffolds with Structural Motifs** [2022]  
  Maziarz, Krzysztof, Henry Jackson-Flux, Pashmina Cameron, Finton Sirockin, Nadine Schneider, Nikolaus Stiefl, Marwin Segler, and Marc Brockschmidt.   
  [Paper](https://openreview.net/forum?id=ZTsoE8G3GG)

* **Hierarchical generation of molecular graphs using structural motifs** [2020]  
  Jin, Wengong, Regina Barzilay, and Tommi Jaakkola.   
  [Paper](https://dl.acm.org/doi/abs/10.5555/3524938.3525387) |  [code](https://github.com/wengong-jin/hgraph2graph) 



### Fragment-based DMGs

* **MacFrag: segmenting large-scale molecules to obtain diverse fragments with high qualities** [2023]  
  Yanyan Diao, Feng Hu, Zihao Shen, Honglin Li*.  
  [Paper](https://doi.org/10.1093/bioinformatics/btad012) |  [code](https://github.com/yydiao1025/MacFrag) 

* **Fragment-based Deep Molecular Generation using Hierarchical Chemical Graph Representation and Multi-Resolution Graph Variational Autoencoder** [2023]  
  Gao, Zhenxiang, Xinyu Wang, Blake Blumenfeld Gaines, Xuetao Shi, Jinbo Bi, and Minghu Song.  
  [Paper](https://doi.org/10.1002/minf.202200215)

* **Fragment-based t-SMILES for de novo molecular generation** [2023]  
  Wu, Juan-Ni, Tong Wang, Yue Chen, Li-Juan Tang, Hai-Long Wu, and Ru-Qin Yu.  
  [Paper](https://arxiv.org/abs/2301.01829) |  [code](https://github.com/juanniwu/t-SMILES) 

* **Target-Focused Library Design by Pocket-Applied Computer Vision and Fragment Deep Generative Linking** [2022]  
  Eguida, Merveille, Christel Schmitt-Valencia, Marcel Hibert, Pascal Villa, and Didier Rognan.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00931) |  [code](https://github.com/kimeguida/POEM) 

* **Incorporating Target-Specific Pharmacophoric Information into Deep Generative Models for Fragment Elaboration** [2022]  
  Hadfield, Thomas E., Fergus Imrie, Andy Merritt, Kristian Birchall, and Charlotte M. Deane.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01311) |  [code](https://github.com/tomhadfield95/STRIFE) 

* **Fragment-Based Ligand Generation Guided By Geometric Deep Learning On Protein-Ligand Structure** [2022]  
  Powers, Alexander S., Helen H. Yu, Patricia Suriana, and Ron O. Dror.  
  [Paper](https://www.biorxiv.org/content/10.1101/2022.03.17.484653v2) 

* **FAME: Fragment-based Conditional Molecular Generation for Phenotypic Drug Discovery** [2022]  
  Pham, Thai-Hoang, Lei Xie, and Ping Zhang.  
  [Paper](https://www.biorxiv.org/content/10.1101/2022.01.21.477292v1) 

* **Scalable Fragment-Based 3D Molecular Design with Reinforcement Learning** [2022]  
  Flam-Shepherd, Daniel, Alexander Zhigalin, and Alán Aspuru-Guzik.  
  [Paper](https://arxiv.org/abs/2202.00658) 

* **Hit and Lead Discovery with Explorative RL and Fragment-based Molecule Generation** [2021]  
  Yang, S., Hwang, D., Lee, S., Ryu, S., & Hwang, S. J.  
  [Paper](https://arxiv.org/abs/2110.01219) |  [code](https://github.com/AITRICS/FREED) 

* **Automated Generation of Novel Fragments Using Screening Data, a Dual SMILES Autoencoder, Transfer Learning and Syntax Correction** [2021]  
  Bilsland, Alan E., Kirsten McAulay, Ryan West, Angelo Pugliese, and Justin Bower.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01226) |  [code](https://github.com/abilsland/fragmentEncoder) 

* **A Deep Generative Model for Fragment-Based Molecule Generation** [2020]  
  Podda, Marco, Davide Bacciu, and Alessio Micheli.  
  [Paper](http://proceedings.mlr.press/v108/) |  [code](https://github.com/hengwei-chan/fragment-based-de-novo) 

* **Fragment Graphical Variational AutoEncoding for Screening Molecules with Small Data** [2019]  
  Armitage, John, Leszek J. Spalek, Malgorzata Nguyen, Mark Nikolka, Ian E. Jacobs, Lorena Marañón, Iyad Nasrallah et al.  
  [Paper](https://arxiv.org/abs/1910.13325) |  [code](https://github.com/OE-FET/FraGVAE) 








### Linkers-based DMGs

* **Equivariant 3D-Conditional Diffusion Models for Molecular Linker Desig** [2023]  
Igashov, I., Stärk, H., Vignac, C., Satorras, V.G., Frossard, P., Welling, M., Bronstein, M. and Correia, B.,   
[Paper](https://openreview.net/forum?id=cnsHSSLnHVV) |  [code](https://github.com/igashov/DiffLinker) 

* **DRlinker: Deep Reinforcement Learning for Optimization in Fragment Linking Design** [2022]  
  Tan, Y., Dai, L., Huang, W., Guo, Y., Zheng, S., Lei, J., ... & Yang, Y.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00982) |  [code](https://github.com/biomed-AI/DRlinker) 

* **3DLinker: An E(3) Equivariant Variational Autoencoder for Molecular Linker Design** [2022]  
  Huang, Yinan, Xingang Peng, Jianzhu Ma, and Muhan Zhang.   
  [Paper](https://arxiv.org/abs/2205.07309) |  [code](https://github.com/GraphPKU/3DLinker) 

* **SyntaLinker-Hybrid: A deep learning approach for target specific drug design** [2022]  
  Feng, Yu, Yuyao Yang, Wenbin Deng, Hongming Chen, and Ting Ran.    
  [Paper](https://doi.org/10.1016/j.ailsci.2022.100035) 

* **Deep Generative Models for 3D Linker Design** [2020]  
  Imrie, Fergus, Anthony R. Bradley, Mihaela van der Schaar, and Charlotte M. Deane.  
  [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120) |  [code](https://github.com/fimrie/DeLinker) 

* **SyntaLinker: automatic fragment linking with deep conditional transformer neural networks** [2020]  
  Yang, Yuyao, Shuangjia Zheng, Shimin Su, Chao Zhao, Jun Xu, and Hongming Chen.  
  [Paper](https://pubs.rsc.org/en/content/articlelanding/2020/sc/d0sc03126g) |  [code](https://github.com/YuYaoYang2333/SyntaLinker) 
