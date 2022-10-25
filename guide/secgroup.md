# 安全组

UPgSQL实例支持安全组功能。 当用户账号开通安全组功能后， 在支持安全组的地域创建数据库实例， 数据库实例会自动加入默认安全组中。

默认事项：
- 创建从库：新建从库自动绑定到主库所在的安全组。
- 单点提升高可用：高可用备库资源自动绑定到主库所在的安全组。
- 回档到到新实例：新实例自动绑定到源实例所在的安全组。

## 查看安全组

在网站首页产品列表中找到“私有网络 UVPC”点击进入

![image](/images/secgroup/secgroup_list.png)

点击操作栏的“详情”按钮可查看当前此安全组绑定的资源以及安全规则。

![image](/images/secgroup/secgroup_detail.png)

## 修改安全组

具体操作请参考[安全组操作文档](https://docs.ucloud.cn/vpc/introduction/secgroup)