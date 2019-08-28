## syncmap

golang好不容易官方支持了协程安全的map，但是却不支持len方法。。。

这个实现基于官方的sync.Map ，加了 len 方法，加了Delete时返回是否删除成功的flag。

