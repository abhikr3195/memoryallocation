# Memory Allocation
There are two ways that memory get allocated for data storage.

 ###  Compile Time(or Static) Allocation
      - Memory for named variables is allocated by the compiler
      - Exact size and type of storage must be known at compile time
      - For standard array declarations, this is why the size has to be constant

###  Dynamic Memory Allocation
      - Memory allocated “on the fly” during run time 
      - Dynamically allocated space are usually placed in a program                                            
        segment known as the heap or the free store
      - Exact amount of space or number of items does not have to be known by the compiler in advance.
      - For dynamic memory allocation, pointers are crucial
      - For this reason, dynamic allocation requires two steps
          - Creating the dynamic space
          - Storing its address in a pointer
      - To dynamically allocate memory in C++, we use new operator and to deallocate memory we use               
        delete operator.
      
      
            Allocation
            int * prtr= new int[40];
            Deallocation
            delete [] ptr;     
