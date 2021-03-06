# takeLastWithTime

`Rx.Observable.prototype.takeLastWithTime(duration, [timeScheduler], [loopScheduler])`
<a href="#rxobservableprototypetakelastwithtimeduration-timescheduler-loopscheduler">#</a> [&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/takelastwithtime.js "View in source") 

Returns elements within the specified duration from the end of the observable source sequence, using the specified schedulers to run timers and to drain the collected elements.

#### Arguments
1. `duration` *(`Number`)*: Duration for taking elements from the end of the sequence.
2. `[timeScheduler=Rx.Scheduler.timeout]` *(`Scheduler`)*: Scheduler to run the timer on. If not specified, defaults to timeout scheduler.
2. `[loopScheduler=Rx.Scheduler.currentThread]` *(`Scheduler`)*: Scheduler to drain the collected elements. If not specified, defaults to current thread scheduler.

#### Returns
*(`Observable`)*: An observable sequence with the elements taken during the specified duration from the end of the source sequence.
    
#### Example

[](http://jsbin.com/liwori/1/embed?js,console)

### Location

File:
- [`/src/core/observable/takelastwithtime.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/takelastwithtime.js)

Dist:
- [`rx.time.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.time.js)

Prerequisites:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Time`](http://www.nuget.org/packages/RxJS-Time/)

Unit Tests:
- [`/tests/observable/takelastwithtime.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/takelastwithtime.js)