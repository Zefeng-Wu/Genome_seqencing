# Genome_seqencing

## 1.睡莲：   

### 1.组装
        三代组装（Canu）---> pollish（Arrow）----> 二代pollish（Pilon）----> 组装质量评估（BUSCO）---> group chromosomes by Hi-C (Lachesis)
### 2.基因预测
        Genscan + Augustus + MAKER
### 3.进化分析
        OrthoFinder
        multispecies coalescent model and a supermatrix method
### 4.推断WGD
        LAST QUOTA-ALIGN
        
        KS based： all_vs_all blast--- > 基因家族（mcl）----> PAML
        
        
## 2.脚苔
### 1.组装
        BUSCO scores

### 2.基因预测
        Braker2（Augustus）

### 5.重复序列注释
       RepeatModeler + LTR_retriever+ fileter（UniProt）+ RepeatMasker +EVidenceModeler (EVM)
       
       
