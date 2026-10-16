---
type: libro
title: "基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建"
author: "赵杨1,2, 赵颖慧1,2, 甄贞1,2*"
categoria: "Tecnología láser, fotogrametría, otros"
paginas: 14
extraccion: "texto"
fuente: "local:E:/DISCIPLINAS, TEXTOS Y MAPAS/Biblioteca digital/Tecnología láser, fotogrametría, otros/High-Precision Digital Elevation Model Reconstruction of the Greater Khingan Forest Area Based on UAV LiDAR.pdf"
convertido: 2026-10-13
---

# 基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建

> Texto extraído de `Tecnología láser, fotogrametría, otros/High-Precision Digital Elevation Model Reconstruction of the Greater Khingan Forest Area Based on UAV LiDAR.pdf` (14 páginas, texto). El PDF original está en el disco E: (DISCIPLINAS, TEXTOS Y MAPAS\Biblioteca digital); `<!-- p. N -->` marca el inicio de cada página.

<!-- p. 1 -->

森 林 工 程
FOREST ENGINEERING

· XXXX XXXX ·

基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建

赵杨1，2，赵颖慧1，2，甄贞1，2*
（1. 东北林业大学 森林生态系统可持续管理教育部重点实验室，哈尔滨 150040；2. 东北林业大学 林学院，哈尔滨 150040）

摘 要：结合应用辅助信息估计和超分辨率重建思想，以去植被建筑数字高程模型（forest and buildings removed Coper‐
nicus digital elevation model，FABDEM）（30 m）为辅助变量，无人机激光雷达数字高程模型（digital elevation model，
DEM）为目标变量，进行区域尺度精细分辨率（0.5 m）DEM 重建。选择传统双三次（bicubic）插值、简单线性回归
（simple linear regression，SLR）和深度残差网络（deep residual networks，ResNet）3 种方法进行高精度DEM 的重建，采
用最优方法重建大兴安岭林区精细分辨率（0.5 m）DEM 数据（DEM_0.5），通过独立实测精度验证点将重建DEM （DEM_
0.5）与原始FABDEM 和Bicubic法重建的DEM （DEM_b）进行对比分析。结果表明，在重建效率和质量之间，SLR法的表现
最为均衡，其均方根误差（root mean square error，RMSE）、平均绝对误差（mean absolute error，MAE）、偏差（bias）和
具有稳健性的90％分位数绝对偏差（LE90）均优于FABDEM 和Bicubic 法，时间效率与Bicubic 法效率相当，较ResNet 法有
明显提升；在独立的实测精度验证点上，SLR 法重建的DEM_0.5 在RMSE、MAE、Bias 和LE90 误差上表现最优，较FABDEM
分别下降15.0%、15.8%、26.5%和12.1%，较Bicubic插值法重建的DEM分别下降了7.8%、9.4%、12.2%和8.3%。在坡向分
析中，SLR重建结果在8个坡向上均优于FABDEM，在北、东北、东、东南、西、西北6个方向上优于Bicubic方法，表现出
更强的稳定性与地形细节恢复能力。综上所述，基于简单线性回归（SLR）的重建方法最适合应用于大兴安岭林区的精细
分辨率（0.5 m）DEM的重建，这种重建方法聚焦于“轻量、可解释、易应用”的地形重建框架，很好地平衡了重建方法的
成本、可行性和重建质量，为低成本、高效率地获取区域尺度高质量的DEM数据提供新思路。
关键词：简单线性回归；辅助信息；ResNet；DEM；无人机激光雷达；FABDEM；超分辨率重建；复杂地形
中图分类号：TP701 文献标识码：A DOI：10.7525/j.issn.1006-8023.XXXX.XX.001

High-Precision Digital Elevation Model Reconstruction of
the Greater Khingan Forest Area Based on UAV LiDAR
ZHAO Yang1，2，ZHAO Yinghui1，2，ZHEN Zhen1，2* （1. Key Laboratory of Sustainable Forest Ecosystem Management，Ministry of Education，Northeast Forestry University，Harbin
150040，China；2. College of Forestry，Northeast Forestry University，Harbin 150040，China）
Abstract：This study integrated auxiliary information estimation and super-resolution reconstruction techniques to per⁃
form regional-scale fine-resolution（0. 5 m）DEM reconstruction，using the forest and buildings removed Copernicus digi⁃
tal elevation model（30 m）as auxiliary data and unmanned aerial vehicle laser scanning（ULS）DEM as the target vari⁃
able. Three methods-traditional bicubic interpolation，simple linear regression （SLR），and deep residual networks
（ResNet）-were employed for high-precision DEM reconstruction. The optimal method was then applied to reconstruct in-situ the 0. 5 m DEM （DEM_0. 5） of the Greater Khingan forest region. Independent validation points were used to
compare DEM_0. 5 with the original FABDEM and the bicubic-interpolated DEM（DEM_b）. Results indicated that the
SLR method achieved the best balance between reconstruction efficiency and quality. Its root mean square error
（RMSE），mean absolute error （MAE），bias，and 90% quantile absolute error （LE90） were all superior to FABDEM

收稿日期：2026-01-27
基金项目：国家重点研发计划青年科学家项目（2023YFF1305900）；黑龙江省自然科学基金项目（LH2023C040）。
第一作者简介：赵杨，硕士研究生。研究方向为林业遥感和地理信息系统。E-mail：mimi@nefu. edu. cn
\* 通信作者：甄贞，博士，教授。研究方向为遥感与地理信息科学。E-mail：zhenzhen@nefu. edu. cn
引文格式：赵杨，赵颖慧，甄贞. 基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建［J］. 森林工程，XXXX，XX（XX）：1-14.

ZHAO Yang，ZHAO Yinghui，ZHEN Zhen. High-Precision Digital Elevation Model Reconstruction of the Greater Khingan Forest Area Based on

UAV LiDAR［J］. Forest Engineering，XXXX，XX（XX）：1-14.

<!-- p. 2 -->

2 森 林 工 程

and bicubic interpolation，with time efficiency comparable to bicubic interpolation and significantly higher than ResNet.
At independent validation points，the DEM_0. 5 reconstructed by SLR showed the best performance in RMSE，MAE，
Bias，and LE90，decreasing by 15. 0%，15. 8%，26. 5%，and 12. 1% relative to FABDEM，and by 7. 8%，9. 4%，
\12. 2%，and 8. 3% relative to bicubic interpolation，respectively. Slope-aspect analysis further showed that SLR recon⁃
struction outperformed FABDEM across all eight slope directions and exceeded bicubic interpolation in six directions
（N，NE，E，SE，W，NW），demonstrating higher stability and superior terrain detail recovery. In conclusion，the SLR-
based reconstruction method is the most suitable for fine-resolution（0. 5 m）DEM generation in the Greater Khingan re⁃
gion. Its lightweight，interpretable，and easily applicable framework effectively balances reconstruction cost，feasibil⁃
ity，and accuracy，providing a practical solution for low-cost，high-efficiency acquisition of high-quality regional DEMs.
Keywords：Simple linear regression；ancillary information；ResNet；DEM；UAV LiDAR；FABDEM；super resolution
reconstruction；complex terrain

包括其上所有物体（植被、建筑物等）在内的上表面高
0　引言
度，后者表示裸露地面的高度，而地球表面往往被各种
地形特征是地球表面特定区域内地势起伏与地形 地物覆盖，难以直接获取精确的地面形态，因此基于不
要素的综合表现，在漫长的地质演化过程中内外力的 同卫星传感器获取的全球DEM，多包含森林植被、建
相互作用中形成了地形［1］，微小变化就会引起土壤、植 筑物等地物，严格意义上是DSM［11］。随着卫星平台更
被的显著差异，进而影响生态系统碳循环。数字高程 新和计算资源提升，研究重点转向生产移除地表物体
模型（digital elevation model，DEM）是地形的数字化表 高度的DEM 产品（在本研究指的是DTM，下同）。例
达，是描述及分析地形特征的基础数据，蕴含丰富的地 联手推出了 如，Fathom 与布里斯托尔大学FloodLab
数据获取主要依赖传统地面测量、数 的“裸地”版本去植被建筑数字高程模型形信息［2］。DEM COP DEM
字摄影测量、光学遥感和合成孔径雷达（synthetic aper⁃ （forest and buildings removed Copernicus DEM，FAB⁃
质量的重要体现，精度 ture radar interferometry，InSAR）干涉测量等方式［3］，实 DEM）［12］。尺度和精度是DEM
际应用中存在不同的局限性。传统地面测量（人工野 的垂直误差，尺度包括空间分辨率和空间覆盖 指DEM
数据精度高，但难以 范围两方面。这些产品在尺度和精度上有明显局限外测量等）以单点采集为主，DEM
满足高精度DEM 数据的大尺度需求［4］。数字摄影测 性，空间分辨率多为30~90 m，在局部区域实际精度都
量指基于高分辨率立体影像根据摄影测量原理对局部 低于目标设计精度，存在不确定性，作为参数被纳入到
数据，成本较 后续应用模型时会造成模拟分析的结果误差，而高质区域进行精细测绘，获取高精度的DEM
能够更准确地表现实际地表，从而正确推导高、实现过程复杂，同样难以大尺度推广［5］。随着遥感 量的DEM
数据快 地形因子，描绘更为精确的地形特征和细节，这对于需技术的发展，光学遥感和InSAR 为高质量DEM
速、高效地获取提供了有力的技术支撑。但光学遥感 要高精细地形信息的应用至关重要，是灾害评估、精准
技术更易受地形倾角影响，从而 林业和水文建模等领域的刚需［13］。因此，在精度和尺易受天气影响，InSAR
数据 具有重要研究意影响后续生成的三维高程信息的精度，制约DEM 度方面改进DEM，获取高质量DEM
质量［6］。 义。在此背景下，通过发射激光脉冲并接收反射信号，
产品多是通过上述观 目前公开的全球尺度DEM 快速获取地表高质量三维空间信息的激光雷达（light
测手段获取，基于已有资料重新整合而成的产品如美 detection and ranging，LiDAR）测量技术备受关注［14］。
种地形数据源 在空间范围和时效性上有显著优国地质调查局发布的GTOPO30［7］，由8 其中，星载LiDAR
编译而成；雷达衍生产品如航天飞机雷达地形测绘任 构建提供技术支撑，但当前模式 势，为全球尺度DEM
务DEM 和哥白尼数字高程模型（Copernicus DEM， （如GEDI 和ICESat-2）多为稀疏采样，空间不连续［15］；
COP DEM）［8-9］，光学衍生产品如基于先进陆地观测卫 无人机激光雷达（unmanned aerial vehicle laser scan⁃
星上的全色立体遥感成像仪采集的图像生成的 ning，ULS）能穿透植被精确获取空间连续的高分辨率
卫星的观测数据立体摄影测量 地面信息，尺度和精度上有一定的优势，但设备成本 AW3D30 和基于Terra
得到的先进星载热发射和反射辐射仪全球数字高程模 高、性能受自然条件限制，仅适用于局部区域地形的精
作为“数字表 细测绘，难以大范围推广［16］。 型［10］。DEM 的数据提供者多使用DEM
受限于测量设备分辨率、采样率精度和地形测绘 面模型”（digital surface model，DSM）和“数字地表模
的质量很难通过测量手段在短期得 型”（digital terrain model，DTM）的通用表达，前者表示 成本等因素，DEM

<!-- p. 3 -->

赵杨等：基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建 3
到提高，研究发现通过图像超分辨率重建（super reso⁃ 1　材料与方法
lution image reconstruction，SR）能在不更新测绘设备的
技术在重 1. 1　研究区域情况下获取高空间分辨率DEM，验证了SR
大兴安岭林区位于内蒙古自治区东部和黑龙江省建高质量DEM 任务中具有的巨大潜力［17-18］，常见方法
有基于插值、回归和深度学习的方法［19］。传统插值方 北部，地理位置在40°59′—53°33′N，115°05′—125°
万法使用简单，重建速度快，但高频区域性能较差；基于 16′E，如图1 所示。研究区域总面积为25. 3 km2，海 的回归和深度学习能学习到更多高频信息，重建DEM 拔介于148~1 708 m，整体地势呈现西高、东低的特征。
研究重点关注多样的深度 大兴安岭林区属浅山丘陵地带，满足复杂地形定义中质量更高［20］。现有DEM SR
任务的卷积神经网络、 的区域（复学习算法，最初将用于图像SR 的两类：海拔低于500 m 时高差超过100 m 重建任务，并取得了比 或生成对抗网络等算法引入DEM 杂地形Ⅰ）；海拔介于500~2 500 m，高差超过300 m
插值方法更好的表现，但上述方法只能通过浅层网络 坡度超过5°的区域（复杂地形Ⅱ）［23- 24］。提取有限地形信息，重建精度有限［21］。后续研究发现 1. 2　高程验证点的获取
适当增加网络层数能进一步提高重建精度，但随着层
数的不断增加出现了梯度爆炸、消失和网络退化的问 实时动态（real-time kinematic，RTK）载波相位差 分技术是一种常用的卫星定位测量方法，能在野外实
题，深度残差网络（deep residual networks，ResNet）的出 通过引入残差 时得到厘米级定位精度。本研究于2025年8—9月，在现提供了解决思路。验证发现ResNet 所 特征的能力表现出 大兴安岭林区随机布设379 个精度验证点，如图2结构加深网络深度、增强捕捉DEM 的千寻星矩 示，使用垂直精度为±（15+1×10⁻⁶D）mm更好的重建性能［17］。同时，当前区域尺度DEM超分辨 设备获取高程值（D 为基准站到流动站的距离， 数据为单一数据 Srmini率重建研究大多依赖全球开源DEM源，通过下采样构建高、低分辨率的“样本对”来训练网 km），作为与建模样本独立的高程验证点，评估大兴安
络，此类研究在方法论上取得了一定进展，但缺乏对真 岭林区精细分辨率（0. 5 m）DEM产品的数据精度。
\1. 3　ULS数据的获取与预处理
实测绘数据（如ULS DEM）的有效利用，因而重建结果的地形适用性和可靠性仍存在不足［22］。此外，深度学 本研究中应用ULS 数据构建高分辨率（0. 5 m）
习方法通常依赖大规模训练样本，模型结构复杂，参数 DEM数据（ULS DEM）作为重建精细DEM的目标变量。
数量庞大，算力及时间需求高，限制了其在大尺度 于2024—2025 年8 月使用Feima D200 无人机搭载D-
LiDAR200测量系统收集ULS数据，采用自适应地形飞DEM重建中的推广应用。 行，确保点云数据的精度以及完整性。在大兴安岭林
产品可提供区域尺度基 综上所述，全球开源DEM 测绘来补 区随机设置的26 个机载测区，如图1（a）所示，采集了础数据支撑，ULS 技术能以局部高质量DEM 数据。测区地形起伏大，植被覆盖 技术可指导如何低成本、高效率 大约25 km2的ULS充真实地形信息，SR 度高，因此采用机器滤波与人工判读相结合的方式分 方面优势，回归“轻地提升DEM 质量，本研究融合这3 类地面点。先基于改进的渐进加密三角网滤波算量、可解释、易应用”的地形重建框架，在平衡重建成本
法［25］对地面点自动分类，采用人工编辑的方式对错 重建。具和质量的前提下，实现区域尺度的精细DEM
体研究目标包括：1）基于运用辅助信息的统计思想，以 分、少分或多分的点进行正确分类。基于提取的地面 点数据，基于克里金插值法［26］，以0. 5 m的格网尺寸构低分辨率但能全区域覆盖的FABDEM（30 m）数据为辅 数据（即 建DEM，得到测区0. 5 m 空间分辨率DEM助变量、高分辨率但只有小区域覆盖的ULS DEM（0. 5 m）
数 ULS DEM）。为目标变量，通过分层抽样构建高、低分辨率DEM
据对样本集；2）在SR技术的指导下分别通过简单线性 1. 4　辅助变量的获取与预处理
回归（simple linear regression，SLR）与深度学习方法 本研究选择覆盖大兴安岭林区全域的开源FAB⁃
（ResNet）建立辅助变量和目标变量间的关系模型，进 DEM 数据（30 m）作为重建精细DEM 的辅助变量。
的重建研行区域尺度精细空间分辨率（0. 5 m）DEM FABDEM 数据是Fathom 与布里斯托尔大学FloodLab
的“裸地”版本，最新版本为究，并与传统双三次（bicubic）插值方法进行对比分析； 联手推出的COP DEM
3）综合考虑重建方法的成本和结果的准确性，应用最 FABDEM V1-2，可从Google Earth Engine（GEE，https：//
优方法重建大兴安岭林区的精细分辨率（0. 5 m）DEM code. earthengine. google. com/）上获取（数据ID：proj⁃
的高质量重建提 基于数据，为区域尺度下精细分辨率DEM ects/sat-io/open-datasets/FABDEM）。FABDEM
供了新思路和方法参考。 COP DEM 的30 m 空间分辨率DEM 产品（GLO-30），使

<!-- p. 4 -->

4 森 林 工 程

DEM数据基于FABDEM V1-2数据集制作，该图基于审图号为GS（2024）0650号的标准地图制作。
The DEM data is produced based on the FABDEM V1-2 dataset. The map was made based on the standard map with No. GS（2024）0650.
图1　研究区域概况图
Fig. 1 Overview map of the study area

该图基于审图号为GS（2024）0650号的标准地图制作。
The map was made based on the standard map with No. GS（2024）0650.
图2　应用RTK实测的精度验证点分布图
Fig. 2 The distribution of validation points using RTK

<!-- p. 5 -->

赵杨等：基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建 5

用机器学习方法有效地剥离地表植被和建筑物高程， 1. 5. 2　基于深度学习的重建
分辨率以真实地表达“裸地”地面高程［12］。经验证，FABDEM 现有研究表明，卷积神经网络在提升DEM
中来自植被和建筑物的高程伪影得到了显著改善，城 上有巨大应用潜力，增加网络层数，能学习到更深层的
分别减少了 地形特征，但常出现梯度爆炸或消失现象，且运行时间市和森林区域的平均高程误差比GLO-30
数据和独立实测精 长不利于模型训练，使用残差学习能缓解上述网络退 约3. 34 m 和1. 26 m［27］。ULS DEM
度验证点的高程值均为大地高，参考基准WGS84椭球 化问题［31］。因此，本研究选择复杂的ResNet 算法，网
数据的高程值是正高，高程基准是体，而FABDEM 络结构设计如图3所示。整体由30层卷积网络叠加而
EGM08大地水准面。为确保DEM数据的一致性，本研 成，其中第一层实现DEM 的输入，中间为14 个残差模
究统一选择WGS84椭球体为参考基准，将FABDEM 转 块，最后一层为输出层。第一层由宽度为5×5 的卷积
换到WGS84 椭球体上。统一高程基准的转换公 核组成，其余29 层都由64 个宽度为3×3 的卷积核组
式［28］为 成，每次卷积的结果采用ReLU 激活函数进行拟合［32］，
h H N。 = + （1） 此外，每次卷积后对输出进行补零以保证输入输出大
式中：h 为基于WGS84 椭球体的大地高；H 为基于 小一致。引入采用跳跃连接的残差模块，设输入值为
EGM08大地水准面的正高；N为大地水准面差距，表示 x，期望输出为y，F（x）表示残差，函数表示为 y x。 = F(x) + （3） EGM08 大地水准面点沿参考椭球法线方向至WGS84
参考椭球面的距离。重建前，基于FABDEM（30 m）通
过双线性插值方法恢复到目标空间分辨率（0. 5 m），以
实现1∶1 超分辨率重建，高程基准转换应用ENVI 5. 6
的SARscape模块（https：//envi. geoscene. cn/）完成。
\1. 5　区域尺度的精细分辨率（0. 5 m）DEM重建
将与目标变量相关的辅助变量引入估计过程中，
通过建立辅助变量与目标变量间的关系模型，能有效
利用辅助变量的信息来增强估计量的准确性［29］，以此
易于统计思想和SR 技术为指导，结合开源FABDEM
获取、局部测绘ULS DEM 的高质量优势，将FABDEM
（30 m）作为辅助变量，ULS DEM（0. 5 m）为目标变量，
种方法建立高、低分选择简单线性回归和深度学习2
间的关系模型，构建大兴安岭林区精细分辨辨率DEM
率（0. 5 m）DEM重建模型。
\1. 5. 1　基于简单线性回归和传统插值方法的重建
本研究旨在构建一个“轻量、可解释、易推广”的地
图3　基于深度残差网络的DEM超分辨率模型网络结构形重建框架，因此选择了简单线性回归方法建立FAB⁃
DEM（辅助变量）和ULS DEM（目标变量）间的关系模 Fig. 3 Network structure of DEM super-resolution
型，数学计算公式为 model based on deep residual networks
y β0 β1x ε。 = + + （2） 选择平均绝对误差（mean absolute error，MAE）为
损失函数，通过最小化损失函数求解来评估模型，来求式中：y为高分辨率ULS DEM 高程值（0. 5 m）；x为低分
是自变量系 取最优训练成果。为加速模型训练、消除不同样本的辨率DEM 高程值（即FABDEM，30 m）；β0
数；β1 是截距；ε 是模型残差。通过普通最小二乘法来 绝对高程差异，DEM数据被裁剪为96×96大小，通过最
的值后再输入模估计参数，以保证真实高程值与重建结果之间的离差 大最小值法将高程值归一化到0~1
同样需要进行反平方和最小［30］。基于插值的重建方法是根据特定的 型，最终模型输出的精细分辨率DEM
插值核由已知相邻像素值估计未知像素值，众多插值 归一化处理，以便于获取具备真实高程值的DEM。网
框架实现，设置模型初始化学习率为方法中双三次（bicubic）插值表现出最佳精度［20］，因 络基于Pytorch
插值方法为基准方法进行此，本研究选择Bicubic 1×10-5，采取自适应策略调整学习率，验证损失经过
比较。 5 个epoch都无改善时学习率乘以比例系数0. 5。模型

<!-- p. 6 -->

6 森 林 工 程

n每次选取样本数（batch size）为16，最大迭代轮数设置 1 RMSE = i (hi，sr - hi，ref )2。 （4） = 1为200，使用Adam 优化算法（β1=0. 9，β2=0. 999，ε=1× n∑ n
10-8）更新模型权重，为避免过拟合采取早停机制，连 1 | |。 轮验证损失无改善时停止训练，最终得到最佳 MAE= i hi，sr - hi，ref （5） = 1续20 n∑n模型。 1 Bias = i (hi，sr - hi，ref )。 （6） = 1 1. 5. 3　样本的选取 n∑
\| | 本研究在26 块无人机测区范围中分别获取ULS LE90 = Q̂ Δh (0.90)。 （7）
DEM和FABDEM 对应的高、低分辨率DEM“样本对”数 式中：n为样本数量；hi，sr为第i个样本重建DEM的高程
据集。为应对该区域复杂地形带来的挑战，应用分层 值；hi，ref 为第i 个样本的参考高程值（本研究中为ULS
随机抽样的方法，按照大兴安岭林区复杂地形类型的 | | 的 DEM 或独立实测验证点高程值）；Q̂ Δh (0. 90)为Δh
面积比（复杂类型Ⅰ与复杂类型Ⅱ之比为1∶2）分别在 绝对值的90% 分位数；Δh为重建高程值和参考高程值 2 个类型中抽取共6 000 个样本（其中，类型Ⅰ为2 000 间的差异。
个样本，类型Ⅱ为4 000个样本）。在每一层（不同地形
的比例将样本划分为训练集和验证集， 2　结果与分析类型）中按7∶3
个样本用于模其中4 200 个样本用于模型训练，1 800 2. 1　精细分辨率DEM重建方法对比
型验证。在保证不同地形类型代表性的同时，兼顾样 在训练集和验证集上分别基于简单线性回归
本间的空间独立性。 （SLR）、深度学习（ResNet）和传统插值（bicubic）方法 1. 6　精度评价与分析 间的映射关系，对比分析不同 学习高、低分辨率DEM 为验证本研究提出的重建方法的有效性，将简单 和 模型的重建精度，结果见表1。从RMSE、MAE、Bias
方法线性回归法（SLR）、深度学习法（ResNet）和传统插值 LE90精度指标来看，本研究提出的ResNet和SLR
法（bicubic）的重建效果进行对比，应用均方根误差 相比于传统插值方法（bicubic）表现出更好的重建效
下降了（root mean square error，RMSE）、MAE、偏差（bias）和具 果，RMSE 分别下降了2. 8% 和8. 2%，MAE
下有稳健性的90％分位数绝对偏差（LE90）进行定量评 3. 4% 和8. 2%，Bias 下降了81. 4% 和93. 0%，LE90
方法的改善效果更显价。Bias（式中记为Bias）可以反映高程误差的整体趋 降了3. 0% 和9. 8%。其中SLR
的偏差表示地形的表达存在高估或低估。 进势，以与0 著，相比于ResNet 法，其RMSE、MAE、Bias 和LE90
MAE（式中记为MAE）和RMSE（式中记为RMSE）可排除 一步下降了5. 5%、5. 3%、62. 5% 和7. 0%，同时，从时
误差值正负号干扰，准确反映高程误差大小。LE90 间效率看，SLR 法处理时间仅为10. 5 s，与Bicubic插值
（式中记为LE90）具有稳健性，考虑到高程误差有时受 法（10. 3 s）效率相当，但相较于ResNet 法（9 994. 9 s）
到异常值的影响，以及可能存在系统偏差而呈现非正 重建 方法有明显提升，在区域尺度、精细分辨率DEM
态分布［33］。评价指标计算公式为 的时间成本上有极大的优势。

表1　重建模型精度对比
Tab. 1　Accuracy comparison of different reconstruction models

方法 模型形式
RMSE/m MAE/m Bias/m LE90/m t/s
Method Model form

Bicubic — 3.16 2.32 -0.43 5.60 10.3

SLR ULS DEM=1.002×FABDEM-0.8 2.90 2.13 -0.03 5.05 10.5

ResNet — 3.07 2.25 -0.08 5.43 9 994.9

种重建方法的重建精度，本研究进 方法在不同复杂地形区域都比传统插值方法 为全面评估3 和SLR
个维度对比不同方 种一步从高程区间和复杂地形类型2 （bicubic）表现出更高的重建精度，其中SLR 法在2
种复杂地形类型下的精 复杂地形上的重建效果始终最优，在不同地形区域均法的重建精度。对研究区内2
种方法的重建精度在复杂地 具有最高重建精度。不同高程区间下的精度误差统计度误差统计结果见表2，3
种方法的形Ⅰ上的表现均优于复杂地形Ⅱ。3 ResNet 结果如图4所示，3种方法的ResNet和SLR方法在不同

<!-- p. 7 -->

赵杨等：基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建 7

和地形区域均表现出最优性能，稳定性和泛化能力高程区间都比传统插值方法（bicubic）表现出更高的重
方法在所有高程区间中的重建精度也始 更佳。建精度，SLR
终表现最优。结果表明SLR重建方法在不同高程区间
表2　不同复杂地形的重建模型精度对比
Tab. 2　Accuracy comparison of different reconstruction models for different complex terrains

复杂地形类型 方法
RMSE/m MAE/m Bias/m LE90/m
Type of complex terrain Method

Bicubic 3.05 2.22 0.47 5.53

SLR 2.84 2.07 0.45 4.96Ⅰ

ResNet 3.02 2.18 0.61 5.47

Bicubic 3.22 2.37 -0.86 5.63

SLR 2.93 2.16 -0.28 5.05Ⅱ

ResNet 3.09 2.28 -0.43 5.40

图4　对于不同高程区间的重建模型精度对比
Fig. 4 Accuracy comparison of different reconstruction models for different elevation intervals

\2. 2　大兴安岭林区林区精细分辨率DEM 数据重 个不同复杂地形类型的典型区域构建高 选择具有2
建结果 在两类复杂 程剖面，如图10 所示。重建的DEM_0. 5
综合考虑时间成本、重建精度和实际应用的可行 地形上的重建效果相似，在地形变化较小的区域，重
更接近。在谷底和山脊的地形变性，最终选择简单线性回归（SLR）的重建方法完成大 建效果与ULS DEM
表现出一定的兴安岭林区精细分辨率（0. 5 m）DEM（DEM_0. 5）的重 化较大，重建难度高，与ULS DEM
重建结果，并 差距。建，图5 展示了大兴安岭林区整体DEM

<!-- p. 8 -->

8 森 林 工 程

图5　大兴安岭林区精细分辨率DEM数据重建结果
Fig. 5 Reconstruction results of high-resolution DEM data in the Greater Khingan forest region

\2. 3　大兴安岭林区精细分辨率DEM 产品精度 DEM_0. 5）与原始FABDEM 和插值方法重建的DEM
验证 （DEM_b）相比，质量有明显提升。重建的DEM_0. 5产
数据的准确性， 为验证本研究重建的DEM_0. 5 品不仅在空间分辨率上由30 m 提高到0. 5 m，在尺度
进一步通过379 个独立的实测精度验证点对重建 上能覆盖大兴安岭林区，精度上RMSE、MAE、Bias 和
DEM 产品进行进一步的精度验证，并与传统Bicubic LE90 误差也明显下降：与FABDEM 和DEM_b 相比，
插值法的重建结果（DEM_b）和原始低分辨率DEM RMSE分别下降15. 0%和7. 8%，MAE下降了15. 8%和
（FABDEM）进行对比。由表3 可知，在大兴安岭林 7. 1%，Bias 下降了26. 5% 和16. 3%，LE90 下降了
区，应用SLR 方法重建的0. 5 m 空间分辨率DEM（即 12. 1%和4. 1%。
表3　不同DEM数据产品精度验证表
Tab. 3　Accuracy validation of different DEM data m

数据产品 空间分辨率
RMSE MAE Bias LE90
Data product Spatial resolution

FABDEM 30 3.06 2.40 0.49 4.88

DEM_b 0.5 2.82 2.23 0.41 4.68

DEM_0.5 0.5 2.60 2.02 0.36 4.29

分辨率的大兴安岭 注：DEM_0. 5 为基于SLR 方法重建的0. 5 m 分辨率的大兴安岭林区DEM，DEM_b 为传统Bicubic 插值法重建的0. 5 m
林区DEM。
Note：DEM_0. 5 is a 0. 5 m DEM of the Greater Khingan forest region reconstructed using the SLR method，and DEM_b is a 0. 5 m DEM of the
Greater Khingan forest region reconstructed using the traditional bicubic interpolation method.

<!-- p. 9 -->

赵杨等：基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建 9

数据的 根据独立实测精度验证点绘制3 种DEM 值最低且分布最分散（图6（a），标准差σ 为3. 03 m），
所示。 为高程误差频数分布及其对应拟合曲线，如图6 其次是传统插值法重建的DEM（图6（b），标准差σ
的高程误差分布均呈现正态分布，且均存在 误差分布最为集 3 种DEM 2. 80 m），应用SLR 方法重建的DEM
的偏移程度最大 的一定程度的正方向偏移，以FABDEM 中（图6（c），标准差σ 为2. 56 m）。综合不同DEM
（均值μ 偏移程度 各项评估指标和高程误差分布结果来看，空间分辨率 为0. 49 m），以SLR 方法重建的DEM
数据精度的改 最小（DEM_0. 5，均值μ 为0. 36 m）。这表明这些方法 从30 m 到0. 5 m 的重建有助于DEM
的重建方法 善，且简单线性回归重建方法比传统插值方法更稳对地表高程都存在一定的高估，应用SLR
更大程度地减弱了对地表高程的高估现象，更接近“裸 质量最佳，在大 定，重建效果更好，重建的DEM_0. 5
种高程误差曲线的形状和峰值位置 重建任务中有良好的效果和地”地形。其次，3 尺度、精细分辨率DEM
的误差峰 可行性。存在差异。其中，30 m 空间分辨率FABDEM

图6　不同DEM数据的高程误差直方图
Fig. 6 Histogram of elevation error for different DEM data

\2. 4　大兴安岭林区精细分辨率DEM 产品各坡向 在西和东南坡向上的下降幅度较小，在北和东北坡向
精度验证 相 上降低幅度更显著。由图7（b）可知，与FABDEM
对大兴安岭林区不同DEM 在8 个坡向（北、东北、 比，DEM_0. 5 的LE90 误差在各坡向上误差有不同程
的分布东、东南、南、西南、西和西北）的RMSE 和LE90 度改善，下降了1. 1%~21. 1%，在西坡向的改善最小，
进行分析。由图7（a）可知，应用SLR 方法重建DEM 在北坡向的改善最显著。与传统插值法重建的DEM
在 误差在南和西南（即DEM_0. 5）的RMSE 误差相较于原始FABDEM （即DEM_b）相比，DEM_0. 5 的LE90
方向上略高，在其余坡向上都有不同程度的改善，下降所有坡向上均有明显改善，下降了10. 2%~21. 5 %，在
西坡向的改善最小，在东北坡向的改善最显著。与传 了0. 9%~22. 7%，在东南坡向上下降幅度最小，在北和
方法在西南、南统插值重建的DEM（即DEM_b）相比，仅在西南坡向上 东北坡向降低幅度更显著。针对SLR
的现象，进一步统计样本中各 RMSE 略高，其余各坡向上下降了3. 0%~19. 7%，其中 坡向精度略低于DEM_b

<!-- p. 10 -->

10 森 林 工 程

图7　不同DEM数据的（误差在各坡向的分布
Fig. 7 The distribution of different DEM data in different aspects

可知，南向及西南向坡面在样 偏差，是反映复杂地形下“裸地”地形的最佳全球坡向分布情况。由图8
本集中的占比偏低（\<10%），重建过程中更易被北向、 DEM［27］。
东北向等主导坡向的地形趋势所影响，从而在西南、南 种主流 将GLO-30、MERIT DEM 和FABDEM 共3
坡向上产生相对更高的误差，精度较低。 DEM数据的高程基准统一转换为WGS84椭球体，基于
个独立的实测精度验证点进行高程精度的对比与 379
数据的误差统计指标结果。由表 分析，得到3 种DEM
4 可知，FABDEM 的误差指标均优于GLO-30，这与
数据进行误差校正而生成的事 FABDEM 是由GLO-30
存在不同程度的正方向偏移，以 实相符。3 种DEM
的偏移 GLO-30的偏移最大（Bias为4. 55 m），FABDEM
最小（Bias为0. 49 m）。这表明3种DEM都对大兴安岭
实际上是包含地 林区的地面高程存在高估，GLO-30
面上植被和建筑物高度的DSM，因此整体显著高估；
MERIT DEM 去除了树高，有效改善了高估现象；FAB⁃
去除了植被和建筑物高度，高估程度最小，与现 图8　样本中各坡向占比 DEM
Fig. 8 The proportion of different slope aspects 有研究结论相符［36］。FABDEM 的4种误差统计指标均
最小，精度最优，且最接近“裸地”地形，与其他研究结
within the samples
数据质量更高，满足本研究精细 果一致［9］。FABDEM
数据3　讨论 分辨率DEM 重建任务中低空间分辨率辅助DEM
的需求。
\3. 1　辅助变量（开源DEM）的选择
表4　MERI TDEM、GLO-30和FABDEM的误差指标对比
每两年更 在全球众多的开源DEM 中，COP DEM Tab. 4　Comparison of error index of MERIT DEM，
的平面和高 GLO-30 and FABDEM m新一次，其30 m 空间分辨率产品GLO-30
程精度较高，被认为是全球DEM 的“黄金标准”［34］。 数据产品 空间分辨率 RMSE MAE Bias LE90
进行误差 Data product Spatial resolution90 m 空间分辨率的MERIT DEM 对已有DEM
校正，去除树高偏差以及绝对偏差、散斑噪声和条带 MERIT DEM 90 5.82 4.74 1.70 9.14
化，比其他全球DEM 更接近DTM，但尚未完全去除全 GLO-30 30 5.69 4.13 4.55 9.06
为基球范围的建筑物偏差［35］。FABDEM 以GLO-30 FABDEM 30 3.06 2.40 0.49 4.88
础，基于机器学习法有效移除地表森林植被和建筑物

<!-- p. 11 -->

赵杨等：基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建 11

\3. 2　不同重建方法的特点及应用条件 重建 从DEM SR 技术来看，现有区域尺度的DEM
重建方法的本 数据利用深度学习技 本研究提出的区域尺度精细DEM 多以单一来源的低分辨率DEM
质是应用辅助信息估计和图像超分辨率重建思想的结 数据的空间分辨率大多 术实现，使用的低分辨率DEM
产品丰富但空间分辨率低且精度 为30~90 m，常规转换尺度多为3 倍或4 倍［38］，受基础合，在全球开源DEM
有限的条件下，ULS技术能高效、精细地测绘局部地形， 分辨率和尺度转换因子的限制，很难进行更精细（如
重建问题转换成回归问将区域尺度精细分辨率DEM 0. 5 m、1 m）的重建。本研究提出的地形重建框架基于
题，研究关键在于找到最适当的关系模型。同时考虑区 不同尺度、来源和精度的DEM 的信息互补实现DEM
域尺度精细分辨率DEM 重建问题的“大数据量”特点， SR，提升DEM 的尺度和精度，引入的ULS 测量技术提
在重建质量、方法成本与可行性间找到平衡点，提出“轻 供了空间分辨率1 m 或更高的目标地形信息，让0. 5 m
量、可解释、易应用”的大尺度、高精度地形重建框架。 空间分辨率的重建目标成为可能。
从应用辅助信息的思想分析，区域尺度精细分辨 从关系模型的选择来看，简单线性回归算法假设
率DEM 重建方法应用时，ULS 技术测绘得到的ULS 自变量与因变量间呈线性关系，模型具有明确的统计
作为目标变量，空间分辨率高且精度接近真实地 学意义，易于解释；模型参数少，训练和调参速度快，计DEM
个条件：辅助变 算简单高效；同时对数据的要求较低，通常仅需基础预形。辅助变量的选择需要满足以下3
量在研究区域全覆盖；获取成本更低；辅助变量与目标 处理即可投入训练。深度学习算法则能够从大量数据
变量有高度的相关性［37］。经验证，本研究中高、低分 中学习到复杂的模式和结构，捕捉到数据中更深层次
之间具有显著相关关系（r辨率DEM 为0. 999 8），如图 的关系，但模型复杂且庞大，需要大量高质量数据和计
9 所示，因此选择FABDEM 的高程值为辅助变量，很好 算资源。本研究使用的低分辨率FABDEM 和高分辨 为地满足了辅助信息易得性、可靠性和相关性要求。为 率ULS DEM 的高程值间具有极强的线性关系（R2
的差异是否具有统计学显 0. 998 9，图9），与线性假设相符合，此时应用深度学习证明SLR 与ResNet/Bicubic 反而易于过拟合和增加成本；同时精细分辨率地形数著性，基于验证集样本高程误差开展配对统计检验。
首先采用Shapiro-Wilk 检验对SLR 与ResNet、Bicubic 据的构建需要大数据量训练，这给深度学习算法的时 间效率和计算力带来较大的压力，使得其在区域尺度的误差差值进行正态性检验，结果表明差值均不满足
正态分布假设（P\<0. 05）。因此，进一步采用Wilcoxon 上的应用存在困难，而线性回归方法模型参数少，对算 力需求小，时间效率更高；此外，参数明确的线性回归符号秩检验在整体和不同地形类型上对不同模型间的精
度差异进行统计显著性分析。Wilcoxon符号秩检验结果 模型能直观地解释不同分辨率地形数据间的映射关
表明，整体上SLR模型在重建精度上相较于ResNet方法 系。常见的高程误差变量包括植被覆盖度、地形复杂
和Bicubic插值方法均具有统计显著优势（P\<0. 05）。 度和土地利用类型等［39］，相比加入更多变量的多变量 之间具有非常 回归方法，本研究中高、低分辨率DEM
作为单 强的线性相关关系，进一步表明粗分辨率DEM
一变量输入已满足研究需要，再加入植被、建筑物等外
源变量可提供的解释力程度很小，并且会极大地增加
计算量，因此本研究选择了适合单变量回归的简单线
性回归作为超分辨率重建方法。简单线性回归方法体
现出时间和算力成本低、可解释性强、重建精度更高的
特点，既能满足精度要求，又能满足大尺度、高效率的
重 工作需求，适合应用到区域尺度精细分辨率的DEM
建中。
\3. 3　研究局限性与展望
重建方法 尽管本研究提出的区域尺度精细DEM
技术的优 图9　基于4200个训练集样本的FABDEM—ULS 充分结合了应用辅助信息的统计思想和SR
DEM散点图及线性拟合关系 的高效率、高质量重 势，并在大尺度精细分辨率DEM
Fig. 9 FABDEM-ULS DEM scatter plot and linear fitting 建任务中取得了良好效果，但仍存在一定局限性，如：
relationship based on 4200 training samples 首先，受硬件条件、计算资源和时间成本限制，本研究

<!-- p. 12 -->

12 森 林 工 程

在深度学习超参数设置上主要依赖经验选取，未能对 8. 3%），精度表现更佳。同时，SLR 法重建的DEM_0. 5
所有参数进行更大范围的系统化搜索，从而限制 在8个坡向（北、东北、东、东南、南、西南、西和西北）上
模型精度；其次，受生产效率所限，本研究尚未 ResNet 精度均优于原始DEM 数据（FABDEM），且在北、东北、
结果， 个方向上的误差精度表现优于生成覆盖全大兴安岭区域的深度学习重建DEM 东、东南、西、西北共6
因此无法将其与独立高程验证点进行精度评估。在未 传统Bicubic插值法重建的DEM。因此，基于简单线性
来仍需进一步深化和完善，随着深度学习理论和计算 回归（SLR）的重建方法最适合应用于大兴安岭林区的
的重建，这种重建方法聚焦设备的持续发展，更强的算力、更轻量化的网络结构和 精细分辨率（0. 5 m）DEM
自动化超参数优化方法将为构建更大规模、更精确的 于“轻量、可解释、易应用”的地形重建框架，为类似区
重建提供条件，从而进一步提升模型对真实地形 提供了DEM 域低成本、高效率地获取区域尺度高质量DEM
细节的捕捉能力。 新思路，也为需要高质量地形信息的相关应用奠定了
重建的准确性受到辅助 基础。在数字林业与智慧林业建设背景下具有良好的 此外，精细分辨率DEM
数据产品不确定性的影响，同时样本抽样过程中 应用潜力，为森林资源精细化空间表达、林业信息化管DEM
的不确定性对最终重建结果也会产生影响。尽管本研 理平台构建以及智能化经营决策提供了可靠的精细地
产品，并在样本设置中 重建质量在大兴安岭林区表现究选择了精度较高的FABDEM 形数据支撑。但DEM 自身的不确 出一定程度的坡向分异，在西南和南坡向重建效果略考虑了复杂地形的分布特征，但辅助DEM
定性以及样本选取的空间代表性仍可能对最终重建结 应用时，可以根据 差，因此未来进行相关研究和DEM果产生影响。未来随着技术发展，可进一步获取质量 不同区域间的地形特征差异进行训练数据抽样方案的
作为辅助数更高、误差结构更稳定的低分辨率DEM 重建方法的精度 调整，更进一步提升精细分辨率DEM据，并构建更全面反映地形起伏特征的样本体系，从而 和普适性。
降低重建结果的不确定性，增强模型泛化能力和细节
恢复能力。 参 考 文 献
我国数字高程模型与数字地形分析研究进展4　结论 ［1］ 汤国安.
［J］. 地理学报，2014，69（9）：1305-1325.
数据的传统解决方 TANG G A. Progress of DEM and digital terrain analysis in 获得高质量精细分辨率DEM
案是提高测量设备的精度，但这个过程困难、昂贵且耗 China［J］. Acta Geographica Sinica，2014，69（9）：1305时。在此背景下，本研究以FABDEM（30 m）作为辅助 1325.
复杂地形条件下星载变量、ULS DEM（0. 5 m）为目标变量进行大兴安岭林区 ［2］ 张锦瑞，朱建军，万阿芳，等.
重建，选择简单线性回归 武汉大学精细分辨率（0. 5 m）DEM LiDAR 与InSAR DEM 平面位置校正［J/OL］.
种方法建立高、低分辨率（SLR）、深度学习（ResNet）2 学报（信息科学版），2025：1-13.［2025-01-26］.
DEM 间的关系模型，以传统双三次（bicubic）插值法为 ZHANG J R，ZHU J J，WAN A F，et al. Terrain-consider⁃ 重建方法的对比 ate registration method of spaceborne LiDAR with InSAR基准，进行区域尺度精细分辨率DEM DEM ［J/OL］. Geomatics and Information Science of分析，选择最优重建方法（SLR）实现区域尺度（大兴安 高效且准确地重建。 Wuhan University，2025：1-13.［2025-01-26］.岭林区）精细分辨率（0. 5 m）DEM 和 ［3］ LIN X，ZHANG Q Q，WANG H Y，et al. A DEM super-研究结果表明，与传统Bicubic 插值方法相比，SLR 重建 resolution reconstruction network combining internal and ResNet 重建方法的重建精度表现更佳，其中SLR external learning［J］. Remote Sensing，2022，14（9）：2181.方法精度最优，其RMSE、MAE、Bias 和LE90 较ResNet ［4］ YU C L，WANG Q S，ZHANG Z B，et al. Multi-source data法进一步下降了5. 5%、5. 3%、62. 5% 和7. 0%，且SLR joint processing framework for DEM calibration and fusion 法（10. 5 s）的时间效率远高于ResNet 法（9 994. 9 s）， ［J］. International Journal of Applied Earth Observation 方法在不同高程区间、不同类型的复杂地形上始 SLR and Geoinformation，2025，139：104484.终表现最高重建精度，重建效果更具稳定性。基于最 月球形貌遥感测绘发展现状与 ［5］ 刘成保，薄正，张鹏，等. 高优重建方法（SLR 法）重建整个大兴安岭林区0. 5 m 未来展望［J］. 地球信息科学学报，2025，27（4）：
空间分辨率产品（DEM_0. 5），经过独立验证点验证， 801-819.
较原始高程误差明显下降（RMSE、MAE、Bias 和LE90 LIU C B，BO Z，ZHANG P，et al. Current status and future
FABDEM 分别下降15. 0%、15. 8%、26. 5% 和12. 1%； prospects of lunar topographic remote sensing and mapping
和 ［J］. Journal of Geo-information Science，2025，27（4）： 较Bicubic 插值法下降了7. 8%、9. 4%、12. 2%

<!-- p. 13 -->

赵杨等：基于无人机激光雷达的大兴安岭林区高精度数字高程模型重建 13

801-819. evaluation and correction of ASTER GDEM in China
［6］ KARAKUŞ O，KURUOĞLU E E，ACHIM A. A generalized southeast hilly region by combining ICESat-2 and GEDI
Gaussian extension to the Rician distribution for SAR data［J］. Journal of Geo-information Science，2023，25
image modeling［J］. IEEE Transactions on Geoscience and （2）：409-420.
激光雷达在生态与地学领域 Remote Sensing，2022，60：1-15. ［16］ 陶胜利，王迪，谢欢，等.
全球高分辨率数字高程模型研［7］ 李振洪，李鹏，丁咚，等. 的发展回顾与展望［J］. 遥感学报，2025，29（6）：1963-
究进展与展望［J］. 武汉大学学报（信息科学版），2018， 2004.
43（12）：1927-1942. TAO S L，WANG D，XIE H，et al. Review and prospects
LI Z H，LI P，DING D，et al. Research progress of global of the development of LiDAR in ecology and geosciences
high resolution digital elevation models［J］. Geomatics and ［J］. National Remote Sensing Bulletin，2025，29（6）：
Information Science of Wuhan University，2018，43（12）： 1963-2004.
1927-1942. ［17］ JIANG Y H，XIONG L Y，HUANG X H，et al. Super-reso⁃
［8］ FRANKS S，RENGARAJAN R. Evaluation of Copernicus lution for terrain modeling using deep learning in high
DEM and comparison to the DEM used for Landsat collec⁃ mountain Asia［J］. International Journal of Applied Earth
tion-2 processing［J］. Remote Sensing，2023，15（10）： Observation and Geoinformation，2023，118：103296.
\2509. ［18］ ZHANG R C，BIAN S F，LI H P. RSPCN：Super-resolu⁃
［9］ GOLIN A S，CAMPOS H R，OCHOA C，et al. Assessing tion of digital elevation model based on recursive sub-
open⁃access digital elevation models for hydrological appli⁃ pixel convolutional neural networks［J］. ISPRS Interna⁃
cations in a large scale plain：drainage networks，shallow tional Journal of Geo-Information，2021，10（8）：501.
基于自适应生成对抗网 water bodies and vertical accuracy［J］. Earth Surface Pro⁃ ［19］ 侯旭娟，邓筱曈，花卫华，等.
武汉大学学报（信息 cesses and Landforms，2024，49（15）：5269-5283. 络的DEM 超分辨率重建方法［J］.
［10］ HUANG H B，CHEN P M，XU X Q，et al. Estimating 科学版），2026，51（3）：557-566.
building height in China from ALOS AW3D30［J］. ISPRS HOU X J，DENG X T，HUA W H，et al. DEM super-reso⁃
Journal of Photogrammetry and Remote Sensing，2022， lution reconstruction method based on adaptive generative
185：146-157. adversarial network［J］. Geomatics and Information Sci⁃
［11］ JULZARIKA A，DJURDJANI D. DEM classifications：op⁃ ence of Wuhan University，2026，51（3）：557-566.
portunities and potential of its applications［J］. Journal of ［20］ ZHANG Y F，YU W H. Comparison of DEM super-resolu⁃
Degraded and Mining Lands Management，2019，6（4）： tion methods based on interpolation and neural networks
1897-1905. ［J］. Sensors，2022，22（3）：745.
［12］ HAWKER L，UHE P，PAULO L，et al. A 30 m global map ［21］ ZHANG B，SHI Z，HONG D，et al. Super-resolution re⁃
of elevation with forests and buildings removed［J］. Envi⁃ construction of the 1 arc-second Australian coastal DEM
ronmental Research Letters，2022，17（2）：24016. dataset［J］. Geo-Spatial Information Science，2025，28
［13］ YANG Q，TANG F Q，TIAN Z H，et al. Intelligent pro⁃ （6）：3056.
cessing of UAV remote sensing data for building high-pre⁃ ［22］ ZHU Y，BURLANDO P，TAN P Y，et al. Improving plu⁃
cision DEMs in complex terrain：A case study of loess pla⁃ vial flood simulations with multi-source DEM super-reso⁃
teau in China［J］. International Journal of Applied Earth lution［J］. Natural Hazards and Earth System Sciences
Observation and Geoinformation，2024，134：104187. Discussions，2024，25（7）：1-22.
基于激光雷达的自然资源［14］ 李玉美，郭庆华，万波，等. ［23］ REYES W，EPSTEIN H，LI X，et al. Complex terrain in⁃
三维动态监测现状与展望［J］. 遥感学报，2021，25（1）： fluences ecosystem carbon responses to temperature and
381-402. precipitation［J］. Global Biogeochemical Cycles，2017，31
LI Y M，GUO Q H，WAN B，et al. Current status and pros⁃ （8）：1306-1317.
pect of three-dimensional dynamic monitoring of natural ［24］ 张伟，李爱农，江晓波. 基于DEM的中国山地空间范围
resources based on LiDAR［J］. National Remote Sensing 定量界定［J］. 地理与地理信息科学，2013，29（5）：
Bulletin，2021，25（1）：381-402. 58-63.
的中［15］ 焦怀瑾，陈崇成，黄洪宇. 结合ICESat-2 和GEDI ZHANG W，LI A N，JIANG X B. Study on computing the
高程精度评价与修正 国东南丘陵地区ASTERGDEM area of mountain regions in China based on DEM［J］. Ge⁃
［J］. 地球信息科学学报，2023，25（2）：409-420. ography and Geo-Information Science，2013，29（5）：
JIAO H J，CHEN C C，HUANG H Y. Elevation accuracy 58-63.

<!-- p. 14 -->

14 森 林 工 程

针对山区点云的渐进加密三［25］ 王欢，张翰超，张艳，等. sparseness，and the encoding of optic flow in neural net⁃
角网滤波改进算法［J］. 地理空间信息，2020，18（12）： works［J］. Sensors，2024，24（23）：7453.
数据的开放 27-30. ［33］ 雷秋佳，刘婧，曹新运. 利用机载LiDAR
武汉大学学报（信息科学版）， WANG H，ZHANG H C，ZHANG Y，et al. Improved filter⁃ DEM 产品精度评估［J］.
ing algorithm of progressive TIN densification for point 2025，50（1）：153-163.
cloud in mountain areas［J］. Geospatial Information， LEI Q J，LIU J，CAO X Y. Accuracy evaluation of open
2020，18（12）：27-30. DEM products based on airborne LiDAR data［J］. Geo⁃
点［26］ 李朋飞，张晓晨，严露，等. 复杂地形中机载LiDAR matics and Information Science of Wuhan University，
农业工程学报， 云构建DEM 的插值算法对比［J］. 2025，50（1）：153-163.
2021，37（15）：146-153. ［34］ SIMARD M，DENBINA M，MARSHAK C，et al. A global
LI P F，ZHANG X C，YAN L. Comparison of interpolation evaluation of radar ⁃ derived digital elevation models：
algorithms for DEMs in topographically complex areas SRTM，NASADEM，and GLO⁃30［J］. Journal of Geophysi⁃
using airborne LiDAR point clouds［J］. Transactions of cal Research：Biogeosciences，2024，129（11）：e2023J.
the Chinese Society of Agricultural Engineering，2021，37 ［35］ WANG L H，YANG M，HUANG Z Y，et al. Impacts of
（15）：146-153. digital elevation model elevation error on terrain gravity
［27］ OSAMA N，SHAO Z F，FREESHAH M. The FABDEM field calculations：A case study in the Wudalianchi air⁃
outperforms the global DEMs in representing bare terrain borne gravity gradiometer test site，China［J］. Remote
heights［J］. Photogrammetric Engineering & Remote Sens⁃ Sensing，2024，16（21）：3948.
ing，2023，89（10）：613-624. ［36］ BIELSKI C，LÓPEZ-VÁZQUEZ C，GROHMANN C H，et
的高寒山［28］ 张欢，李弘毅，李浩杰，等. 基于机载LiDAR al. Novel approach for ranking DEMs：Copernicus DEM
区遥感高程数据精度评估［J］. 遥感技术与应用，2021， improves one arc second open global topography［J］.
36（6）：1311-1320. IEEE Transactions on Geoscience and Remote Sensing，
ZHANG H，LI H Y，LI H J，et al. Accuracy evaluation of 2024，62：1-22.
空间相关总体下基于时空二维辅助 remote sensing elevation data in Alpine mountains based ［37］ 杨颖琪，陈光慧.
数理统计与管 on airborne LiDAR［J］. Remote Sensing Technology and 信息的连续性回归抽样估计研究［J］.
Application，2021，36（6）：1311-1320. 理，2025，44（4）：589-606.
大数据背景下贝叶斯模型平均辅助［29］ 陈茜儒，贺建风. YANG Y Q，CHEN G H. The study of successive regres⁃
抽样估计方法研究［J］. 系统科学与数学，2025，45（4）： sion sampling estimation based on two-dimensional spa⁃
1255-1278. tiotemporal auxiliary information under spatial correlation
CHEN Q R，HE J F. The study on Bayesian model averag⁃ population［J］. Journal of Applied Statistics and Manage⁃
ing assisted sampling estimation method in the context of ment，2025，44（4）：589-606.
big data［J］. Journal of Systems Science and Mathematical ［38］ WANG H E，XIONG L Y，HU G H，et al. DEM super-
Sciences，2025，45（4）：1255-1278. resolution framework based on deep learning：Decompos⁃
［30］ NEWTON I H，HASAN M H，RAZZAQUE S，et al. As⁃ ing terrain trends and residuals［J］. International Journal
sessment of climate-induced rice yield using ordinary of Digital Earth，2024，17（1）：2356121.
的新疆 least squares （OLS） regression analysis：a case study ［39］ 章诗芳，赵尚民，樊晶莹. 基于ICESat-2/ATL08
from coastal context［J］. Earth Systems and Environment， 昆仑山地区全球多源DEM 数据精度验证与评价［J］.
2024，8：1437-1451. 地理与地理信息科学，2025，41（2）：40-46.
［31］ CAO H Y，XIONG L Y，WANG H G，et al. Integrating hy⁃ ZHANG S F，ZHAO S M，FAN J Y. Accuracy validation
drological knowledge into deep learning for DEM super- and evaluation of global multi-source DEM data in the
resolution［J］. International Journal of Geographical Infor⁃ Kunlun Mountains of Xinjiang based on ICESat-2/ATL08
mation Science，2025，39（2）：301-325. ［J］. Geography and Geo-Information Science，2025，41
［32］ LAYTON O W，PENG S Y，STEINMETZ S T. ReLU， （2）：40-46.
