# Minecraft Item List

Minecraft 基岩版所有物品列表。

## JSON 结构

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

## 文件结构

/repo/README.md  仓库描述文件  
/repo/list.json  物品列表json  
/repo/textures/  原版icon图片  

本仓库使用tag管理版本  

v + Minecraft版本 + - + 修订号

如：v1.19.73-1

## License

LGPL 3.0