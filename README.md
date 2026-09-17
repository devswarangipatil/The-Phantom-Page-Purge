# The-Phantom-Page-Purge

A historian is digitizing an ancient manuscript. The pages have already been sorted by their page numbers, but due to a scanning error, some pages were scanned multiple times and appear as consecutive duplicates in the archive.

The historian wants to remove these duplicates in-place — without allocating extra storage — so that each unique page number appears exactly once at the front of the archive, in sorted order. The remaining positions at the back do not matter.

Return the number of unique pages. The first k entries of the modified array must be the unique values in sorted order.

Input
The first line contains an integer 
n
n. The second line contains 
n
n space-separated integers in non-decreasing order.

Output
The first line contains 
k
k — the count of unique elements. The second line contains the 
k
k unique values in sorted order.

Constraints 
1 ≤ n ≤ 30000 
−100≤nums i ​ ≤100 
Array is sorted in non-decreasing order.

Array is sorted in non-decreasing order.

Example
Example 1:
Input
3
1 1 2
Output
2
1 2

Example 2:
Input
10
0 0 1 1 1 2 2 3 3 4
Output
5
0 1 2 3 4
