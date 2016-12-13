1、2015基于全局距离的自适应 LLE 方法研究及人体行为应用   解决了稀疏问题
2、2014基于最小剩余方差的LLE改进算法_吴学斌  计算K,D
3、2013一种改进的局部线性嵌入超分辨率重建算法_曹明明 
   这里选取K的时候，先求10个近邻时候的平均值，小于平均值的才作为近邻。
   避免了 贡献小、距离较远的数据被选取后导致最后的嵌入结果误差增大。

4、2007局部线性嵌入算法的稳健性改进及有监督扩展
   2.4讲解LLE的问题以及研究者的解决方案
   .deRidderD.,DuinR.P.W.,Loeallylinearembeddingforclassifieation,TeehniealRePort
PH一2002一01,PattemReeognitionGrouP,DePartmentofImagingSeieneeandTeehnology,
DelftUniversityofTeehnology,Delft,TheNetherlands,2002
   Ridder和Duin在文献((Loeallylinea:embedding伪:。lassi五eation》['o]中指出:如果
K太小,算法将错误的把连续流形分成不相交的子流形,映射将不会反映任何全局性
质;如果K太大,映射会丢失它的非线性特性,表现的像传统的PCA一样,即整个数
据集都将被看成局部邻域。如果d太小,数据集的分离部分将映射到一起;而如果d太
大,映射将增强噪声的影响。



5、2008小世界邻域优化的局部线性嵌入算法_张育林   基于聚类的局部线性嵌入
6、20132013求解高维多目标优化问题的流形学习算法研究   讲了流形降维的发展
7、2013基于流形学习的局部嵌入线性研究   讲lle自适应选取K