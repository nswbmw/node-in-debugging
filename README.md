## node-in-debugging

《Node.js 调试指南》是本人整理的从事 Node.js 开发这几年的一些调试经验和思路，希望授人以鱼也能授人以渔。

## 开发环境

- MacOS|Linux(Ubuntu@16.04 64位)
- Node.js@8.9.4

## 目录

- CPU 篇
  - [perf + FlameGraph](https://github.com/nswbmw/node-in-debugging/blob/master/1.1%20perf%20%2B%20FlameGraph.md)
  - [v8-profiler](https://github.com/nswbmw/node-in-debugging/blob/master/1.2%20v8-profiler.md)
- 内存篇
  - [gcore + llnode](https://github.com/nswbmw/node-in-debugging/blob/master/2.1%20gcore%20%2B%20llnode.md)
  - [heapdump](https://github.com/nswbmw/node-in-debugging/blob/master/2.2%20heapdump.md)
  - [memwatch-next](https://github.com/nswbmw/node-in-debugging/blob/master/2.3%20memwatch-next.md)
  - [cpu-memory-monitor](https://github.com/nswbmw/node-in-debugging/blob/master/2.4%20cpu-memory-monitor.md)
- 代码篇
  - [Async + Await](https://github.com/nswbmw/node-in-debugging/blob/master/3.1%20Async%20%2B%20Await.md)
  - [Error Stack](https://github.com/nswbmw/node-in-debugging/blob/master/3.2%20Error%20Stack.md)
  - [Node@8](https://github.com/nswbmw/node-in-debugging/blob/master/3.3%20Node%408.md)
  - [Rust Addons](https://github.com/nswbmw/node-in-debugging/blob/master/3.4%20Rust%20Addons.md)
- 调试篇
  - [Source Map](https://github.com/nswbmw/node-in-debugging/blob/master/4.1%20Source%20Map.md)
  - [Chrome DevTools](https://github.com/nswbmw/node-in-debugging/blob/master/4.2%20Chrome%20DevTools.md)
  - [Visual Studio Code](https://github.com/nswbmw/node-in-debugging/blob/master/4.3%20Visual%20Studio%20Code.md)
  - [debug + repl2 + power-assert](https://github.com/nswbmw/node-in-debugging/blob/master/4.4%20debug%20%2B%20repl2%20%2B%20power-assert.md)
  - [supervisor-hot-reload](https://github.com/nswbmw/node-in-debugging/blob/master/4.5%20supervisor-hot-reload.md)
- APM 篇
  - [NewRelic](https://github.com/nswbmw/node-in-debugging/blob/master/5.1%20NewRelic.md)
  - [Elastic APM](https://github.com/nswbmw/node-in-debugging/blob/master/5.2%20Elastic%20APM.md)
- 日志篇
  - [koa-await-breakpoint](https://github.com/nswbmw/node-in-debugging/blob/master/6.1%20koa-await-breakpoint.md)
  - [async_hooks](https://github.com/nswbmw/node-in-debugging/blob/master/6.2%20async_hooks.md)
  - [ELK](https://github.com/nswbmw/node-in-debugging/blob/master/6.3%20ELK.md)
  - [OpenTracing + Jaeger](https://github.com/nswbmw/node-in-debugging/blob/master/6.4%20OpenTracing%20%2B%20Jaeger.md)
  - [Sentry](https://github.com/nswbmw/node-in-debugging/blob/master/6.5%20Sentry.md)
- 监控篇
  - [Telegraf + InfluxDB + Grafana(上)](https://github.com/nswbmw/node-in-debugging/blob/master/7.1%20Telegraf%20%2B%20InfluxDB%20%2B%20Grafana(%E4%B8%8A).md)
  - [Telegraf + InfluxDB + Grafana(下)](https://github.com/nswbmw/node-in-debugging/blob/master/7.2%20Telegraf%20%2B%20InfluxDB%20%2B%20Grafana(%E4%B8%8B).md)
- 工具篇
  - [node-clinic](https://github.com/nswbmw/node-in-debugging/blob/master/8.1%20node-clinic.md)
  - [alinode](https://github.com/nswbmw/node-in-debugging/blob/master/8.2%20alinode.md)

## 捐赠

支付宝 | 微信
------|------
![](./assets/alipay.png) | ![](./assets/wechat.jpeg)
