# Go-Internals![image title](http://www.zpoint.xyz:8080/count/tag.svg?url=github%2Fgo-Internals-CN)
* [English](https://github.com/zpoint/Go-Internals)
* 如果你需要接收更新通知, 点击右上角的 **Watch**, 当有文章更新时会在 issue 发布相关标题和链接

这个仓库是本人分析 [go](https://github.com/golang/go) 源码的时候做的记录/博客

```shell script
# based on the current master branch which is 1.15
cd go
git reset --hard d317ba5d4489c1ef53d3077afbff30eb72d7d3b0
```

本人是 [go](https://github.com/golang/go) 新手, 本人在写下列内容时会尽力保持和 [CPython-Internals](https://github.com/zpoint/CPython-Internals) 还有 [Redis-Internals](https://github.com/zpoint/Redis-Internals) 一致的风格



# 目录

* [Debug](#Debug)
* [Objects](#Objects)
* [Runtime](#Runtime)

# Debug

- [x] [setup(编译安装额外版本/runtime包中增加print函数调用)](https://github.com/zpoint/Go-Internals/blob/1.15/debug/setup/setup_cn.md)

# Objects

- [x] [map](https://github.com/zpoint/Go-Internals/blob/1.15/objects/map/map_cn.md)
- [x] [channel](https://github.com/zpoint/Go-Internals/blob/1.15/objects/chan/chan_cn.md)

# Runtime

- [x] goroutine
	- [x] [概览与调度](https://github.com/zpoint/Go-Internals/blob/1.15/runtime/goroutine/goroutine_cn.md)
- [ ] [垃圾回收](https://github.com/zpoint/Go-Internals/blob/1.15/runtime/gc/gc_cn.md)
- [ ] [内存管理](https://github.com/zpoint/Go-Internals/blob/1.15/runtime/memory_management/memory management_cn.md)

