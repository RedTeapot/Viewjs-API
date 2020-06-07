---
description: 视图渲染所需要的数据的获取方法。
---

# ViewDataFetchAction

## 签名

`(resolve: Function, reject: Function) => boolean`

## 入参

1. `resolve: Function` - 由 View.js 提供，供开发者执行的，用于告知 View.js 数据加载完成的方法。
2. `reject: Function` - 由 View.js 提供，供开发者执行的，用于告知 View.js 数据加载失败的方法。

## 返回

`true` - 继续执行下一个拦截器或执行视图跳转动作；`false` - 中止拦截器的继续执行或视图跳转动作。

