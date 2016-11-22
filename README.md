# Jimmy's first R package:humanid

------

It's a unoffical package, just for **fun**. I will put many simple R functions which used frequently in my daily data analysis, which should be useful for you too. Don't be worry to learn them, I'm used to write minimal function, just like perl, my favorate computer language ! 

### functions including:

> * batch_enrichment
> * batch_pheatmap
> * batch_t_test
> * createGSEAinput
> * downGSE
> * draw_boxplot_gene
> * format_DEG
> * geneAnno
> * keggAnno
> * pathway_heatmap(todo)
> * probesetAnno
> * QCexpressionMatrix 


please feel free to contact with me if there's bug in my package, so far it's very simple，not Defensive programming,So don't fool around with my function. 

### [my blog](http://www.bio-info-trainee.com/)

>  I perfer email communication: jmzeng1314@163.com 

------


```R

library(CLL)
data(sCLLex)
group_list=sCLLex$Disease
QCexpressionMatrix(example_exprSet,group_list)
batch_pheatmap(example_exprSet,group_list,name=F,genesets=enzyme_genesets)

```