# Pros 

- There's a pertential speed up if well implemented
- Conscise 


# Cons 

## Benchmark Crime ?

## Shadow Array's Overhead

## Demand of Compaction is a waste 

## TLB Miss Trigger is not identical to the Access Bit (VM Fault)

this is not directlyy address 

## H-Tree is not Fast, Although it can access fast
O(nlogn) performance of sorting, O(logn) for access 

## Article Problem
Step 2 ?

## High tempreture doesn't incur it's well utilised?

Addressed?

## No evidence of H-Policy have more 2MB blocks 

## Do they sampling both PTE and H-Policy?

## The analyze is not deep enough 

- There's shouldn't be that much slow down between MonH and Access Bit 
- Why the merge will cause 5 sec halt (there's not evidence of H-policy's performance while merging, high probabily they have same figure)

# Related Work 

I can't find SysMon-H and H-Policy even in Chinese Search Engine, there's impossible to reproduce the work.

The citation is irrelevant (22,27,2...TSs)

# Questions 

However, database workloads often perform poorly with THP, because they tend to have sparse rather than contiguous memory access patterns. You should disable THP on Linux machines to ensure best performance with MongoDB. [MongoDB](https://docs.mongodb.com/manual/tutorial/transparent-huge-pages/)

# Side Note 

In micro-Kernel, the application can build their own memory model to address these issue. It's enabled by micro-kernel to the application with more intergrated system-grade application. It's possible to build a database-OS with micro-kernel and only do the transaction handling with huge performance advantages.  
Disabling huge pages is a trend? But huge page is neccessary. 



