# 问题
你和你的朋友玩下面的Nim游戏：桌子上有一堆石头，每次你们轮流去除1到3块石头。 去掉最后一块石头的人将是胜利者。 您将首先转动以移除宝石。

你们两个都很聪明，并且拥有最佳的游戏策略。 编写一个函数，以确定您是否可以在堆中的石块数量的情况下赢得游戏。

例如，如果堆中有4块石头，那么你永远不会赢得比赛：无论你移除的是1块，2块还是3块石头，最后一块石头总是会被你的朋友移除。
# 代码
```c
bool canWinNim(int n)
{
 if((n%4)==0) return false;
    else return true;
}
```
# 总结
不明白有什么意义......找规律？