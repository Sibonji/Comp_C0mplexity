# Comp_Complexity

To run programm type in cmd line:
python3 merge_sort.py 

Output should be like this:

List length: 461131
Random list generated in 0.226185
Verification of sorting algorithm: True
Single Core elapsed time: 14.404590 sec
Starting parallel sort.
Performing final merge.
Final merge duration: 7.250960 sec
Sorted arrays equal: True
2-Core elapsed time: 11.105521 sec


When executing, code uses single core implementation to test if multicore implementation is correct and to compare performance of singlecore and multicore implemetation.

Single core Merge Sort algorithm have time complexity - $\theta$(nlogn).
Multicore (p-core)  merge sort algorithm have time complexity - $\theta$(log(p)*n/p).

If we look into the test data and compare it with analytical solution we wiil see that they are converging.
