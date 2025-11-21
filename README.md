Mini-Project 2 – Multi-Threaded Log Analyzer

Objective To design and implement a concurrent system that processes multiple log files simultaneously, applies Stream pipelines for aggregation, and uses thread pools for scalability.

Requirements

● Input: Folder path containing text log files.

● Each file analyzed by a separate worker thread (Callable returning result).

● Use ExecutorService with fixed pool of N threads.

● Use ConcurrentHashMap to aggregate keyword counts.

● Measure total execution time.

● Output summary to console and write to result file.

Deliverables

Source code and compiled output.

Execution time comparison between sequential and concurrent versions

Screenshot of thread-pool monitoring (Task Manager or console logs).

README with explanation of concurrency strategy.
