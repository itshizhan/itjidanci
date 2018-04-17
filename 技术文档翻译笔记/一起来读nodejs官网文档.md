
# nodejs英文文档中值得品味的1000个单词或短语


## 0001： is spawned with 由……产生，由……创建的

If the Node.js process is spawned with an IPC channel (see the Child Process and Cluster documentation), the 'disconnect' event will be emitted when the IPC channel is closed.

如果node 进程是由IPC通道创建的，则当IPC通道关闭时，会产生disconnect事件。

> spawn: 原意是：鱼卵、产卵，引申为：生产，创建，产物。

> 电影《再生侠》（spawn）是一部科幻电影，改编自托德·麦克法兰的漫画，是美国Image漫画旗下超级英雄。

 #### 提示：spawn一词在编程语言中使用极其广泛，很多编程语言中都有 spawn 函数。例如nodejs 中的：

 `child_process.spawn(command[, args][, options])` :使用给定的 command 和 args 中的命令行参数来衍生一个新的进程。

由于同一命令，不同平台的执行方式可能不同，因此有一个不错的跨平台执行 spawn 函数的npm 包：

```js
npm install cross-spawn 
//A cross platform solution to node's spawn and spawnSync

```



