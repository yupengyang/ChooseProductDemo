这是一个Demo, 模仿的是淘宝买东西时选择款式大小时的组合.

需求描述:

1. 一个产品有多个类别属性, 比如颜色, 大小, 套餐等;
2. 根据库存中包含的产品来过滤可以购买的类别选项;
3. 当用户选中某一类别的一个值之后, 比如选中了颜色中的绿色, 根据已选中的值在库存商品中过滤其他类别中可以选择的选项;
4. 当所有类别都被选择之后, 启用购买按钮, 否则, 购买按钮不可使用(但可见)

demo本身很简单, 主要是逻辑和数据结构部分. 在结构组织上没有进行拆分. 其实可以不同category的view的分开, 用单独的view去实现, 这里只是想试验写下逻辑, 看有没有问题. 所以就没有做这个事情(主要是懒)
