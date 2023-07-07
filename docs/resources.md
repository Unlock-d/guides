# Useful Packages

## State management

- The [Flutter docs](https://docs.flutter.dev/data-and-backend/state-mgmt/options) contains an extensive list of possible packages.

## Unit Testing

- [clock](https://pub.dev/packages/clock)
This package provides a Clock class which encapsulates the notion of the "current time" and provides easy access to points relative to the current time.
Different Clocks can have a different notion of the current time, and the default top-level clock's notion can be swapped out to reliably test timing-dependent code.

- [fake_async](https://pub.dev/packages/fake_async)
This package provides a FakeAsync class, which makes it easy to deterministically test code that uses asynchronous features like Futures, Streams, Timers, and microtasks.
It creates an environment in which the user can explicitly control Dart's notion of the "current time".
When the time is advanced, FakeAsync fires all asynchronous events that are scheduled for that time period without actually needing the test to wait for real time to elapse.
