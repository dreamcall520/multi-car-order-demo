# 独立站多车合并下单（脱敏演示版）

> GitHub 仓库：`multi-car-order-demo`；对应项目名称为“独立站多车合并下单”。

这是“独立站多车合并下单”的个人 GitHub 项目，不承接其他会话或其他项目的文件。

统一预览入口为 `multi-car-order-demo.html`：可在同一页面切换 PC 采购清单、订单列表、合单主订单详情、子订单详情、外销合同及移动端页面。所有名称、编号、状态和金额均为虚构演示数据。

本次按项目负责人明确授权，额外上传两份 PC 端测试原型：`customer-detail-purchase-list.html` 与 `customer-detail-demand-agent-order.html`，以及移动端测试草稿：`crm-mobile-multi-car-agent-order-draft.html`。

移动端文件为当前评审草稿：已覆盖采购清单、需求多车源与代客建单交互，但尚待代码清理和截图验收，不应视为最终原型或可直接投入生产的实现。

## 合单订单页面草稿

以下最新的 PC 端订单页面集中存放在 `prototypes/orders/`：

- `order-list-merged-draft.html`：合单主订单聚合列表及子订单展开。
- `order-master-detail-current-structure-draft.html`：合单主订单详情（按现有后台结构整理的最新确认页面）。
- `order-child-detail-draft.html`：单车子订单详情与履约追溯。
- `order-master-sales-contract-draft.html`：主订单外销合同页面。

上述文件共同用于呈现“采购清单 → 订单列表 → 合单主单 → 单车子订单 → 外销合同”的查看链路；仅含测试数据，不含公司代码、账号、接口或内部链接。

## 内容边界

- 不包含账号信息、接口地址、凭据或内部链接。
- 原型中的示例名称、编号、状态和金额均按项目负责人确认为测试数据。
- 不包含未公开的需求文档、截图、数据和配置文件。
- 后续新增内容均应先完成脱敏与公开范围确认。

## 计划内容

- 产品需求与流程模板
- 脱敏后的原型或界面示例
- 可公开的产品思考和方法总结
