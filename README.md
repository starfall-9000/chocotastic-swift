# chocotastic-swift

tutorial for training swift and rxswift 

https://www.raywenderlich.com/900-getting-started-with-rxswift-and-rxcocoa

### learning

delegate (extension / protocol)

implement table-view (delegate / datasource)

singleton (static let)

Variable<[Chocolate]> = Variable([])

@IBOutlet

*rxswift*

Observable.just()

asObservable().subscribe(onNext:).disposed(by:)

bind(to:view.rx).disposed(by:) using for bind table view datasource (tableView.rx.items / tableView.rx.modelSelected)

combineLatest

rx extension: rx.items, rx.modelSelected, rx.text

throttle, debounce

DisposeBag - ensure observers clean up when deinit()

### reactive cocoa notes

Reactive Cocoa Basic

pod 'libextobjc'

Subscribe Next

Filter

Map

Combine

Create Signal

Flatten Map (Signal of Signal)

Do Next (side effect)

Then (chaining)

Deliver On (threadings)

Throttle

====

signal (create signal, signal for selector)

emit

subscribe (next, complete, error)

disposable

====

NOTICE

Retain Cycles

LinqToObjectiveC

====

Reactive Cocoa Advance

distinctUntilChanged

command

command excuting (not)

tuple

push view model (navigation)

binding table view

(motion design)

