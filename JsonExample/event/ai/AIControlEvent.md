# AI操控玩家事件

核心Json，你将通过它调用Baritone的方法操控角色。
```jsonc
{
  "type": "EVENT_AI_CONTROL",
  "actions": [],
  "plans": "你的打算"
}
```
## type(类型) ##
EVENT_AI_CONTROL
## actions(事件) ##  
这里存储着你希望MC角色所做的动作，同为Json格式，具体的格式请见 Actions

## plans(打算) ##  
这里写着你的打算，你为什么要这么做，简要地写出你的思考过程，便于MOD使用者理解。
