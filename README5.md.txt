# Practical 5 — Circular Queue Implementation for Parcel Handling

## Problem statement
Manage parcel numbers in a fixed-size circular queue with add, dispatch, and display operations.

## Aim / objective
To implement the above task in C and observe how the selected data structure or algorithm processes the input.

## Data structure / concepts
Array; circular queue; FIFO.

## Algorithm / approach
Use front and rear indices modulo the queue size. Detect full and empty conditions before enqueue/dequeue.

## Flowchart (text form)
```text
Start → Menu → Add/Dispatch/Display → Check full/empty → Update indices → Repeat until Exit → Stop.
```

## Sample input
```text
1
101
1
102
3
4
```

## Sample output (illustrative)
```text
Parcel 101 added.
Parcel 102 added.
Parcels in queue: 101 102
```

## Test cases
- **Normal:** Add 5 parcels.
- **Boundary / invalid:**  attempt dispatch on empty queue..
- **Additional checks:** Test the relevant menu operations and verify the output against the entered data.

## Time and space complexity
Add: O(1); dispatch: O(1); display: O(n). Auxiliary space: O(SIZE), fixed at 5.

## Compile and run
Use a standard C compiler such as GCC or Code::Blocks. In the practical folder, run:

```bash
gcc program.c -o program
./program
```

On Windows, run `program.exe` after compiling. The program is written in standard C style and the source file contains only the code (no student name or roll-number comments).

## Conclusion
The program demonstrates the selected data structure or algorithm and its basic operations. Test the normal and boundary cases before committing updates to the repository.

