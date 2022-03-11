# pi_guid64

全局唯一ID, 64位

{1970年的时间（ms）（6字节），节点编号（2字节）}

同一个GuidGen分配的guid，保证time不重复

分布式系统可以利用控制编号来管理hash，进行一致hash命中
