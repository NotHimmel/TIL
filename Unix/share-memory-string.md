# 共享内存中的string
share memory分配内存时，sizeof定长，如果要存string，可以分配定长的char数组，char abc[256];