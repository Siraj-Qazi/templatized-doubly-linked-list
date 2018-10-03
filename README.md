# circular-templatized-doubly-linked-list
Dynamic Templatized Linked List v1.0
By Siraj Qazi
-------------------------------------
Changelog Updated on Sept 15, 2018


Build 1.0
Sept 15, 2018, 123AM PST

   - Initial build
   - First stable version
   - Implemented all standard linked-list operations
   - Designed an interactive UI to ease usage of the Data Structure.


Build 2.0
Sept 15, 2018 249AM PST

   - Fixed all index out-of-bounds errors, particularly in the search functions.
   - [FEATURE UPDATE] Added Continuous Input Mode  Now data can be entered into a list continuously while new nodes are dynamically allocated size-by-side at runtime.
   - UI Changes
   - Minor bug fixes


Build 3.0
Sept 15, 2018 1:16PM PST

   - [FEATURE UPDATE] File IO introduced. Now linked lists can be written to and read from a file.
   - File data validity check A file with string data will not be read when in INT or FLOAT mode of      operation.
   - Separated complete list deletion to an independent deleteList() Function.
   - Cleaned main() function to do only minimal tasks.
   - UI Changes
   - Bug Fixes


Build 3.1
Sept 16, 2018 10:01PM PST

   - [STRUCTURAL CHANGE] Now a doubly-linked list. Nodes can be traversed from start to end or from end to start.
   To use the doubly-linked list functions (like reverse-traversal), #include the doubly_linked_list.h file in the Source.cpp file.
   - Added function to print list in reverse (Due to the _previous pointer)
   - Fixes and improvements

Build 3.1c
October 3rd, 2018 11:46PM PST

  - [STRUCTURAL CHANGE] Now a circular-doubly-linked-list (3.1c).
  - Print list in circular mode function added
  - Out-of-bound error fixes
