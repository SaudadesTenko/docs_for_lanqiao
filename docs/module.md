---
hide:
- navigation
- footer
---

# 模块

## 1、随机整数

```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main(int argc, char const *argv[])
{
    srand(time(0));           //以当前时间作为随机生成器的种子
    int a = rand() % 100 + 1; //生成[1,100]之间的随机数
    printf("%d", a);
    return 0;
}
```

## 2、整数分解

```C
对一个整数做%10的操作，就得到它的个位数
对一个整数做/10的操作，就去掉了它的个位数
```

## 3、整数逆置

```c
明确700的逆置为007还是7
可以通过求数的阶乘，不一定用递归，也可以用循环
```
