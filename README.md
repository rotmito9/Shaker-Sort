# Shaker-Sort

shaker_sort(L) consumes a list of integers L, returns None and mutates L so that the list is in sorted order using shaker Sort

Shaker Sort Algorithm:

Starting from the smallest position index and alternate between the following until sorted:
Scan left to right swaping adjacent elements if out of order. In this way, the largest unsorted element is in its correct spot.
Scan right to left swaping adjacent elements if out of order. In this way, the smallest unsorted element is in its correct spot.
In this way, like a salt shaker, you alternate between ensuring the biggest and smallest elements are in order.
