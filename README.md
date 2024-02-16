# CECS 326 Reading Assignment: Memory Management

### Assignment Description
Answer the following questions from the Chapter 3 reading from your text book. Be complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. Consider a swapping system in which memory consists of the following hole sizes in memory order: 10MB, 4MB, 20MB, 18MB, 7MB, 9MB, 12MB, and 15MB. Which hole is taken for successive segment requests of:
    - 12MB
    - 10MB
    - 9MB 
    for first fit? 
    
    Repeat the question for best fit, worst fit, and next fit.

2. What is the difference between a physical address and a virtual address?
   
3. Using the page table of Fig. 3-9 of MOS4e, give the physical address corresponding to each of the following virtual addresses:
   - 20
   - 4100
   - 8300

4. Copy on write is an interesting idea used on server systems. Does it make any sense on a smartphone? Why?

5. If FIFO page replacement is used with four page frames and eight pages, how many page faults will occur with the reference string **0172327103** if the four frames are initially empty? Repeat this problem for LRU.

6. In the WSClock algorithm of Fig. 3-20(c) on pg. 220 of **MOS4e**, the hand points to a page with R=0. If tau(400), will this page be removed? What about if tau(1000)?

7. Virtual memory provides a mechanism for isolating one process from another. What memory management difficulties would be involved in allowing two operating systems to run concurrently? How might these difficulties be addressed?

8.  When segmentation and paging are both being used, as in *MULTICS*, first the segment descriptor must be looked up, then the page descriptor. Does the TLB also work this way, with two levels of lookup?

9. A student in a compiler design course proposes to the professor a project of writing a compiler that will produce a list of page references that can be used to implement the optimal page replacement algorithm. Is this possible? Why or why not? Is there anything that could be done to improve paging efficiency at run time?

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.