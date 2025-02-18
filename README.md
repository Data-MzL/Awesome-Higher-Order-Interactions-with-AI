# Awesome-Higher-Order-Interactions-with-AI
> ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) Higher-Order Interactions(HOI) in complex network. Collections of related research papers for HOI,commomly used datasets and tools.

## Conetents
- [Surveys for HOI](#Surveys-for-HOI)
- [Datasets of HOI](#Datasets-of-HOI)
- [Tools of HOI](#Tools-of-HOI)
- [Related research paper of HOI](#Related-research-paper-of-HOI)
----------
## Surveys for HOI
| **Paper Title** | **Venue** | **Year** | **Code** |
| ----------------- | :--: | :--: | :--: |
|[Networks beyond pairwise interactions: Structure and dynamics](https://www.sciencedirect.com/science/article/pii/S0370157320302489)|Physics Reports|2020|-|
|[A Survey on Hypergraph Neural Networks: An In-Depth and Step-by-Step Guide](https://arxiv.org/pdf/2404.01039v3)|KDD|2024|-|
|[Topological Data Analysis in Graph Neural Networks: Surveys and Perspectives  pham2025topological](https://ieeexplore.ieee.org/abstract/document/10826583)|TNNLS|2025|-|
|[Architectures of Topological Deep Learning: A Survey of Message-Passing Topological Neural Networks](https://arxiv.org/abs/2304.10031)|Arxiv|2023|[[code](https://github.com/awesome-tnns)]|

----------
## Datasets of HOI
| **Network Types** | **Descriptions** | **Examples** | **Datasets** |
| :--:  | -- | :--: | :--: |   
|Social Networks|Social networks consist of individuals (people, organizations, groups) and their relationships, which can be personal, competitive, or collaborative. Higher-order interactions in these networks involve complex dynamics among multiple individuals.|1.Collaboration Networks<br>2.Workplace Social Network <br>3.Campus Social Network|1.Microsoft Academic Graph with HOI<br>2.Temporal Social Network with HOI|
|Biological Networks|Biological networks map the complex relationships among entities like genes, proteins, and cells. Nodes represent entities, and edges signify their interactions. Higher-order interactions reflect the nonlinear cooperation among multiple entities, which cannot be fully captured by pairwise interactions alone.|1.Protein Interaction Network<br>2.Brain Network<br>3. Gene Regulatory Network<br>|1. Human Triadic PPI Dataset<br>2. Cancer Datasets with HOI<br>3. Macaque Brain Networks with HOI|
|Chemical Molecular Networks| Chemical molecular networks are graph models that represent molecules as nodes and their pairwise interactions as edges. High-order interactions in molecular networks involve three or more atoms or groups, such as electronic delocalization and many-body potential energy.|1. Conjugated Polymers<br>2. Polycentric Bond<br>3. Dependencies between Leaving Groups|1. Organic Photovoltaic Dataset<br>2. PubChemQC Dataset v2<br>3. USPTO-50K datasets|

----------
## Tools of HOI
| **Name** | **Environment** | **Domians** | **Functions** |**Code**|
| :--:  | :--: | :--: | :--: |:--:|
|HyperNetX|Python|Hypergraphs|Analysis, Visualization|[[Code]](https://github.com/pnnl/HyperNetX)|
|Hypergraphx|Python|Hypergraphs|Construction, Analysis, Visualization|[[Code]](https://github.com/HGX-Team/hypergraphx)|
|XGI|Python|Hypergraphs, SCs|Modelling, Analysis, Visualization|[[Code]](https://github.com/xgi-org/xgi)|
|giotto-ph|C++|Vietoris-Rips SCs|Persistent homology|[[Code]](https://github.com/giotto-ai/giotto-p)|
|scikit-tda|Python, scikit-learn|SCs|TDA|[[Code]](https://github.com/scikit-tda)|
|GUDHI|C++, Python|SCs|TDA|[[Code]](https://gudhi.inria.fr/)|
|Teaspoon|Python|Dynamic Systems, Graphs, SCs|Topological signal processing|[[Code]](https://github.com/TeaspoonTDA/teaspoon)|
|TDA.jl|Julia|SCs|TDA|[[Code]](https://github.com/wildart/TDA.jl)|
|JuliaTDA|Julia|SCs|TDA|[[Code]](https://github.com/JuliaTDA)|
|JavaPlex|Java, Matlab|SCs|Persistent homology|[[Code]](https://github.com/appliedtopology/javaplex)|
|giotto-tda|Python, scikit-learn|SCs|TML|[[Code]](https://github.com/giotto-ai/giotto-tda)
|TopologyLayer|Python, Pytorch|SCs|TDL, Persistent homology|[[Code]](https://github.com/bruel-gabrielsson/TopologyLayer)|
|giotto-deep|Python, Pytorch|SCs|TDL|[[Code]](https://github.com/giotto-ai/giotto-deep)|
|torch-tda|Python, Pytorch|SCs|Automatic differentiation, TDA|[[Code]](https://github.com/CompTop/torch-tda)|
|torch_topological|Python, Pytorch|SCs|TML|[[Code]](https://github.com/aidos-lab/pytorch-topological)|
|TopoX|Python, Pytorch|SCs, CellCs, CCs|TML|[[Code]](https://pyt-team.github.io/)|
|DHG|Python, Pytorch|Graphs, Hypergraphs|Deep learning|[[Code]](https://github.com/iMoonLab/DeepHypergraph/)|
|TopoBenchmarkX|Python, Pytorch|Graphs, Hypergraphs, SCs, CellCs, CCs|Benchmark|[[Code]](https://github.com/geometric-intelligence/TopoBenchmark)|

----------
## Related research paper of HOI

<table border="1">
    <thead>
        <tr>
            <th>Category</th>
            <th>Method</th>
            <th>Task</th>
            <th>Venue</th>
            <th>Code Links</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="3">Pattern-based Generative Model</td>
            <td>Thera</td>
            <td>Generation</td>
            <td>KDD'2023</td>
            <td><a href="https://github.com/kswoo97/hypertrans">GitHub</a></td>
        </tr>
        <tr>
            <td>HyperLap</td>
            <td>Generation</td>
            <td>WWW'2021</td>
            <td><a href="https://github.com/young917/www2.1-hyperlap">GitHub</a></td>
        </tr>
        <tr>
            <td>HyRec</td>
            <td>Generation</td>
            <td>WWW'2025</td>
            <td><a href="https://github.com/young917/HyRec">GitHub</a></td>
        </tr>
        <tr>
            <td rowspan="2">Diffusion-based Generative Model</td>
            <td>HYGENE</td>
            <td>Generation, Representation learning</td>
            <td>Preprint'2024</td>
            <td><a href="https://github.com/DorianGailhard/HYGENE">GitHub</a></td>
        </tr>
        <tr>
            <td>DDE</td>
            <td>Generation, Representation learning</td>
            <td>Preprint'2025</td>
            <td>-</td>
        </tr>
        <tr>
            <td rowspan="3">Statistical Inference Method</td>
            <td>BHyRe</td>
            <td>Inference</td>
            <td>Commun.Phys.'2021</td>
            <td><a href="https://github.com/k-zhou/hypergraph-recovery">GitHub</a></td>
        </tr>
        <tr>
            <td>SIEM</td>
            <td>Inference</td>
            <td>Nat.Commun.'2022</td>
            <td><a href="https://github.com/HuanWang2022/reconstruct_simplicial_complex">GitHub</a></td>
        </tr>
        <tr>
            <td>KHiT</td>
            <td>Inference</td>
            <td>NeurIPS'2023</td>
            <td><a href="https://github.com/barahona-research-group/streitberg-interaction">GitHub</a></td>
        </tr>
        <tr>
            <td rowspan="3">Information-Theoretic Approach for HOI</td>
            <td>LHOIF</td>
            <td>Inference</td>
            <td>AISTATS'2025</td>
            <td><a href="https://github.com/neurips2024hoi/nips2024hoi">GitHub</a></td>
        </tr>
        <tr>
            <td>DHETE</td>
            <td>Inference</td>
            <td>Phys.revres.'2024</td>
            <td><a href="https://github.com/danielemarinazzo/TE_decomposition">GitHub</a></td>
        </tr>
        <tr>
            <td>PED</td>
            <td>Inference</td>
            <td>PNAS'2023</td>
            <td>-</td>
        </tr>
        <tr>
            <td rowspan="2">Learning-based Method for HOI</td>
            <td>DCM</td>
            <td>Inference, Representation learning</td>
            <td>ICLR'2024</td>
            <td><a href="https://github.com/spindro/differentiable_cell-complex_module">GitHub</a></td>
        </tr>
        <tr>
            <td>SHyRe</td>
            <td>Inference, Representation learning</td>
            <td>ICLR'2024</td>
            <td>-</td>
        </tr>
        <tr>
            <td rowspan="3">HOT Aware Feature Extraction</td>
            <td>PCN</td>
            <td>Representation learning</td>
            <td>AAAI'2024</td>
            <td><a href="https://github.com/quang-truong/Path-Complex-Networks">GitHub</a></td>
        </tr>
        <tr>
            <td>CliquePH</td>
            <td>Representation learning</td>
            <td>LoG'2024</td>
            <td><a href="https://github.com/DavideBuffelli/CliquePH">GitHub</a></td>
        </tr>
        <tr>
            <td>SIMPLEX2VEC</td>
            <td>Representation learning</td>
            <td>PMLR'2022</td>
            <td><a href="https://github.com/simonepiaggesi/simplex2pred">GitHub</a></td>
        </tr>
        <tr>
            <td rowspan="5">Message Passing for HOT</td>
            <td>CIN++</td>
            <td>Representation learning</td>
            <td>Preprint'2023</td>
            <td><a href="https://github.com/twitter-research/cwn">GitHub</a></td>
        </tr>
        <tr>
            <td>SCN</td>
            <td>Representation learning</td>
            <td>TAPMI'2023</td>
            <td>-</td>
        </tr>
        <tr>
            <td>CSMPNs</td>
            <td>Representation learning</td>
            <td>ICLR'2024</td>
            <td><a href="https://github.com/congliuUvA/Clifford-Group-Equivariant-Simplicial-Message-Passing-Networks">GitHub</a></td>
        </tr>
        <tr>
            <td>Wit-TopoPool</td>
            <td>Representation learning</td>
            <td>AAAI'2023</td>
            <td><a href="https://github.com/topologicalpooling/TopologicalPool">GitHub</a></td>
        </tr>
        <tr>
            <td>TopoGDN</td>
            <td>Representation learning</td>
            <td>CIKM'2024</td>
            <td><a href="https://github.com/ljj-cyber/TopoGDN">GitHub</a></td>
        </tr>
        <tr>
            <td rowspan="3">Spectral-based Learning for HOT</td>
            <td>BScNets</td>
            <td>Representation learning</td>
            <td>AAAI'2022</td>
            <td><a href="https://github.com/BScNets/BScNets">GitHub</a></td>
        </tr>
        <tr>
            <td>HiGCN</td>
            <td>Representation learning</td>
            <td>AAAI'2024</td>
            <td><a href="https://github.com/Yiminghh/HiGCN">GitHub</a></td>
        </tr>
        <tr>
            <td>SNN-PDE</td>
            <td>Representation learning</td>
            <td>AAAI'2024</td>
            <td><a href="https://github.com/yuzhouguangc/SNNPDE">GitHub</a></td>
        </tr>
    </tbody>
</table>

----------

Emails:	mingzhang23@mails.jlu.edu.cn

