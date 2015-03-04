Rust Skiplist
=============

A [skiplist](http://en.wikipedia.org/wiki/Skip_list) provides a way of storing
data with `log(i)` access, insertion and removal for an element in the `i`th position.

There are three kinds of collections defined here:
- **SkipList**  This behaves like nearly any other double-ended list.
- **OrderedSkipList**  Ensures that the elements are always sorted.  Still
  allows for access nodes at a given index.
- **SkipMap**  A map in which the keys are ordered.

Documentation can be found
[here](https://jp-ellis.github.io/rust-skiplist/skiplist/) and the cargo crate
can be found [here](https://crates.io/crates/skiplist).
