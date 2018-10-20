# QuickSort
A beginner's guide to quick sort

This is ONE of a series made to be helpful to newbs in the Data struuctures and algorithms, to help them grasp the algorithms and its intuitions, i hope you find it helpful, if you want any more clarification or an algorithm to be broken down by me in this style just send a mail, thanks a lot for checking this.
- This algorithm's intuition is about choosing a pivot and comparing all the elements to it, 
  then the smaller elements are placed to the left of the array, while the lerger elements are moved to the right part after the pivot, 
  the pivot here is selected based on different aspects, in this implementation it is choosen as the first element in the array, the important
  thing here in choosing the pivot is to make it as close to the median as possible, so it will place mostly half the smaller elements
  in the array to the left, and the rest to the right.
- O(n^2), if the pivot is the smallest or largest element in the array, but the closer the pivot to the median the better it is O(n log n (to the base 2)).
- In-place algorithm, does not need any extra space.
- Unstable algorithm, the order of the duplicate algorithms is not preserved.
- Some variations of this algorithms are found, like the dual pivot quick sort, which utilizes 2 pointers, which makes the complexity much better. 
