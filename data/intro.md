## 1. 引言

自从1895年被伦琴首次发现以来，X射线已经成为物理、化学、生物、材料、医学等多学科重要的研究和诊断工具。


### 1.1 X射线自由电子激光
#### 1.1.1 X射线自由电子激光的发展历史及现状

XFEL的第一个重要概念波荡器是由Motz在1951年提出的：当相对论性电子通过具有周期性的磁铁阵列时可以在毫米波尺度内产生相干辐射[Motz@1951]。1953年Motz及其同事利用斯坦福线性加速器的3-5MeV电子束和平板波荡器，成功产生了毫米波波长的相干辐射。当电子能量提高到100MeV时，可以产生非相干的可见光[Motz@1953]。Motz的理论和实验表明，利用聚束装置和波荡器可以实现电子的相干辐射，但是对于更短的波长则遇到了很大的困难。比如产生1Å波长的相干辐射，要将电子束压缩到十分之一波长，这在工程上很难实现。1960年Philips在Ubitron（一个基于波荡器的微波源）的工作表明电子在通过波荡器时可以发生自发的调制（bunching），自发辐射的能量来自于电子在轴向方向的动能[Philips@1988]。

1971年Madey提出了自由电子激光（FEL）的概念。在FEL体系内，电磁波被纳入到电子-波荡器系统中，Madey从量子力学的角度，利用Weizsacker–Williams方法计算了电子束在通过波荡器时的小信号低增益过程，证明了FEL在远红外到可见光波长范围内的可行性，并提出实现紫外甚至X射线波段相干辐射的可能性[Madey@1971]。Madey研究组通过实验进一步证明了FEL的可行性。1976年，Elias等人利用螺旋波荡器成功观测到10.6μm的信号放大（单程增益7%）[Elisa@1976]。1977年，Deacon等实现了第一个振荡器模式的FEL，工作波长为3.4μm，输入电子能量43MeV，光学谐振腔长12.7米[Deacon@]。在振荡器模式的低增益FEL中，电磁辐射在谐振腔中多次往返，每次经过波荡器强度都有小幅增长，经过若干次放大，最终达到很高的能量输出。因为这种模式的FEL在短波长时增益下降，而且需要反射镜实现放大，导致很难进一步向X射线波段发展。

在Madey提出FEL概念并在实验上证实了其可行性之后，许多科学家提出了新的理论解释以及工作模式。Colson[Colson@1977]和Hopf[Hopf@1976]用经典理论解释了Madey的低增益FEL系统。后续的很多研究工作提出了FEL的高增益模式[Kondratenko@1980]。在高增益模式中，电子只在波荡器中通过一次，初始电磁辐射通过指数放大直至饱和。这种模式不需要光学谐振腔，而且可以使用自发辐射作为初始信号，即所谓的自放大自发辐射（Self-Amplified Spontaneouse Emission）。1982年Derbenev等人提出了基于高增益理论，利用1GeV电子的储存环（storage ring）实现软X射线激光的可能性[Derbenev@1982]。

XFEL的产生离不开高质量的电子束，上世纪80年代光阴极微波电子枪等技术的发展使得高增益的短波长FEL成为可能。1998年Hogan等人实现了第一个SASE模式的FEL，工作在红外波段下，实现了600%的增益[Hogan@Hogan-1]，并在几个月后实现12μmFEL的10^5的增益[Hogan@Hogan-2]。2003年德国DESY的Ischebeck研究组利用TESLA实验设施进行了100nmFEL的衍射实验，验证了SASE模式FEL的横向相干性[Ischebeck@2003]。2007年德国FLASH实现了13.7nm的SASE出光，脉冲长度10fs。2009年是XFEL发展历史上的一个重要里程碑，世界上第一个硬X射线波段的自由电子激光设施LCLS建成并投入使用[Emma@2010]，LCLS可以产生最短1.2Å的X射线脉冲，脉冲长度可以在500fs到<10fs区间内调节。2011年日本的SACLA设施建成并出光，可以产生0.6Å波长的脉冲。到目前为止，世界上建成或在建的XFEL设施还包括意大利的FERMI FEL，欧洲的European XFEL，韩国的PAL-XFEL，瑞士的SwissFEL以及我国软X射线波段的SXFEL[Zhao@2016]和硬X射线波段的SHINE[Zhao@2018]。表x.x总结了各个XFEL设施的基本参数。

我国的自由电子激光的相关研究起始于上世纪80年代。1985年，中国科学院上海光学精密机械研究所实现了拉曼型FEL[赵振堂]。1993年，由北京高能物理研究所建设的BFEL实现了红外波段的振荡型FEL，并于12月实现饱和出光，并达到了10^8的功率增益[Xie@1995]。2005年中国工程物理研究院远红外FEL实现出光[Li@2005]。2014年底，我国第一个XFEL装置SXFEL在上海应用物理研究所张江园区动工，其最终目的是产生8.8nm波长的全向干软X射线脉冲，目前已经完成试验装置，用户装置正在建设中。另外，采用超导直线加速器的硬XFEL装置SHINE也已于2018年开始动工建设，首期将建设三条波荡线，提供从软X射线到超硬X射线的飞秒级XFEL激光，脉冲频率高达100万Hz，与美国LCLS-II和欧洲的European XFEL相当。


#### 1.1.2 X射线自由电子激光的物理原理




#### 1.1.3 X射线自由电子激光的应用领域


### 1.2 利用X射线衍射方法解析晶体结构的原理


### 1.3 串行晶体学的数据分析流程及现状
#### 1.3.1 串行晶体学与传统的X射线晶体学的区别
#### 1.3.2 串行晶体学的数据分析流程
#### 1.3.3 串行晶体学的发展现状


### 1.4 论文的研究内容和结构安排



Motz, Hans. "Applications of the radiation from fast electron beams." Journal of Applied Physics 22.5 (1951): 527-535.
Motz, Hans, W. Thon, and R. N. Whitehurst. "Experiments on radiation by fast electron beams." Journal of Applied Physics 24.7 (1953): 826-833.
Phillips, Robert M. "History of the ubitron." Nuclear Instruments and Methods in Physics Research Section A: Accelerators, Spectrometers, Detectors and Associated Equipment 272.1-2 (1988): 1-9.
Madey, John MJ. "Stimulated emission of bremsstrahlung in a periodic magnetic field." Journal of Applied Physics 42.5 (1971): 1906-1913.
Elias, Luis R., et al. "Observation of stimulated emission of radiation by relativistic electrons in a spatially periodic transverse magnetic field." Physical Review Letters 36.13 (1976): 717.
Deacon, David AG, et al. "First operation of a free-electron laser." Physical Review Letters 38.16 (1977): 892.
Kondratenko, A. M., and E. L. Saldin. "Generating of coherent radiation by a relativistic electron beam in an ondulator." Part. Accel. 10 (1980): 207-216.
Colson, W. B. "One-body electron dynamics in a free electron laser." Physics Letters A 64.2 (1977): 190-192.
Hopf, F. A., et al. "Classical theory of a free-electron laser." Physical Review Letters 37.18 (1976): 1215.
Derbenev, Ya S., A. M. Kondratenko, and E. L. Saldin. "On the possibility of using a free electron laser for polarization of electrons in storage rings." Nuclear Instruments and Methods in Physics Research 193.3 (1982): 415-421.
Hogan, M., et al. "Measurements of high gain and intensity fluctuations in a self-amplified, spontaneous-emission free-electron laser." Physical review letters 80.2 (1998): 289.
Hogan, M. J., et al. "Measurements of Gain Larger than 10 5 at 12 μ m in a Self-Amplified Spontaneous-Emission Free-Electron Laser." Physical Review Letters 81.22 (1998): 4867.
Ischebeck, R., et al. "Study of the transverse coherence at the TTF free electron laser." Nuclear Instruments and Methods in Physics Research Section A: Accelerators, Spectrometers, Detectors and Associated Equipment 507.1-2 (2003): 175-180.
Ackermann, Wet al, et al. "Operation of a free-electron laser from the extreme ultraviolet to the water window." Nature photonics 1.6 (2007): 336.
Emma, Paul, et al. "First lasing and operation of an ångstrom-wavelength free-electron laser." nature photonics 4.9 (2010): 641.
Pile, David. "X-rays: First light from SACLA." Nature Photonics 5.8 (2011): 456.
赵振堂, and 冯超. "X 射线自由电子激光." 物理 47.8: 481-490.
Xie, Jialin, et al. "The saturation of the Beijing FEL." Nuclear Instruments and Methods in Physics Research Section A: Accelerators, Spectrometers, Detectors and Associated Equipment 358.1-3 (1995): 256-259.
Li, Maozhen, X. Jin, and Z. Xu. "First Lasing of the CAEP FIR-FEL." (2005).
Zhao, Z. T., and D. Wang. "Seeded FEL Experiments at the SDUV-FEL Test Facility." IEEE Transactions on Nuclear Science 63.2 (2016): 930-938.
Zhao, Zhentang, et al. "SCLF: An 8-GeV CW SCRF linac-based X-ray FEL facility in Shanghai." (2018): MOP055.