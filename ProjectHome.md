中文字符串多模式匹配算法
大家阅读关于wumanber的论文，以及网上一些找到的wumanber的算法，都是针对英文的。
为了在工程实践中使用wumanber查找中文，我进行了改写。
1). 该算法的速度是极快的。以前有过测试，现在忘记了。
2). pattern文件里面的子串，建议至少2个字，因为整个查找算法的效率，是和pattern中最短的相关的。