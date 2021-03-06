# RxJS Coincidence Module #

The Reactive Extensions for JavaScript has a set of coincidence-based operators such as `join` and `groupJoin` which allow one to correlate two observable sequences much as you would do in SQL.  There is also support for advanced windowing and bufferring capabilities which allow for the specification of opening and closing observable sequences to denote how much data to capture.

## Details ##

Files:
- [`rx.coincidence.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.coincidence.js)

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Coincidence`](http://www.nuget.org/packages/RxJS-Coincidence/)

File Dependencies:
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js) | [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js) | [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.lite.js) | [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.lite.compat.js)

NuGet Dependencies:
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)

## Included Observable Operators ##

## `Observable Instance Methods`
- [`buffer`](../core_objects/observable/observable_instance_methods/buffer.html)
- [`groupBy`](../core_objects/observable/observable_instance_methods/groupby.html)
- [`groupByUntil`](../core_objects/observable/observable_instance_methods/groupbyuntil.html)
- [`groupJoin`](../core_objects/observable/observable_instance_methods/groupjoin.html)
- [`join`](../core_objects/observable/observable_instance_methods/join.html)
- [`pairwise`](../core_objects/observable/observable_instance_methods/pairwise.html)
- [`partition`](../core_objects/observable/observable_instance_methods/partition.html)
- [`window`](../core_objects/observable/observable_instance_methods/window.html)
