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

