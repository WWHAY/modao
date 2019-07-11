# React Framework: Card page

Framework: React (JavaScript)  
Render: HTML/CSS

## Page structure

`mockData`: mocked data, the data should be JSON data from back end in reality [模拟后端JSON数据]  
`CardList_Component`: all cards rendered on the page, including all `Card_Component`s generated from data & a `NewCard_Component` [所有卡片的列表，包含所有数据产生的卡片和‘新建项目组’卡片]  
`Card_Component`: individual card, detailed structure in commment line 100 [单张卡片，卡片结构参考文件注释第100行]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`Card_Locked_SubComp`: sub-component for `isLocked` attribute [处理`isLocked`属性的亚组件]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`Card_Private_SubComp`: sub-component for `isPrivate` attribute [处理`isPrivate`属性的亚组件]  
`NewCard_Component`: card for creating a new card, function not implemented [创建新卡片的最后一张卡片，功能未实现]
`FlavorForm`: This is a screening menu for the project [这是一个关于项目的筛选菜单，点击之后文字变蓝的功能未实现]
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;` IsLockedItems`: sub-component for `isLocked` attribute [处理`isPrivate`项目属性的亚组件]  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`IsPrivateItems`: sub-component for `IsPrivateItems` attribute [处理`isPrivate`项目属性的亚组件]  


## Known drawbacks

See comment line 178  




