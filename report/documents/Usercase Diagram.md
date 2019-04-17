# 用例图
##### 整个系统的用例图如下：
![](https://github.com/uml163/UML/blob/master/pictures/%E7%94%A8%E4%BE%8B%E5%9B%BE.png)
## 用例文本
#### 整个系统的用例如下，可根据需要查看各子用例图。
##### **基本用例：**
商家：
* [注册登录](https://github.com/uml163/UML/blob/master/report/documents/Usercase%20Diagram/%E6%B3%A8%E5%86%8C%E7%99%BB%E5%BD%95.md)：餐厅管理员可通过此用例注册和登录系统
* [管理菜品信息](https://github.com/uml163/UML/blob/master/report/documents/Usercase%20Diagram/%E7%AE%A1%E7%90%86%E8%8F%9C%E5%93%81%E4%BF%A1%E6%81%AF.md)：管理员可以对菜品信息进行管理，管理的内容包括：分类、价格、图片、描述、标签、菜品排序
* [查看订单](https://github.com/uml163/UML/blob/master/report/documents/Usercase%20Diagram/%E7%AE%A1%E7%90%86%E5%91%98%E6%9F%A5%E7%9C%8B%E8%AE%A2%E5%8D%95.md): 管理员可以查询已有订单，并能查看订单的详细信息
* [处理订单](https://github.com/uml163/UML/blob/master/pictures/%E7%AE%A1%E7%90%86%E5%91%98%E5%A4%84%E7%90%86%E8%AE%A2%E5%8D%95.png)：管理员可对现有订单进行确认和拒绝
***
顾客：
* [点餐](https://github.com/uml163/UML/blob/master/pictures/%E7%82%B9%E9%A4%90.png)：顾客在到达餐厅后，可扫描餐桌上的二维码进入本小程序，根据菜单选择菜品，并支付下单
* [查看订单]()：顾客可以查看已下的订单
* [取消订单]()：如果顾客对订单不满意，可对订单进行取消。

##### **扩展用例**
* 催单：在半个小时内没有上菜则可以进行催单
