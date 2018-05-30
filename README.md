<h1 align="center">
<img src="./assets/book.jpg" alt="node-in-debugging" width="200" height="200" />
<br>
《Node.js 调试指南》
</h1>
<h4 align="center">
<a href="http://product.dangdang.com/25278935.html">当当</a> | <a href="https://item.jd.com/12356929.html">京东</a> | <a href="https://s.taobao.com/search?q=Node.js%E8%B0%83%E8%AF%95%E6%8C%87%E5%8D%97">淘宝</a> | <a href="https://www.amazon.cn/dp/B07D57FDY4/">亚马逊</a> | <a href="http://product.china-pub.com/8004731">china-pub</a>
</h4>

## 开发环境

- MacOS|Linux(Ubuntu@16.04 64位)
- Node.js@8.9.4

## 目录

- CPU 篇
  - [perf + FlameGraph](https://github.com/nswbmw/node-in-debugging/blob/master/1.1%20perf%20%2B%20FlameGraph.md)
  - [v8-profiler](https://github.com/nswbmw/node-in-debugging/blob/master/1.2%20v8-profiler.md)
  - [Tick Processor](https://github.com/nswbmw/node-in-debugging/blob/master/1.3%20Tick%20Processor.md)
- 内存篇
  - [gcore + llnode](https://github.com/nswbmw/node-in-debugging/blob/master/2.1%20gcore%20%2B%20llnode.md)
  - [heapdump](https://github.com/nswbmw/node-in-debugging/blob/master/2.2%20heapdump.md)
  - [memwatch-next](https://github.com/nswbmw/node-in-debugging/blob/master/2.3%20memwatch-next.md)
  - [cpu-memory-monitor](https://github.com/nswbmw/node-in-debugging/blob/master/2.4%20cpu-memory-monitor.md)
- 代码篇
  - [Promise](https://github.com/nswbmw/node-in-debugging/blob/master/3.1%20Promise.md)
  - [Async + Await](https://github.com/nswbmw/node-in-debugging/blob/master/3.2%20Async%20%2B%20Await.md)
  - [Error Stack](https://github.com/nswbmw/node-in-debugging/blob/master/3.3%20Error%20Stack.md)
  - [Node@8](https://github.com/nswbmw/node-in-debugging/blob/master/3.4%20Node%408.md)
  - [Rust Addons](https://github.com/nswbmw/node-in-debugging/blob/master/3.5%20Rust%20Addons.md)
  - [Event Loop](https://github.com/nswbmw/node-in-debugging/blob/master/3.6%20Event%20Loop.md)
  - [uncaughtException + llnode](https://github.com/nswbmw/node-in-debugging/blob/master/3.7%20uncaughtException%20%2B%20llnode.md)
- 工具篇
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
- 应用篇
  - [node-clinic](https://github.com/nswbmw/node-in-debugging/blob/master/8.1%20node-clinic.md)
  - [alinode](https://github.com/nswbmw/node-in-debugging/blob/master/8.2%20alinode.md)
