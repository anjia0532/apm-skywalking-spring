# apm-spring-rabbitmq-5.x-plugin

Skywalking 中追踪 RabbitMQ 的自定义插件，添加对 Spring RabbitMQ 的支持。

解决 Spring RabbitMQ 5.x 版本 Skywalking 无法追踪 tid:N/A 的问题。

## 版本说明

1. Skywalking：9.5.0
2. spring-amqp：2.2.5

## 使用步骤：

1. 使用 maven 打包；
2. 将 jar 包放到 Skywalking 目录下的 plugin 文件夹，重启项目即可。
