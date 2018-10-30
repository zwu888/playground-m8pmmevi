```C++ runnable
#include <cstdio>

void foo(int v1, int v2, int v3, int v4)
 {
    printf("%d %d %d %d\n",v1,v2,v3,v4);
 }

 int main()
 {
    int lut[] = { 1, 2, 3, 4 };
    int idx = 0;
    foo(lut[idx++],lut[idx++],lut[idx++],lut[idx++]);
    return 0;
 }
