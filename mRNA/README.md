# 介绍


## mRNA转变过程

![](https://github.com/eternal-bug/molecular_biology/blob/master/mRNA/pic/mRNA.png)

+ 结构解释

```
                                      与某基因相关的区域
chr:                       ......==============================.....

transcription initiation:        ==============================
                                 ***|----------------------->|
                                  ^ ^        基因             ^
                                  | |                        |
                                  | 转录起始位点               转录终止位点
                                 启动子
```

+ 位于DNA上的结构
```
DNA:
             +--------+----------------------------------------------+
             |promoter|                gene                          |
             +--------+----------------------------------------------+
                      ^                                              ^
                      |                                              |
                      TSS(transcriptional start site)                TTS(tanscription termination site)
```

+ 位于RNA上的结构
```
preRNA:
                     +-----+-----+--------+--------+------+----+-----+
                     |5'UTR| CDS | intron |   CDS  |intron|CDS |3'UTR|
                     +-----+-----+--------+--------+------+----+-----+
                     
                     |    exon   | intron |  exon  |intron|    exon  |

第一个外显子不等于第一个CDS片段，而是包含了5'-UTR的区域，某个完整成熟的mRNA同样最后一个外显子等于3'UTR加上最后一个CDS片段

mature RNA:

                +----+-----+-----+--------+----+-----+------+
                | cap|5'UTR| CDS |   CDS  |CDS |3'UTR|Poly A|
                +----+-----+-----+--------+----+-----+------+
                           ^                   ^
                           |                   |
                           initiation codon    termination codon
```

## 参考
+ [怎么查找基因的启动子、UTR、TSS等区域以及预测转录因子结合位点](http://www.hzrna.com/6273.html)
