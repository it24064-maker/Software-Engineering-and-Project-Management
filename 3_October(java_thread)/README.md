# Lecture: 3 October (Java Thread Basics)

## Topics Covered
1. **Static vs Non-Static Fields**:
   - `static` field: Shared single copy across all instances/objects.
   - Non-static field: Each object holds its own independent copy.
2. **Thread Basics**:
   - Creating threads by extending the `Thread` class.
   - Multithreading lifecycle, `start()` vs `run()`, `sleep()`, and `join()`.
3. **Race Condition & Synchronization**:
   - Unsynchronized shared variable access causing lost updates.
   - Preventing race conditions using `synchronized` methods/blocks and `AtomicInteger`.

## Code Files
- Static vs Non-Static demonstration
- Java Multithreading & Race Condition experiments
