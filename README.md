# 数据库课程设计——网上销售系统
## 设计
订单状态：

0. 支付失败
1. 支付成功
2. 物流中
3. 退款
4. 交易成功

- 支付失败算作交易结束
- 支付成功之后，商家可以选择发货或者退款，退款会结束交易
- 支付成功之后，用户可以在交易未结束前选择申请退款，退款会结束交易
- 支付成功之后，商家选择发货，此时状态为物流中，用户可以选择收货，此时交易成功，正常完结