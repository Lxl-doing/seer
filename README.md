### 井字棋小游戏

棋子三类：
- 不能移动
- 立即移动
- 静置一回合后移动

游戏设计：
- 棋盘一开始中央有一个和后行者同色的棋子，生命值1，立即移动类型，作为后手补偿
- 棋手每回合最多两种操作，召唤和移动各一次
- 棋手可操作棋子有3个，剩下3子在等候区，类似循环队列
- 生命值会进行抵消，横竖斜最先出现1、2、3三种类型的数字方胜利