# from

`Rx.Observable.from(iterable, [mapFn], [thisArg], [scheduler])`
[&#x24C8;](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/from.js "View in source")

This method creates a new Observable sequence from an array-like or iterable object.

#### Arguments
1. `iterable` *(`Array` | `Arguments` | `Iterable`)*: An array-like or iterable object to convert to an Observable sequence.
2. `[mapFn]` *(`Function`)*: Map function to call on every element of the array.
3. `[thisArg]` *(`Any`)*: The context to use calling the mapFn if provided.
4. `[scheduler=Rx.Scheduler.currentThread]` *(`Scheduler`)*: Scheduler to run the enumeration of the input sequence on.

#### Returns
*(`Observable`)*: The observable sequence whose elements are pulled from the given iterable sequence.

#### Example

##### Array-like object (arguments) to Observable

[](http://jsbin.com/dekire/1/embed?js,console)

##### Set

[](http://jsbin.com/dapoju/2/embed?js,console)

##### Map

[](http://jsbin.com/yukiyu/2/embed?js,console)

##### String

[](http://jsbin.com/bemuqa/1/embed?js,console)

##### Array

[](http://jsbin.com/tiluno/1/embed?js,console)

##### Generate a sequence of numbers

[](http://jsbin.com/piyehe/1/embed?js,console)

### Location

File:
- [`/src/core/linq/observable/from.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/src/core/linq/observable/from.js)

Dist:
- [`rx.all.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.js)
- [`rx.all.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.all.compat.js)
- [`rx.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.js)
- [`rx.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/dist/rx.compat.js)
- [`rx.lite.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.js)
- [`rx.lite.compat.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/rx.lite.compat.js)

Prerequisites:
- None

NPM Packages:
- [`rx`](https://www.npmjs.org/package/rx)

NuGet Packages:
- [`RxJS-Complete`](http://www.nuget.org/packages/RxJS-Complete)
- [`RxJS-Main`](http://www.nuget.org/packages/RxJS-Main/)
- [`RxJS-Lite`](http://www.nuget.org/packages/RxJS-Lite/)

Unit Tests:
- [`/tests/observable/from.js`](https://github.com/Reactive-Extensions/RxJS/blob/master/tests/observable/from.js)
