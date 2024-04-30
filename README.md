# Minecraft Item List

Minecraft 基岩版所有物品列表。

JSON 结构

```json
[
  {
    "name": "游戏内显示的物品名称",
    "id": "物品的游戏内id",
    "type": "物品标准类型名",
    "aux": "物品的特殊值（用于区分同Type不同Aux的物品）",

    "icon": "物品贴图路径",
    "class": "物品类别"
  }
]
```

文件夹结构

/Json/ 存放每个版本的物品列表
/Icon/ 存放每个物品的贴图
