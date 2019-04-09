# 成员管理

易观方舟支持一个项目多个成员共享，方便企业内部共同参与到数据分析和决策的过程中来。项目创建人或管理员可以邀请多个成员，并对不同成员分配不同角色来实现应用的授权。

## 1. 角色-权限

系统预置了常用的角色，不同角色对应不同的权限，管理员授权时对不同的成员选择不同的角色即可。

| 角色 | 角色描述 | 看板 | 分析 | 分群 | 运营 | 元数据管理 | 项目设置 | 成员管理 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 管理员 | 通常赋予项目的leader | √ | √ | √ | √ | √ | √ | √ |
| 产品人员 | 通常赋予产品经理或产品运营该角色 | √ | √ | √ | √ | 设置维度字典和设置数据显示状态之外的功能 |  |  |
| 数据分析师 | 赋予数据分析师该角色 | √ | √ | √ | 仅查看消息列表 | 设置维度字典、数据显示状态、可视化埋点之外的功能 |  |  |
| 工程师 | 赋予内部协助埋点的工程师 | 仅查看 | 仅查看图表列表和已有图表详情页 | 仅查看分群列表 | 仅查看消息列表 |  |  |  |
| 普通成员 | 赋予普通查看者角色 | 仅查看 | 仅查看图表列表和已有图表详情页 | 仅查看分群列 | 仅查看消息列表 |  |  |  |

更详细的不同角色对应的功能范围，见[《附：角色 - 权限对应表》](member.md#fu-jiao-se-quan-xian-dui-ying-biao)。

## 2. 邀请成员

项目管理员有权限邀请企业成员到本项目中。点击 **成员管理** 进入项目成员列表。

点击右上角 **添加成员** ，选择要邀请的 **企业内成员**，直接添加到 **已选择成员**，点击 **确定** 即可。

![ ](https://imguserradar.analysys.cn/fangzhou/img/2018/12/201812191130157614.gif)

添加成功后，被邀请成员就可以使用 **邮箱/手机号/用户名** 和 **初始密码** 登录到项目中。

## 3. 修改成员

在成员列表页可以查看当前项目中，成员的信息以及对应的权限，管理员有权移除某个成员。

> 注：管理员之间没有权限移除或者修改对方权限

![ ](https://imguserradar.analysys.cn/fangzhou/img/2018/12/201812191136255193.png)

**A. 移除成员**

当添加的成员已离职，或者不再授权时，点击移除成员，移除后将无法访问该项目的数据。

![ ](https://imguserradar.analysys.cn/fangzhou/img/2018/12/201812191140131115.png)

**B. 修改权限**

当成员权限错误时，可以点击角色下拉框，快速修改角色

![ ](https://imguserradar.analysys.cn/fangzhou/img/2018/12/201812191141170214.png)

## 附：角色 - 权限对应表

![ ](https://imguserradar.analysys.cn/fangzhou/img/2019/01/201901041749381381.png)

如有更多有关问题，请随时联系我们 **4006-010-231。**

![](../../.gitbook/assets/201901151711159657.jpg)
