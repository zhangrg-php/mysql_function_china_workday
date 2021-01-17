# mysql_function_china_workday

使用mysql是json函数，通过给每个工作日index的方式，计算法定节假日时效

## workday.php

循环出每年日历的JSON。

## wokday.sql

自定义函数的sql

## 注意

+ 未兼容下班后（比如：18:00）算下一个工作日
+ 没有0个工作日概念，所以结果+1
+ 不支持mysql 5.6版本
+ 测试用，勿适用于生产环境