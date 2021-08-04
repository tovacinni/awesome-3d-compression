# 3D Compression

This is very much work in progress. The categorizations etc are very likely to change.

## Related Surveys / Position Papers

**[Compression is Again Driving the Evolution of Media](https://medium.com/making-vr-human/compression-is-again-driving-the-evolution-of-media-ac77d599d27b#.279r7yezk)**<br>
*Philip A. Chou*<br>

**[Toward Truly Immersive Holographic-Type Communication: Challenges and Solutions](https://ieeexplor.ieee.org/document/8970173)**<br>
*Alexander Clemm, Maria Torres Vega, Hemanth Kumar Ravuri, Tim Wauters, Filip De Turkc*<br>
IEEE Communications Magazine 2020<br>

**[Extremely Interactive and Low-Latency Services in 5G and Beyond Mobile Systems](https://ieeexplore.ieee.org/abstract/document/9464920)**<br>
*Tarik Taleb, Zinelaabidine Nadir, Hannu Flinck, JaeSeung Song*<br>
IEEE Communications Standards Magazine 2021<br>

## Standards

**[MPEG-I: Coded Representation of Immersive Media](https://mpeg.chiariglione.org/standards/mpeg-i)**<br>

**[Emerging MPEG Standards for Point Cloud Compression](https://ieeexplore.ieee.org/document/8571288)**<br>
*Sebastian Schwarz, Marius Preda, Madhukar Budagavi, Pablo Cesar, Philip A. Chou, Robert A. Cohen, Maja Krivokuca, Sebastien Lasserre, Zhu Li, Joan Llach, Khaled Mammou, Rufael Mekuria, Ohji Nakagami, Ernestasia Siahaan, Ali Tabatabai, Alexis M. Tourapis, Vladyslav Zakharchenko*<br>
IEEE JETCAS 2019

**[A Comprehensive Study and Comparison of Core Technologies for MPEG 3-D Point Cloud Compression](https://ieeexplore.ieee.org/document/8945224)**<br>
*Hao Liu, Hui Yuan, Qi Liu, Junhui Hou, Ju Liu*<br>
IEEE Transactions on Broadcasting 2019<br>

**[An overview of ongoing point cloud compression standardization activities: video-based (V-PCC) and geometry-based (G-PCC)](https://www.cambridge.org/core/journals/apsipa-transactions-on-signal-and-information-processing/article/an-overview-of-ongoing-point-cloud-compression-standardization-activities-videobased-vpcc-and-geometrybased-gpcc/56FCAF660DD44348BCB1BCA9B5EC56CF)**<br>
*D. Graziosi, O. Nakagami, S. Kuma, A. Zaghetto, T. Suzuki, A. Tabatabai*
APSIPA Transactions on Signal and Information Processing 2020

## Systems Papers

**[Holoportation: Virtual 3D Teleportation in Real-time](https://dl.acm.org/doi/10.1145/2984511.2984517)**<br>
*Sergio Orts-Escolano, Christoph Rhemann, Sean Fanello, Wayne Chang, Adarsh Kowdle, Yury Degtyarev, David Kim, Philip L Davidson, Sameh Khamis, Mingsong Dou, Vladimir Tankovich, Charles Loop, Qin Cai, Philip A Chou, Sarah Mennicken, Julien Valentin, Vivek Pradeep, Shenlong Wang, Sing Bing Kang, Pushmeet Kohli, Yuliya Lutchyn, Cem Keskin, Shahram Izadi*<br>
ACM UIST 2016<br>

## Point Clouds

### Compression

**[Self-similarity for accurate compression of point sampled surfaces](https://perso.liris.cnrs.fr/julie.digne/articles/pc_compression.html)**<br>
*Julie Digne, Raphaelle Chaine, Sebastien Valette*<br>
Eurographics 2014

**[3D point cloud compression using conventional image compression for efficient data transmission](https://ieeexplore.ieee.org/document/7340499)**<br>
*Hamidreza Houshiar, Andreas Nuchter*
IEEE ICAT 2015

**[Compression and Rendering of Textured Point Clouds via Sparse Coding](https://diglib.eg.org/handle/10.2312/hpg20211284)**<br>
*Kersten Schuster, Philip Trettner, Patric Schmitz, Julian Schakib, Leif Kobbelt*<br>
HPG 2021

## Voxelized Point Clouds

We draw a slight distinction between point clouds and voxelized point clouds. The latter is quantized into
integer coordinates, while the general class of point clouds are still often quantized but not necessarily
into a regular grid.

**[A Volumetric Approach to Point Cloud Compression—Part I: Attribute Compression](https://ieeexplore.ieee.org/document/8676054)**<br>
*Philip A. Chou, Maxim Koroteev, Maja Krivokuca*<br>
IEEE Transactions of Image Processing

**[A Volumetric Approach to Point Cloud Compression—Part II: Geometry Compression](https://ieeexplore.ieee.org/document/8931233)**<br>
*Maja Krivokuca, Philip A. Chou, Maxim Koroteev*<br>
IEEE Transactions of Image Processing

### Compression

**[Compression of 3D Point Clouds Using a Region-Adaptive Hierarchical Transform](https://ieeexplore.ieee.org/document/7482691)**<br>
*Ricardo L. de Queiroz, Philip A. Chou*<br>
IEEE Transactions on Image Processing 2016

**[Geometry and attribute compression for voxel scenes](https://dl.acm.org/doi/10.5555/3058909.3058962)**<br>
*Bas Dado, Timothy R. Kol, Pablo Bauszat, Jean-Marc Thiery, Elmar Eisemann*<br>
Eurographics 2016

**[Real-time compression and streaming of 4D performances](https://dl.acm.org/doi/abs/10.1145/3272127.3275096)**<br>
*Danhang Tang, Mingsong Dou, Peter Lincoln, Philip Davidson, Kaiwen Guo, Jonathan Taylor, Sean Fanello, Cem Keskin, Adarsh Kowdle, Sofien Bouaziz, Shahram Izadi, Andrea Tagliasacchi*<br>
SIGGRAPH Asia 2018

**[Deep Implicit Volume Compression](https://arxiv.org/abs/2005.08877)**<br>
*Danhang Tang, Saurabh Singh, Philip A. Chou, Christian Haene, Mingsong Dou, Sean Fanello, Jonathan Taylor, Philip Davidson, Onur G. Guleryuz, Yinda Zhang, Shahram Izadi, Andrea Tagliasacchi, Sofien Bouaziz, Cem Keskin*<br>
CVPR 2020

**[OctSqueeze: Octree-Structured Entropy Model for LiDAR Compression](https://arxiv.org/abs/2005.07178)**<br>
*Lila Huang, Shenlong Wang, Kelvin Wong, Jerry Liu, Raquel Urtasun*<br>
CVPR 2020

**[MuSCLE: Multi Sweep Compression of LiDAR using Deep Entropy Models](https://arxiv.org/abs/2011.07590)**<br>
*Sourav Biswas, Jerry Liu, Kelvin Wong, Shenlong Wang, Raquel Urtasun*<br>
NeurIPS 2020

**[Region adaptive graph fourier transform for 3d point clouds](https://arxiv.org/abs/2003.01866)**<br>
*Eduardo Pavez, Benjamin Girault, Antonio Ortega, Philip A. Chou*<br>
IEEE ICIP 2020

**[VoxelContext-Net: An Octree based Framework for Point Cloud Compression](https://arxiv.org/abs/2105.02158)**<br>
*Zizheng Que, Guo Lu, Dong Xu*<br>
CVPR 2021<br>

**[Moving Basis Decomposition for Precomputed Light Transport](https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14346)**<br>
*Ari Silvennoinen, Peter-Pike Sloan*
EGSR 2021

### Adaptive Streaming

**[Rate-Utility Optimized Streaming of Volumetric Media for Augmented Reality](https://ieeexplore.ieee.org/abstract/document/8638765)**<br>
*Jounsup Park, Philip A. Chou, Jenq-Neng Hwang*<br>
IEEE JETCAS 2019

**[Towards 6DoF HTTP Adaptive Streaming Through Point Cloud Compression](https://dl.acm.org/doi/pdf/10.1145/3343031.3350917)**<br>
*Jeroen van der Hooft, Tim Wauters, Filip De Turck, Christian Timmerer, Hermann Hellwagner*<br>
ACM MM 2019<br>

## Implicit Neural Networks

### Representation

There is a lot of work in this area. Here, we only list papers which make an experimental comparison in terms of compression (broadly defined).

**[On the Effectiveness of Weight-Encoded Neural Implicit 3D Shapes](https://arxiv.org/abs/2009.09808v3)**<br>
*Thomas Davies, Derek Nowrouzezahrai, Alec Jacobson*<br>
Technical Report

**[Neural Geometric Level of Detail: Real-time Rendering with Implicit 3D Surfaces](https://nv-tlabs.github.io/nglod/)**<br>
*Towaki Takikawa, Joey Litalien, Kangxue Yin, Karsten Kreis, Charles Loop, Derek Nowrouzezahrai, Alec Jacobson, Morgan McGuire, Sanja Fidler*<br>
CVPR 2021

**[ACORN: Adaptive Coordinate Networks for Neural Scene Representation](https://dl.acm.org/doi/abs/10.1145/3450626.3459785)**<br>
*Julien N. P. Martel, David B. Lindell, Connor Z. Lin, Eric R. Chan, Marco Monteiro, Gordon Wetzstein*<br>
SIGGRAPH 2021

### Compression

**[Compressive Neural Representations of Volumetric Scalar Fields](https://arxiv.org/abs/2104.04523)**<br>
*Yuzhe Lu, Kairong Jiang, Joshua A. Levine, Matthew Berger*<br>
EuroVis 2021<br>

**[3D Scene Compression through Entropy Penalized Neural Representation Functions](https://ieeexplore.ieee.org/document/9477505)**<br>
*Thomas Bird, Johannes Balle, Saurabh Singh, Philip A. Chou*<br>
IEEE PCS 2021<br>


**[]()**<br>
**[]()**<br>
**[]()**<br>
**[]()**<br>
**[]()**<br>





