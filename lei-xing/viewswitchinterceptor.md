---
description: 视图跳转拦截器
---

# ViewSwitchInterceptor

## 签名

`(meta:` [`ViewSwitchEventData`](viewswitcheventdata.md)`) => boolean`

## 入参

1. `meta:` [`ViewSwitchEventData`](viewswitcheventdata.md) - 跳转动作的元数据描述。

## 返回

`true` - 继续执行下一个拦截器或执行视图跳转动作；`false` - 中止拦截器的继续执行或视图跳转动作。

