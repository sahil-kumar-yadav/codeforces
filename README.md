# codeforces

## Template
```cpp
#include <bits/stdc++.h>

using namespace std;
int main(){
    // n meter into k pieces a1,a2,a3..ak
    // pick ai>=2  divide it into length 1 and ai-1
    // pick ai ans aj = 1 merge
    // help to merge 
    // 5 3
    // 3 1 1 
    // 1 - 3+1 = [4,1];
    // 2 [4+1]
    // 1 2 3 5 .1
    // 2 3 6 --> break - 1 1 3 6
    // 1 3 7
    // 3 8
    // 1 2 8 
    // 2 9
    // 1 1 9
    // 1 10
    // 11
    return 0;

}
```