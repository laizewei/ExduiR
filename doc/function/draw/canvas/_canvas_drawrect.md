---
description: 画布_画矩形
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_drawrect (
    HCANVAS hCanvas,
    HBRUSH  hBrush,
    float   left,
    float   top,
    float   right,
    float   bottom,
    float   strokeWidth,
    int     strokeStyle
);
```


### Parameters / 参数

`hCanvas`

Type: **HANDLE**

画布句柄

`hBrush`

Type: **HANDLE**

画刷句柄

`left`

Type: **FLOAT**

左边

`top`

Type: **FLOAT**

顶边

`right`

Type: **FLOAT**

右边

`bottom`

Type: **FLOAT**

底边

`strokeWidth`

Type: **FLOAT**

描线宽度

`strokeStyle`

Type: **INT32**

描线风格

---

### Return Value / 返回值

Type: BOOL

绘制矩形