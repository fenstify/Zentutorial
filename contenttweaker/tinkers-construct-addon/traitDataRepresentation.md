# 特性数据

## 导入

通过 `import mods.contenttweaker.tconstruct.TraitDataRepresentation;` 导入TraitDataRepresentation类  

## 参数

| 参数 | 是否有ZenGetter | 是否有ZenSetter | 返回(设定)值类型 | 参数描述 |
| :---- | :---- | :---- | :---- | :---- |
| identifier | √ | √ | string | 特性名称 |
| extraInfo | √ | √ | string | 特性额外信息 |
| info | √ | × | string | 特性信息 |
| colorString | √ | × | string | ? |
| level | √ | √ | int | 特性等级 |
| color | √ | √ | int | 特性颜色 |
| current | √ | √ | int | ? |
| max | √  | √ | int | ? |

可以通过此类设置一些关于 Trait 的信息
