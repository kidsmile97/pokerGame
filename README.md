# pokerGame
## 前端JS斗地主游戏实现，纯前端无后端的，所有的数据逻辑出牌逻辑都用模块化封装好了，可以看看

## 主要实现
+ AMD模块化封装玩家数据和出牌相关
  - 54张手牌
  - 随机分配手牌和地主牌
  - 抢地主后分配地主牌
  - 出牌规则
  - 出牌判定以及出牌数据记录
  - 输赢判断
+ 用promise控制游戏流程
  - 分牌阶段
  - 抢地主阶段
  - 出牌阶段以及输赢判定
+ 要使用后端也简单，把数据全部改成后端获取即可，不需要改动前端以及玩家事件
