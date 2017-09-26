# Reactive Programming with Reactor Core / WIP

[![](https://travis-ci.org/vicboma1/Reactive-Programming-with-Reactor-Core.svg?branch=master)](https://travis-ci.org/vicboma1/Reactive-Programming-with-Reactor-Core)
[![Coverage Status](https://coveralls.io/repos/github/vicboma1/Reactive-Programming-with-Reactor-Core/badge.svg?branch=master)](https://coveralls.io/github/vicboma1/Reactive-Programming-with-Reactor-Core?branch=master)  ![](https://img.shields.io/badge/Java-1.9-blue.svg)  ![](https://img.shields.io/badge/JUnit-4.11-orange.svg)

## Flux - [Testing](https://github.com/vicboma1/Reactive-Programming-with-Reactor-Core/blob/master/src/test/java/core/FluxTest.java)

* never
* just
* fromIterable
* fromArray
* fromStream
* concatWith
* first
* toIterable
* subscribe
* generate
* handle
* using
* range
* doFinally
* onError
* doOnNext
* doOnEach
* elapse
* retry
* exceptions
* retryWhen
* try-catch
* propagate
* log
* transform
* compose
* doOnNext
* merge
* mergeSequential

## Mono - [Testing](https://github.com/vicboma1/Reactive-Programming-with-Reactor-Core/blob/master/src/test/java/core/MonoTest.java)

* just
* delay
* add
* delayElement
* delaySubscription
* as
* cast
* create
* block
* empty
* justOrEmpty
* first
* fromSupplier
* fromCallable
* fromRunnable
* fromCompletable 
* zip

## MonoProcessor - [Testing](https://github.com/vicboma1/Reactive-Programming-with-Reactor-Core/blob/master/src/test/java/mono/MonoProcessorTest.java)

* block
* toFuture
* subscribe
* doOnSubscribe
* doOnSuccess
* doOnNext
* doOnRequest
* doOnEach
* doOnTerminate
* doOnError
* downstreamCount
* hasDownstreams


## Schedulers - [Testing](https://github.com/vicboma1/Reactive-Programming-with-Reactor-Core/blob/master/src/test/java/core/parallelFluxTest.java)

* parallel
* elastic
* inmediate
* fromExecutor
* fromExecutorService

## ParallelFlux with Schedulers - [Testing](https://github.com/vicboma1/Reactive-Programming-with-Reactor-Core/blob/master/src/test/java/core/parallelFluxTest.java)

* parallel
* groups

## ConnectableFlux - [Testing](https://github.com/vicboma1/Reactive-Programming-with-Reactor-Core/blob/master/src/test/java/core/connectableFluxTest.java)

* connect 
* autoConnect

## Custom sources : Flux.create and FluxSink, Mono.create and MonoSink

References
  * https://github.com/vicboma1/Reactive-Programming-with-JDK-9-Flow-API 
  * https://github.com/reactor/reactor-core
  * http://projectreactor.io/docs/core/release/reference/docs/index.html
  * https://projectreactor.io/docs/core/release/api/
  * https://github.com/reactor/lite-rx-api-hands-on
  * https://www.infoq.com/articles/reactor-by-example/
  
