# oner-flexbox
oner-flexbox 是一个flex布局的小样式库

## 设计理念概念
遵循**首尾字母缩写**原则

<img src="http://cdn.dtwave.com/tps/justfiy-content.png" width = "300"  align=center />

<img src="http://cdn.dtwave.com/tps/align-items.png" width = "300"  align=center />

[戳这里=>调试Demo](http://jsbin.com/rusolew/edit?html,output)

## API

### FBH
指定**水平方向**为容器的主轴

### FBV
指定**垂直方向**为容器的主轴

### FBAS
`align-items: flex-start`

### FBAC
`align-items: center`

### FBAE
`align-items: flex-end`

### FBAST
`align-items: stretch`

### FBAB
`align-items: baseline`


### FBJS

`justify-content: flex-start`
伸缩项目向一行的**起始位置靠齐**

### FBJC

`justify-content: center`
伸缩项目向一行的**中间位置靠齐**

### FBJE

`justify-content: flex-end`
伸缩项目向一行的**结束位置靠齐**

### FBJB

`justify-content: space-between`
伸缩项目会**平均地分布**在行里

### FBJA
`justify-content: space-around`

### FBAB
`align-content: space-between`

### FBAA
`align-content: space-around`

### align-content的其他相关值
在`align-items`的基础上加<mark>&nbsp; **-M** &nbsp;</mark>(Multiline)
> eg:
> #### FBAS-M
> `align-content: flex-start`


### align-self的相关值
在`align-items`的基础上加<mark>&nbsp; **-S** &nbsp;</mark>(Self)
> #### FBAS-S
> `align-self: flex-start	`


### FB1

`flex: 1`

### FB2

`flex: 2`

…………
…………
…………
### FB10

`flex: 10`
