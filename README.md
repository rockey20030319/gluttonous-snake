# gluttonous-snake
目的
---------------------------------------------
利用pygame构造一个贪吃蛇游戏来熟悉python类的概念

游戏规则
----------------------------------------------
玩家扮演贪吃龙，龙的生命值等于自身的长度，同时龙身的最长长度作为玩家的分数值，当龙咬到自身时则会把余后的部分咬断，当龙碰壁时则直接死亡
小龙要吃掉三种怪物，分别是“魑”、“魅”和“魍魉”
“魑”：
一种山神，破坏力惊人，它有四个方向，分别是左爪、右爪、头和尾巴，龙从左右爪吃它的时候，能把它消灭，但是扣一条命；从头吃它的话，掉一条命，且无法消灭，它会在另一个方格中出现；从尾巴吃它，方能消灭，并加一条命
“魅”：
一种木精，迷人心窍，贪吃龙若吃掉它，会随机改变前进方向，且在0-10s内玩家不能控制其方向
“魍魉”：
一种水怪，像银鱼一般四处游移，碰到“魅”的时候，自身消失，且在“魅”的周围(九宫格)生成一个新的“魅”；碰到“魑”的时候，自身消失，且“魑”会往“魍魉”移动的方向前进三格，若前进的过程中截断龙身，则龙身余后的部分被咬断；若碰到龙身则分裂成两个“魍魉”
最后记录玩家的得分，得分高者胜利

实施过程
-------------------------------------------
先看相关书籍，并打卡完成后面的联系，掌握基本概念
观看其他作者所写的贪吃蛇代码
撰写自己的代码
