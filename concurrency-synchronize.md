## 并发同步

在多核CPU体系中，资源竞争是不可避免的问题，比如说在 `CPU核心1` 运行的 `进程1` 和在 `CPU核心2` 运行的 `进程2` 同时访问公共 `变量A`，那么就会产生资源竞争。