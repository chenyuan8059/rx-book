# let | letBind

`Rx.Observable.prototype.let(func)`
<a href="#rxobservableprototypeletfunc">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.experimental.js#L76-L78 "View in source") 

Returns an observable sequence that is the result of invoking the selector on the source sequence, without sharing subscriptions.

This operator allows for a fluent style of writing queries that use the same sequence multiple times.  There is an alias of `letBind` for browsers older than IE 9.

#### Arguments
1. `func` *(`Function`)*: Selector function which can use the source sequence as many times as needed, without sharing subscriptions to the source sequence.

#### Returns
*(`Observable`)*: An observable sequence that contains the elements of a sequence produced by multicasting the source sequence within a selector function.

#### Example

[](http://jsbin.com/jetido/1/embed?js,console)

#### Location

- [`rx`](https://www.npmjs.org/package/rx).experimental.js