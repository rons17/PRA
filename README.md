## Page-Replacement-Algorithms
#### It is one of the most important algorithm of memory management in Operating System.
#### Whenever Page Fault occurs, that is, a process tries to access a page which is not currently present in a frame and OS must bring the page from swap-space to a frame.
#### OS must do page replacement to accommodate new page into a free frame, but there might be a possibility the system is working in high utilization and all the frames are busy, in that case OS must replace one of the pages allocated into some frame with the new page.
#### The page replacement algorithm decides which memory page is to be replaced. Some allocated page is swapped out from the frame and new page is swapped into the freed frame.
#### Types of Page Replacement Algorithm: (AIM is to have minimum page faults)
1) FIFO
   1) Allocate frame to the page as it comes into the memory by replacing the oldest page.
   2) Easy to implemen
2) LRU
   1) We can use recent past as an approximation of the near future then we can replace the
   page that has not been used for the longest period.
   2) Can be implemented by 2 methods Counter and Stack methods.
4) OPR
   1) Find if a page that is never referenced in future. If such a page exists, replace this   
   page with new page.
   2) If no such page exists, find a page that is referenced farthest in future. Replace this     page with new page.
   3) Lowest page fault rate among any algorithm.
   4) Difficult to implement as OS requires future knowledge of reference string which is
   kind of impossible.


#### Run codes of all algorithms and display the output in a well mannered step by step frame arrays along with page faults.
#### No. of hits , i.e hit rate and ultimately fault rate can also be calculated and the effectiveness of each algorithm is judged.
#### Finally , frame a report consists of input , cosdes,output screenshots, theory , pseudocode of all three algorithms.
