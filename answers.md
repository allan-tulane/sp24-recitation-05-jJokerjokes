# CMPS 2200 Reciation 5
## Answers

**Name:**___Charles Zhang______________________


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
<img width="678" alt="image" src="https://github.com/allan-tulane/sp24-recitation-05-jJokerjokes/assets/143116067/c497ef29-40d7-4ee7-8396-2017677edc38">

the Ssort will hit the recursion limit if the list size is any larger.

Fixed Pivot Quicksort seems to scale reasonably well as the list size increases. This is expected because as quicksort is typically $O(nlog n)$.

Random Pivot Quicksort displays a similar trend to fixed pivot quicksort but with slightly higher running times. The randomness is intended to avoid the worst-case scenario of $O(n^2)$, which can occur with a fixed pivot in certain list arrangements. The overhead of choosing a random pivot may account for the extra time.

The recursive Selection Sort shows a significant increase in running time as the list size grows, reflecting its $O(n^2)$ complexity.





- **1c.**

output has shown above.

While Random Pivot Quicksort does better than Fixed Pivot Quicksort and significantly better than the recursive Selection Sort, it does not surpass TimSort. TimSort is a merge sort variant that benefits from pre-sorted patterns in the data with complexity of  $O(n log n)$.
