### SpringCloud知识点
* 1.什么是微服务？微服务的特点？微服务的优势？为什么使用微服务？
微服务是一个小的，松耦合的分布式服务。它允许将一个大型应用分解为具有严格职责定义的便于管理的组件。微服务架构具有以下特征：应用程序逻辑分解为职责定义明确的细粒度组件，组件相互协作提供解决方案；每个组件都有一个小的职责领域，并完成独立部署。微服务对业务领域的单个部分负责，此外微服务组件可以在多个应用中复用；微服务组件之间的通讯应该遵循一定的原则，可以采用http与JSON这种轻量级通讯协议，完成服务消费者和服务提供者之间数据的交换；微服务具有小，独立，分布式的特性，适合组织有明确职责领域的小型开发团队进行开发。讨论微服务时记住下面的一句话：小型、简单、解耦的服务=可伸缩、有弹性、灵活的应用
