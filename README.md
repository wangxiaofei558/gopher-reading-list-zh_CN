# Go 阅读清单
---

此项目是一份关于Go的中文博客文章的阅读列表。 灵感来源于：[gopher-reading-list](https://github.com/enocom/gopher-reading-list)。

如果有新的文章也欢迎提交PR或issue。此项目只包含文章标题和链接，不会转载文章内容。

由于能力、精力有限，提交的文章可能无法一一甄别，对于文章中有遗漏或笔误的地方，可以发起issue讨论。

为避免列表过大，对于系列文章，建议只提交系列文章的目录。

此列表将分为以下几个部分：

- [基础](#user-content-基础)
  - [基础](#user-content-基础)
  - [代码组织与风格](#user-content-代码组织与风格)
  - [Web](#user-content-Web)
  - [并发](#user-content-并发)
- [中级](#user-content-中级)
  - [代码设计](#user-content-代码设计)
  - [并发](#user-content-并发-1)
  - [测试](#user-content-测试)
  - [Web](#user-content-Web-1)
  - [工具](#user-content-工具)
  - [问题诊断](#user-content-问题诊断)
  - [杂项](#user-content-杂项)
- [高级](#user-content-高级)
  - [性能](#user-content-性能)
  - [垃圾回收](#user-content-垃圾回收)
  - [并发](#user-content-并发-2)
  - [杂项](#user-content-杂项-1)

## 基础

### 基础

- [十条有用的 GO 技术](https://golangcaff.com/topics/114/ten-useful-techniques-in-go)
- [fmt 如何进行格式化？](http://blog.cyeam.com/golang/2018/09/10/fmt)  
- [像牛人一样改进你的Go代码](https://colobu.com/2017/06/27/Lint-your-golang-code-like-a-mad-man/)
- [使goroutine同步的方法总结](https://www.cnblogs.com/xiaoxlm/p/9753942.html)

## 中级

### 并发

- [通过插图学习 Go 的并发](https://golangcaff.com/topics/140/learning-the-concurrency-of-go-through-illustrations)

### 测试

- [SmartyStreets 的 Go 测试探索之路](https://juejin.im/post/5ba83f2ff265da0a867c3818)

### 杂项

- [Go 的位操作](https://golangcaff.com/topics/139/bit-operation-of-go)
- [Go语言HTTP/2探险之旅](https://mp.weixin.qq.com/s/Wb4STm5tpZUTJkQbReyShg)
- [初窥Go module](https://tonybai.com/2018/07/15/hello-go-module/)
- [goroutine和panic不得不说的故事](https://zhuanlan.zhihu.com/p/42101856)

## 高级

### 性能
- [Golang 大杀器之性能剖析](https://github.com/EDDYCJY/blog/blob/master/golang/2018-09-15-Golang%20%E5%A4%A7%E6%9D%80%E5%99%A8%E4%B9%8B%E6%80%A7%E8%83%BD%E5%89%96%E6%9E%90%20PProf.md)
- [7 种 Go 程序性能分析方法](https://www.7ethan.top/article/golang/94)
- [使用 LLDB 调试 Go 程序](https://colobu.com/2018/03/12/Debugging-Go-Code-with-LLDB/)

### 并发

- [Go并发编程-Goroutine如何调度的?](https://mp.weixin.qq.com/s/eDpNOUR1uKUsV39jDe_w4A)

### 杂项

- [Go Channel 高级实践](https://segmentfault.com/a/1190000016197615)
- [Go Defer 高级实践](https://segmentfault.com/a/1190000016666245)
- [Go 程序是如何编译成目标机器码的](https://segmentfault.com/a/1190000016523685)
- [Go 的栈空间管理](https://zhuanlan.zhihu.com/p/46532477)