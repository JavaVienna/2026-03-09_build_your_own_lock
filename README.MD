# Building your own lock (from scratch)

Talk given at [JavaVienna](https://www.meetup.com/Java-Vienna/) on March 9th, 2026.

## Abstract

In this talk we are going to investigate how locks can be built from concurrency primitives and discuss various questions around atomics along the way.

## Speaker

**Matthias Langer** is an IT enthusiast with 20+ years of experience with JVM technologies and is always eager to learn.

## Code

The talk code is available at various stages in the following branches:

- [build-your-own-lock-from-scratch-start](https://github.com/JavaVienna/2026-03-09_build_your_own_lock/tree/build-your-own-lock-from-scratch-start) — Starting point
- [build-your-own-lock-from-scratch-live](https://github.com/JavaVienna/2026-03-09_build_your_own_lock/tree/build-your-own-lock-from-scratch-live) — Live coding during the talk
- [build-your-own-lock-from-scratch](https://github.com/JavaVienna/2026-03-09_build_your_own_lock/tree/build-your-own-lock-from-scratch) — Work in progress
- [build-your-own-lock-from-scratch-end](https://github.com/JavaVienna/2026-03-09_build_your_own_lock/tree/build-your-own-lock-from-scratch-end) — Final state
- [build-your-own-lock-from-scratch-end-with-comments](https://github.com/JavaVienna/2026-03-09_build_your_own_lock/tree/build-your-own-lock-from-scratch-end-with-comments) — Final state with comments

## Benchmarks

Execute `./gradlew jmh` to execute the JMH benchmarks contained in this repo.
