# RxJavaBasicExample

RxJava is all about two key components: Observable and Observer. In addition to these, there are other things like Schedulers, Operators and Subscription.

Observable: Observable is a data stream that do some work and emits data.

Observer: Observer is the counter part of Observable. It receives the data emitted by Observable.

Subscription: The bonding between Observable and Observer is called as Subscription. There can be multiple Observers subscribed to a single Observable.

Operator / Transformation: Operators modifies the data emitted by Observable before an observer receives them.

Schedulers: Schedulers decides the thread on which Observable should emit the data and on which Observer should receives the data i.e background thread, main thread etc.,

Disposable: Disposable is used to dispose the subscription when an Observer no longer wants to listen to Observable. In android disposable are very useful in avoiding memory leaks.

filter() operator filters the data by applying a conditional statement. The data which meets the condition will be emitted and the remaining will be ignored.

