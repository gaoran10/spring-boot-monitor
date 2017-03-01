# spring-boot提供的监控接口列表及说明

## /metrics  度量指标类
返回当前应用的各类重要度量指标，比如：内存信息、线程信息、垃圾回收信息、http访问指标等。

<| Header One     | Header Two     |
| :------------- | :------------- |
| Item One       | Item Two       |


|序号|指标名|说明|
|-|-|-|
|1|mem|jvm内存总大小|
|2|mem.free|jvm空闲内存大小|
|3|processors|cpu核数|
|4|instance.uptime|实例运行时间|
|5|uptime|运行总时间|
|6|systemload.average|系统平均负载|
|7|heap.committed|提交堆内存大小|
|8|heap.init|初始化堆内存大小|
|9|heap.used|已使用堆内存大小|
|10|heap|堆内存总大小|
|11|nonheap.committed|提交的非堆内存大小|
|12|nonheap.init|非堆初始化内存大小|
|13|nonheap.used|已使用非堆内存大小|
|14|nonheap|非堆内存总大小|
|15|threads.peak|线程峰值|
|16|threads.daemon|守护线程数|
|17|threads.totalStarted|创建的线程总数|
|18|threads|活动线程数量|
|19|classes|当前加载的类总数|
|20|classes.loaded|已加载的类总数|
|21|classes.unloaded|已卸载的类总数|
|22|gc.ps_scavenge.count|垃圾回收次数|
|23|gc.ps_scavenge.time|垃圾回收时间|
|24|gc.ps_marksweep.count|标记清除算法次数|
|25|gc.ps_marksweep.time|标记清楚算法时间|
|26|counter.*|http性能指标 - 次数|
|27|gauge.*|http性能指标 - 最近一次返回的时间  含有-star 表示静态资源返回的时间|
