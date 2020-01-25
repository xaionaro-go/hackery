# Magic comments

* [`//go:generate`](https://golang.org/pkg/cmd/go/internal/generate/)
* [`//go:linkname`](https://sitano.github.io/2016/04/28/golang-private/)
* [`//go:noescape`](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
* [`//go:noinline`](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
* [`//go:nosplit`](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
* [`//go:norace`](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
* [`//line`](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
* [`// import`](https://dave.cheney.net/2018/01/08/gos-hidden-pragmas)
* [`//go:systemstack`](https://github.com/golang/go/blob/master/src/runtime/HACKING.md)
* [`//go:nowritebarrierrec`](https://github.com/golang/go/blob/master/src/runtime/HACKING.md)
* [`//go:yeswritebarrierrec`](https://github.com/golang/go/blob/master/src/runtime/HACKING.md)
* [`//go:notinheap`](https://github.com/golang/go/blob/master/src/runtime/HACKING.md)

# Hidden (but useful) functions

To use this functions you need to use `//go:linkname`.

* [`notewakeup`](https://lk4d4.darth.io/posts/go-timers/)
* [`getg`](https://github.com/golang/go/issues/18590)

# Guides

* [Reduce the size of a binary](https://github.com/xaionaro/documentation/blob/master/golang/reduce-binary-size.md)
