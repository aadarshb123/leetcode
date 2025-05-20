# neetcode 250
https://neetcode.io/practice?tab=neetcode250

| Question                                      | Difficulty | Date Solved | # Times Solved | Notes                                                        | Time Complexity            |
|-----------------------------------------------|------------|-------------|----------------|--------------------------------------------------------------|----------------------------|
| **Arrays & Hashing**                          |            |             |                |                                                              |                            |
| Concantenation of Array                       | Easy       | 4/13/2025   | 1              | Concatenate the array with itself                           | O(n)                       |
| Contains Duplicate                            | Easy       | 4/13/2025   | 1              | Compare length of list vs. set                               | O(n)                       |
| Valid Anagram                                 | Easy       | 4/13/2025   | 1              | Sort both strings (or count chars) and compare               | O(n) or O(n log n)         |
| Two Sum                                       | Easy       | 4/13/2025   | 1              | Use a dictionary                                             | O(n)                       |
| Longest Common Prefix                         | Easy       | 4/14/2025   | 1              | Nested loops over all characters                             | O(S) where S = total chars |
| Group Anagrams                                | Medium     | 4/13/2025   | 1              | Dict keyed by sorted tuple or char-count                     | O(n·m log m) or O(n·m)     |
| Remove Element                                | Easy       | 4/14/2025   | 1              | Two-pointer overwrite                                        | O(n)                       |
| Majority Element                              | Easy       | 4/14/2025   | 1              | Hash-map count (or Boyer–Moore)                              | O(n)                       |
| Design HashSet                                | Medium     | 4/14/2025   | 1              | Wrap built-in `set`                                          | O(1) avg                   |
| Design HashMap                                | Medium     | 4/14/2025   | 1              | Wrap built-in `dict`                                         | O(1) avg                   |
| Sort an Array                                 | Medium     | 4/14/2025   | 1              | Any efficient sort (e.g., mergesort, heapsort)               | O(n log n)                 |
| Sort Colors                                   | Medium     | 4/14/2025   | 1              | Count frequencies of 0/1/2 then overwrite                   | O(n)                       |
| Top K Frequent Elements                       | Medium     | 4/14/2025   | 1              | Bucket-sort or heap                                          | O(n + k) / O(n + k log n)  |
| Encode and Decode String                      | Medium     | 4/29/2025   | 1              | Prefix each word with its length and a delimiter             | O(n)                       |
| Range Sum 2D Immutable                        | Medium     | 4/30/2025   | 1              | Precompute 2D prefix sums                                    | O(m·n)                     |
| Product of Array Except Self                  | Medium     | 4/30/2025   | 1              | Two-pass prefix/suffix products                              | O(n)                       |
| Valid Sudoku                                  | Medium     | 4/30/2025   | 1              | Three hash-maps for rows/cols/boxes                          | O(m·n)                     |
| Longest Consecutive Sequence                  | Medium     | 4/30/2025   | 1              | Hash-set scan for sequence starts                            | O(n)                       |
| Best Time to Buy and Sell Stock II            | Easy       | 5/1/2025    | 1              | Greedy capture every upward slope                            | O(n)                       |
| Majority Element II                           | Medium     | 5/1/2025    | 1              | Boyer–Moore extension or hash-map                            | O(n)                       |
| **Sum Array Sum Equals K**                    |            |             |                |                                                              |                            |
| First Missing Positive                        | Hard       | 4/14/2025   | 1              | Place each number in its “index slot” then scan              | O(n)                       |
| **Two Pointers**                              |            |             |                |                                                              |                            |
| Reverse String                                | Easy       |             |                |                                                              | O(n)                       |
| Valid Palindrome                              | Easy       |             |                |                                                              | O(n)                       |
| Valid Palindrome II                           | Easy       |             |                |                                                              | O(n)                       |
| Merge Strings Alternately                     | Easy       |             |                |                                                              | O(m + n)                   |
| Merge Sorted Array                            | Easy       |             |                |                                                              | O(m + n)                   |
| Remove Duplicates From Sorted Array           | Easy       |             |                |                                                              | O(n)                       |
| Two Sum II (Input Array Sorted)               | Easy       |             |                |                                                              | O(n)                       |
| 3 Sum                                         | Medium     |             |                |                                                              | O(n²)                      |
| 4 Sum                                         | Medium     |             |                |                                                              | O(n³)                      |
| Rotate Array                                  | Easy       |             |                |                                                              | O(n)                       |
| Container With Most Water                     | Medium     |             |                |                                                              | O(n)                       |
| Boats to Save People                          | Medium     |             |                |                                                              | O(n)                       |
| Trapping Rain Water                           | Hard       |             |                |                                                              | O(n)                       |
| Sliding Window                                | Medium     |             |                | (generic “Sliding Window” patterns)                          | O(n)                       |
| Contains Duplicate II                         | Easy       |             |                |                                                              | O(n)                       |
| Best Time to Buy and Sell Stock               | Easy       |             |                |                                                              | O(n)                       |
| Longest Substring Without Repeating Characters| Medium     |             |                |                                                              | O(n)                       |
| Longest Repeating Character Replacement       | Medium     |             |                |                                                              | O(n)                       |
| Permutation in String                         | Medium     |             |                |                                                              | O(n)                       |
| Minimum Size Subarray Sum                     | Medium     |             |                |                                                              | O(n)                       |
| Find K Closest Subarray Sum                   | Hard       |             |                | (usually uses two-pointers + prefix sums)                    | O(n log n)                 |
| Minimum Window Substring                      | Hard       |             |                |                                                              | O(n)                       |
| Sliding Window Maximum                        | Hard       |             |                |                                                              | O(n)                       |
| **Stack**                                     |            |             |                |                                                              |                            |
| Baseball Game                                 | Easy       |             |                |                                                              | O(n)                       |
| Valid Parentheses                             | Easy       |             |                |                                                              | O(n)                       |
| Implement Stack Using Queues                  | Easy       |             |                |                                                              | O(1) per op                |
| Implement Queue Using Stacks                  | Easy       |             |                |                                                              | O(1) amortized             |
| Min Stack                                     | Easy       |             |                |                                                              | O(1) per op                |
| Evaluate Reverse Polish Notation              | Medium     |             |                |                                                              | O(n)                       |
| Generate Parentheses                          | Medium     |             |                |                                                              | Catalan(n) outputs         |
| Asteroid Collision                            | Medium     |             |                |                                                              | O(n)                       |
| Daily Temperatures                            | Medium     |             |                |                                                              | O(n)                       |
| Online Stock Span                             | Medium     |             |                |                                                              | O(n)                       |
| Car Fleet                                     | Medium     |             |                |                                                              | O(n log n)                 |
| Simplify Path                                 | Medium     |             |                |                                                              | O(n)                       |
| Decode String                                 | Medium     |             |                |                                                              | O(n)                       |
| Maximum Frequency Stack                       | Medium     |             |                |                                                              | O(1) per op                |
| Largest Rectangle in Histogram                | Hard       |             |                |                                                              | O(n)                       |
| **Binary Search**                             |            |             |                |                                                              |                            |
| Binary Search                                 | Easy       |             |                |                                                              | O(log n)                   |
| Search Insert Position                        | Easy       |             |                |                                                              | O(log n)                   |
| Guess Number Higher or Lower                  | Easy       |             |                |                                                              | O(log n)                   |
| Sqrt(x)                                       | Easy       |             |                |                                                              | O(log n)                   |
| Search a 2D Matrix                            | Medium     |             |                |                                                              | O(log m + log n)           |
| Koko Eating Bananas                           | Medium     |             |                |                                                              | O(n log n)                 |
| Capacity to Ship Packages                     | Medium     |             |                |                                                              | O(n log n)                 |
| Find Minimum in Rotated Sorted Array          | Medium     |             |                |                                                              | O(log n)                   |
| Search In Rotated Sorted Array                | Medium     |             |                |                                                              | O(log n)                   |
| Search In Rotated Sorted Array II             | Hard       |             |                |                                                              | O(log n)                   |
| Time Based Key-Value Store                    | Medium     |             |                |                                                              | O(log n) per op            |
| Split Array Largest Sum                       | Hard       |             |                |                                                              | O(n log n)                 |
| Median of Two Sorted Arrays                   | Hard       |             |                |                                                              | O(log (min(m,n)))          |
| Find in Mountain Array                        | Hard       |             |                |                                                              | O(log n)                   |
