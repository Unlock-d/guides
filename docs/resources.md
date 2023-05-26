# Useful Packages

## Unit Testing

- [fake_async](https://pub.dev/packages/fake_async)
This package provides a FakeAsync class, which makes it easy to deterministically test code that uses asynchronous features like Futures, Streams, Timers, and microtasks.
It creates an environment in which the user can explicitly control Dart's notion of the "current time".
When the time is advanced, FakeAsync fires all asynchronous events that are scheduled for that time period without actually needing the test to wait for real time to elapse.
