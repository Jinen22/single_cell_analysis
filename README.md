# single_cell_analysis
collection of tools for single cell analysis

### 1 receptors ligands and their interactions
2020/04/22  
受配体结合分析最近被使用的越来越多。在github就有很多可以使用的工具，比如cellPhoneDB[https://github.com/Teichlab/cellphonedb] 和celltalker[https://github.com/arc85/celltalker] 
都可以做

### 2 根据sc-RNAseq数据推断CNV
BROAD有一个R包,叫inferCNV,可以用来分析单细胞转录组中拷贝数变异,但总感觉奇奇怪怪的,觉得不靠谱,尤其是10X的数据,都是非常短的序列,100bp左右,用来推断CNV结果,很难能做到.需要先学习一下原理,再决定是否使用.[官网链接](https://github.com/broadinstitute/inferCNV/wiki)
