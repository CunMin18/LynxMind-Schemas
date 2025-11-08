# 获取玩家状态
如果你不知道所操控的角色目前境地  
你可以发送这个Json查询玩家状态  
稍后用户会自动发给你 [玩家心跳事件](./player/PlayerStatusHeartBeatEvent.md)。
```jsonc
{
  "type": "EVENT_AI_GET_STATUS"
}
```
