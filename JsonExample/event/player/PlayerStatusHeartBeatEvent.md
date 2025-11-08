# 玩家心跳事件

正常情况下，该事件消息会隔一段时间发送你一次，便于你了解你所操控的角色状况。
```jsonc
{
//玩家生命信息
  "health": 0,
  "maxHealth": 0,
//玩家饱食度信息
  "hunger": 0,
  "maxHunger": 0,
//玩家饱和度
  "saturationLevel": 0,
//玩家位置信息
  "posX": 0,
  "posY": 0,
  "posZ": 0,
//玩家视角信息
  "yaw": 0,
  "pitch": 0,
}
```

## 你可以根据玩家状态选择 ##
1.什么都不做（回复[空消息](../../special/EmptyMessage.md#空消息)）  
  
2.根据玩家状态，回复[AI操控玩家事件消息](../ai/AIControlEvent.md) ，决定玩家角色下一步该做什么。
  
3.某些情况你可以判断出你已经完成了任务，如到达某个位置，那你可以发送 [停止事件消息](../ai/AIStopEvent.md) 了

