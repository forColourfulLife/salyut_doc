# \- fill

## 范式
```
- fill: { ele: , value: }
```
您可以通过**fill**标签来填充输入框

## 属性
| 属性 | 类型 | 是否必须 | 备注 |
|--------|--------|--------|--------|
|   ele   | [selector](datatype.md)  | √ |   |
|   value   | [expr](datatype.md)  |  √ |   |

## 用法
```yaml
- fill: { ele: '#input', value: '"hello word!"' }
```