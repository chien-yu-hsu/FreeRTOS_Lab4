"# lab4-heap2_free_memory_merge-chien-yu-hsu" 
# Embedded_OS_Lab4_NE6091116
## Overview

Implement vPrintFreeList and modifying prvInsertBlockIntoFreeList code to implement memory merge.

## vPrintFreeList

先建一個陣列放title,接著定義兩個指標分別放xStart和xEnd的位址。

<img width="495" alt="lab4 code1" src="https://user-images.githubusercontent.com/80887185/123530336-96e3a900-d72b-11eb-9562-639b33e5d037.PNG">

建立四個char分別放，StartAddress、heapSTRUCT_SIZE、xBlockSize、EndAddress.
使用Uint32ConvertHex將得到的位址轉成16進制再放進char.
每次做完,pxLinkList都會指向下個可用的Block,直到"pxLinkList == end"才結束迴圈。


"# FreeRTOS_Lab4" 
"# FreeRTOS_Lab4" 
