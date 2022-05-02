# Survey of 3D Compression and Streaming

Media formats are moving beyond 1D audio and 2D images which are viewed at static viewing angles and scale
to 3D content which are viewed from dynamic viewing angles and scale. This has broad implications in 
gaming, virtual concerts, television, augmented reality, and more. Compression and streaming are at the core 
of the design of the next generation of media systems, and 3D brings new challenges which require innovations 
in algorithms as well as systems. 

This repository collects papers and talks and blog posts which broadly discuss compression and streaming for
3D content. This is an exciting field which combines computer graphics, computer vision, machine learning,
multimedia, systems, signal processing, information theory, security, and more!

This is very much work in progress and missings lots of work. The categorizations etc are very likely to change.

## Related Surveys / Position Papers / Broadly Applicable Papers


**[Compression is Again Driving the Evolution of Media](https://medium.com/making-vr-human/compression-is-again-driving-the-evolution-of-media-ac77d599d27b#.279r7yezk)**<br>
*Philip A. Chou*<br>

**[State-of-the-art in Compressed GPU-Based Direct Volume Rendering](https://www.ifi.uzh.ch/dam/jcr:00000000-1fe0-1a53-ffff-ffff94c9f943/CompressedDVR.pdf)**<br>
*Marcos Balsa Rodríguez, Enrico Gobbetti, Jose Antonio Iglesias Guitian, Maxim Makhinya, Fabio Marton, Renato Pajarola, Susanne K Suter*<br>
Eurographics State-of-the-Art Reports 2014<br>

**[3D Mesh Compression: Survey, Comparisons, and Emerging Trends](https://dl.acm.org/doi/abs/10.1145/2693443?casa_token=KkY70WPF1oYAAAAA:qizzVOiLw7tkICfJBgdCTUvDyaTOc8Rc7-KiF5m3mR1Ady-Ec3vLOmV_5gjl52h7NiMvuqfNAKI6)**<br>
*Adrien Maglo, Guillaume Lavoue, Florent Dupont, Celine Hudelot*<br>
Eurographics State-of-the-Art Reports 2015<br>

**[Nonlinear Transform Coding](https://arxiv.org/abs/2007.03034)**<br>
*Johannes Ballé, Philip A. Chou, David Minnen, Saurabh Singh, Nick Johnston, Eirikur Agustsson, Sung Jin Hwang, George Toderici*<br>
IEEE Journal of Selected Topics in Signal Processing 2020<br>

**[Toward Truly Immersive Holographic-Type Communication: Challenges and Solutions](https://ieeexplor.ieee.org/document/8970173)**<br>
*Alexander Clemm, Maria Torres Vega, Hemanth Kumar Ravuri, Tim Wauters, Filip De Turkc*<br>
IEEE Communications Magazine 2020<br>

**[Extremely Interactive and Low-Latency Services in 5G and Beyond Mobile Systems](https://ieeexplore.ieee.org/abstract/document/9464920)**<br>
*Tarik Taleb, Zinelaabidine Nadir, Hannu Flinck, JaeSeung Song*<br>
IEEE Communications Standards Magazine 2021<br>

**[Neural Fields in Visual Computing and Beyond](https://arxiv.org/abs/2111.11426)**<br>
*Yiheng Xie, Towaki Takikawa, Shunsuke Saito, Or Litany, Shiqin Yan, Numair Khan, Federico Tombari, James Tompkin, Vincent Sitzmann, Srinath Sridhar*<br>
Eurographics State-of-the-Art Reports 2022<br>

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

**[GigaVoxels: ray-guided streaming for efficient and detailed voxel rendering](https://dl.acm.org/doi/abs/10.1145/1507149.1507152)**<br>
*Cyril Crassin, Fabrice Neyret, Sylvain Lefebvre, Elmar Eisemann*<br>
I3D 2009<br>

**[Holoportation: Virtual 3D Teleportation in Real-time](https://dl.acm.org/doi/10.1145/2984511.2984517)**<br>
*Sergio Orts-Escolano, Christoph Rhemann, Sean Fanello, Wayne Chang, Adarsh Kowdle, Yury Degtyarev, David Kim, Philip L Davidson, Sameh Khamis, Mingsong Dou, Vladimir Tankovich, Charles Loop, Qin Cai, Philip A Chou, Sarah Mennicken, Julien Valentin, Vivek Pradeep, Shenlong Wang, Sing Bing Kang, Pushmeet Kohli, Yuliya Lutchyn, Cem Keskin, Shahram Izadi*<br>
ACM UIST 2016<br>

**[Project Startline: A high-fidelity telepresence system](https://research.google/pubs/pub50903/)**<br>
*Jason Lawrence Dan B Goldman Supreeth Achar Gregory Major Blascovich Joseph G. Desloge Tommy Fortes Eric M. Gomez Sascha Häberling Hugues Hoppe Andy Huibers Claude Knaus Brian Kuschak Ricardo Martin-Brualla Harris Nover Andrew Ian Russell Steven M. Seitz Kevin Tong*<br>
ACM Transactions on Graphics 2021<br>

**[Nanite: A Deep Dive](https://advances.realtimerendering.com/s2021/Karis_Nanite_SIGGRAPH_Advances_2021_final.pdf)**<br>
*Brian Karis, Rune Stubbe, Graham Wihlidal*<br>
ACM SIGGRAPH 2021, Advances in Real-time Rendering in Games<br>

## Continuous Point Clouds

### Compression

**[Self-similarity for accurate compression of point sampled surfaces](https://perso.liris.cnrs.fr/julie.digne/articles/pc_compression.html)**<br>
*Julie Digne, Raphaelle Chaine, Sebastien Valette*<br>
Eurographics 2014

**[3D point cloud compression using conventional image compression for efficient data transmission](https://ieeexplore.ieee.org/document/7340499)**<br>
*Hamidreza Houshiar, Andreas Nuchter*<br>
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

**[Point Cloud Attribute Compression with Graph Transform](https://ieeexplore.ieee.org/abstract/document/7025414)**<br>
*Cha Zhang, Dinei Florencio, Charles Loop*<br>
IEEE ICIP 2014

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
*Ari Silvennoinen, Peter-Pike Sloan*<br>
EGSR 2021

### Post-processing

**[Deep Geometry Post-Processing for Decompressed Point Clouds](https://arxiv.org/abs/2204.13952)**<br>
*Xiaoqing Fan, Ge Li, Dingquan Li, Yurui Ren, Wei Gao, Thomas H. Li*<br>
ArXiv, 2022

### Adaptive Streaming

**[Rate-Utility Optimized Streaming of Volumetric Media for Augmented Reality](https://ieeexplore.ieee.org/abstract/document/8638765)**<br>
*Jounsup Park, Philip A. Chou, Jenq-Neng Hwang*<br>
IEEE JETCAS 2019

**[Towards 6DoF HTTP Adaptive Streaming Through Point Cloud Compression](https://dl.acm.org/doi/pdf/10.1145/3343031.3350917)**<br>
*Jeroen van der Hooft, Tim Wauters, Filip De Turck, Christian Timmerer, Hermann Hellwagner*<br>
ACM MM 2019<br>

## Neural Fields

Neural fields offer a new paradigm for compression which is based on function fitting (akin to some earlier
works on compression via polynomial fitting, etc). Eventually I will write something which explains why
neural fields might be a cool alternative / complementary to traditional voxel-adjacent compression methods.

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

**[BACON: Band-limited Coordinate Networks for Multiscale Scene Representation](https://arxiv.org/abs/2112.04645)**<br>
*David B. Lindell, Dave Van Veen, Jeong Joon Park, Gordon Wetzstein*<br>
ArXiv 2021

### Compression

**[Compressive Neural Representations of Volumetric Scalar Fields](https://arxiv.org/abs/2104.04523)**<br>
*Yuzhe Lu, Kairong Jiang, Joshua A. Levine, Matthew Berger*<br>
EuroVis 2021<br>

**[3D Scene Compression through Entropy Penalized Neural Representation Functions](https://ieeexplore.ieee.org/document/9477505)**<br>
*Thomas Bird, Johannes Balle, Saurabh Singh, Philip A. Chou*<br>
IEEE PCS 2021<br>

**[NeRV: Neural Representations for Videos](https://openreview.net/forum?id=BbikqBWZTGB)**<br>
*Hao Chen, Bo He, Hanyu Wang, Yixuan Ren, Ser-Nam Lim, Abhinav Shrivastava*<br>
NeurIPS 2021<br>

**[COIN: COmpression with Implicit Neural Representations](https://arxiv.org/abs/2103.03123)**<br>
*Emilien Dupont, Adam Goliński, Milad Alizadeh, Yee Whye Teh, Arnaud Doucet*<br>
ICLR 2021 Neural Compression Workshop<br>

**[COIN++: Data Agnostic Neural Compression](https://arxiv.org/abs/2201.12904)**<br>
*Emilien Dupont, Hrushikesh Loya, Milad Alizadeh, Adam Goliński, Yee Whye Teh, Arnaud Doucet*<br>
ArXiv 2022<br>

**[LVAC: Learned Volumetric Attribute Compression for Point Clouds using Coordinate Based Networks](https://arxiv.org/abs/2111.08988)**<br>
*Berivan Isik, Philip A. Chou, Sung Jin Hwang, Nick Johnston, George Toderici*<br>
ArXiv 2021<br>

**[Implicit Neural Video Compression](https://arxiv.org/abs/2112.11312)**<br>
*Yunfan Zhang, Ties van Rozendaal, Johann Brehmer, Markus Nagel, Taco Cohen*<br>
ArXiv 2021<br>

**[]()**<br>
**[]()**<br>
**[]()**<br>
**[]()**<br>
**[]()**<br>





