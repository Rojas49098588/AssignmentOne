# AssignmentOne

Objective:
In this assignment, you will use stacks and queues to process a log file containing 10,000
entries. Each log entry follows a specific format that includes a timestamp, log level, and
message. The goal is to demonstrate your understanding of stack and queue operations by
implementing a series of tasks.

Log Entry Format Example:
[2024-08-23 14:35:21] INFO User123 logged in
[2024-08-23 14:35:22] ERROR Database connection failed
[2024-08-23 14:35:23] WARN Memory usage at 85%

Tasks:
1. Implement Queue Operations:
o Read the log file into your program.
o Enqueue all log entries into a queue.
o Dequeue entries one by one until the queue is empty (do not print them)

3. Implement Stack Operations:
o Implement a stack to handle and store error log entries (log level: ERROR).
o Every time an error log entry is dequeued from the queue, it should be
pushed onto the stack.

5. Data Analysis
o Implement functionality to perform the following analysis on the log data:
1. Count Log Levels: Calculate the total number of entries for each log
level (INFO, WARN, ERROR). Hint: Do the calculations during
dequeue.
2. Recent Errors: Provide a list of the last 100 errors that occurred.
3. Memory Warnings: Track how many times a memory warning (log
level: WARN, containing "Memory") appears.
4. Performance Considerations:
o Your implementation should be efficient in terms of time and space,
especially given the large dataset.
o Consider the use of appropriate data structures and algorithms to handle the
high volume of log entries. Solution hint: Use linked list for the
implementation of both queue and stack.
Submission: All source files should be uploaded to Github. You will submit the link to your
GitHub repository on Canvas. You can work in pairs for this assignment. Team members’
names and IDs should be included in a README file.
