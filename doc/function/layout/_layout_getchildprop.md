---
description: 布局_取组件属性
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_getchildprop (
    int hLayout,
    int hObj,
    int dwPropID,
    int *pvValue
);
```


### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`hObj`

Type: **HANDLE**

组件句柄

`dwPropID`

Type: **INT32**

属性ID

`pvValue`

Type: **INT32***

取回的属性值

---

### Return Value / 返回值

Type: BOOL
