# sudoku
 实现了唯一法、隐含唯一法、对数、3~N链法、隐含对数、隐含3~N链法

唯一法
----
	根据相关单元已确切的值，调整本单元可能值
	若可能值只有1个，则唯一
  
隐含唯一法（覆盖 唯一法）
----
	若一个宫格/行/列内的9格 有一个数只出现在一个格的可能值中
	本单元可能值 交集其他所有单元
  
数对、三~N链
----
	同宫内 若N个数只出现在N个单元,则宫内其他单元不可能有这N个数
	对于一个N宫格 大于N/2的链无实际意义
	
