# lessgo

lessgo的伟大目标是：A real serverless platform that pay-as-you-use.

如何定义real：
* 当用户的函数没有被执行的时候，serverless平台不该对用户收取任何费用，例如serverless平台为优化函数冷启动而发生的资源占用不该由用户买单
* 不能简单粗暴的按请求数收费，因为有的函数效率低，耗费cpu、内存等资源多，理应按照资源使用量收费，包括但不限于cpu、memory、带宽、硬盘等
