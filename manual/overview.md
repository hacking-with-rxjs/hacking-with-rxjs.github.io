# 介绍

`RxJS`通过使用可观察的队列(`observable sequences`)来构成异步的和以事件为基础的程序。它提供了一种核心的类型,那就是可观察的对象
([`Observable`](http://reactivex.io/rxjs/manual/overview.html#observable))还有与之辅助的其它类型
(包括`Observer`(观察者), `Schedulers`, `Subjects`);并且通过使用操作符(受到数组的一些方法(`map`, `filter`, `reduce`, `every`, etc)的启发)
允许我们把**异步事件**当做集合来处理。

> 可以把RxJS看作是处理事件的[`Lodash`](https://lodash.com/)库。

`ReactiveX`结合了**观察者模式**(`Observer pattern`)和**迭代器模式**(`Iterator pattern`)
以及**集合的函数式编程(`functional programming with collections`)**为了满足我们对于处理事件队列的理想要求。