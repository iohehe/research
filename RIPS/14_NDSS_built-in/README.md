作者在静态分析时， 对php的621种内建函数进行分类。 在此基础上进行分析，更好的描述污点传播。


## Approach
之前的PHP静态分析工作中，由于不知道内建函数的作用而丢失了精度。这篇文章，对PHP的内建函数进行了分类。