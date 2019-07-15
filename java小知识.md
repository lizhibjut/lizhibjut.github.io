## java小知识

#### threadLocal的理解
threadLocal用于多线程的场景。有2个主要用途：1、保存线程上下文信息，在需要的地方使用；2、线程安全的，避免某些情况需要考虑线程安全必须同步带来的性能损失。

#### 为什么只需要一个eden而需要两个survivor https://blog.csdn.net/qq_35181209/article/details/78033329  
简单说就是减少内存碎片化
