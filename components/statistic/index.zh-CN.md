---
category: Components
subtitle: 统计
type: 数据展示
title: Statistic
---

展示统计数字。

## 何时使用

当需要展示统计类数字时使用。

## API

#### Statistic

| 参数 | 说明 | 类型 | 默认值 |
| -------- | ----------- | ---- | ------- |
| decimalSeparator | 设置小数点 | string | - |
| formatter | 自定义数值展示 | (value) => ReactNode | - |
| precision | 数值精度 | number | - |
| prefix | 设置数值的前缀 | string \| ReactNode | - |
| suffix | 设置数值的后缀 | string \| ReactNode | - |
| title | 数值的标题 | string \| ReactNode | - |
| value | 数值内容 | string \| number | - |
| valueStyle | 设置数值的样式 | style | - |

#### Statistic.Countdown

| 参数 | 说明 | 类型 | 默认值 |
| -------- | ----------- | ---- | ------- |
| format | 格式化倒计时展示，参考 [moment](http://momentjs.com/) | string | 'HH:mm:ss' |
| prefix | 设置数值的前缀 | string \| ReactNode | - |
| suffix | 设置数值的后缀 | string \| ReactNode | - |
| title | 数值的标题 | string \| ReactNode | - |
| value | 数值内容 | number \| moment | - |
| valueStyle | 设置数值的样式 | style | - |