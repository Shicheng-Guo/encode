
Timeline: 

* 2020/01/07: DGE Pancancer analysis to ZNF132, we find different expression is `P=9.6x10-6` with `beta= -0.58`
* 2020/01/07: DGE Pancancer analysis to 1639 TFs and 109 DGE-TFs in which [61](./TFBS/TF.dge.up.tcga.pancancer.smd.meta.pvalue.csv) upreagulated and [48](./TFBS/TF.dge.down.tcga.pancancer.smd.meta.pvalue.csv) downregulated.
* 2020/01/07: Update to have a [1,639 full transcriptional factor list](./TFBS/1639TF.txt) download from [wiki]() and be saved [here]()
* 2020/01/04: data matrix is showed in: https://genome.ucsc.edu/ENCODE/dataMatrix/encodeDataMatrixHuman.html
* 2020/01/03: [Top 30](https://github.com/Shicheng-Guo/encode/blob/master/TFBS/tcgameta/pancancer.tfbs.pick.rnaseq.dmg.smdos.hr.pick.csv) cancer related transcriptional factors were identified and the images were saved [here]()
* 2020/01/02: How to connect narrowpeaks filename with samplenames? (the first files of the `files` is the [meta file](./TFBS/meta.txt))
* 2020/01/02: all the narrowpeak were saved in this folder: `~/hpc/project/encode/tfbs/` and `files` was saved in [here](./TFS/files.txt)
* 2020/01/02: download all `TFBS narrowpeak` from [encode](https://www.encodeproject.org/search/?status=released&type=Experiment&assay_title=TF+ChIP-seq&assembly=GRCh38&files.file_type=bed+narrowPeak) with the command `xargs -L 1 curl -O -L < files.txt` 
* 2020/01/02: ChIP-seq based TFBS: [169 ZNF](./TFBS/169ZNF.txt) in [685 TFs](./TFBS/685TFBS.txt) have been provided in Encode dataset by 01/02/2020. 
