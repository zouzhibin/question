## 函数相关的
- 高阶函数  发布订阅模式（解耦） 观察者模式
  vue里面 数据会依赖很多的watcher, 当数据变化后 自动触发自己身上的注册的观察者


## 实现函数柯里化，反柯里化，防抖和节流


## Promise 相关的
- 掌握Promise实现原理
- Promise中all ,race,finally,promisify 实现原理 then的特点
- co库的实现原理及generator的应用 异步迭代
- setTimeout、Promise、Async/Await 的区别
  
## 
- 实现一个批量请求函数 multiRequest(urls,maxNum)
- 最大并发数 maxNum
- 每当有一个请求返回 就留下一个空位 可以增加新的请求
- 所有请求完成后，结果安装urls里面的顺序依次打出


- 使用promise.all 进行5个请求，若其中1个返回失败，怎么让其他4个可以成功返回


## 浏览器中的EvenetLoop 和NODE中的EventLoop
- EventLoop 事件循环（浏览器的事件环）NodeJS事件循环机制 
- 哪些是宏任务和微任务 （宿主环境提供的方法都是宏任务）（语言实现的mutionbserver promise）

## node的核心
- NodeJS优缺点及应用场景 ,node核心有哪些内置类库?cpu密集、io密集
- NodeJS 是单线程还是多线程 都有哪些现场 JS为什么是单线程的 ？
- process.nextTick()的作用
- nodejs高并发怎么理解？ 为什么不适合运算量大的操作？

## 模块
- 模板引擎的实现原理 ejs的实现
- 介绍模块化发展历程
- require 的解析规则
- CommonJS的实现原理?



## EventEmitter  *** 发布订阅模式
- 掌握 on 、emit 、off、once的实现原理(newListener)


## Buffer(操作的文件类型都是buffer)
- 说一下nodejs 里对Buffer数据类型的认识 ，对于初始化的Buffer，可以实现增加长度吗?
- Buffer.from() Buffer.alloc() Buffer.isBuffer Buffer.concat()


## 手写二进制转base64 



### fs 模块
- 掌握内部的api fs.readFile writeFile access stat .....(open,write,read)
- 需要掌握两种常见的数据结构 链表和树结构 链表如何遍历  树如何遍历


### 实现一个对象的深拷贝功能



## 流 （多个异步嵌套的情况 如何解耦合   发布订阅）
- on('data') on('end') /write end /pipe 方法
- NodeJS 中存在哪些流 ，怎么理解pipe()及其优点
- 可读流 可写流 转化流 zlib.createGZip() 双工流sokect


## http 
- 请求方法  常见的header的使用 及状态吗的应用
- 解决跨域的方案有哪些
- 表单是否可以跨域 (xss csrf)
- 304 强制缓存 和对比缓存 、gzip的压缩实现
- 301 和302 对于seo的优化


## 当一个地址从输入到展示在浏览器中有哪些步骤
- 七层协议 http应用层面 浏览器缓存 浏览器渲染原理
  

## Koa
- 掌握上下文的实现和中间件实现原理  



## 实现compose函数