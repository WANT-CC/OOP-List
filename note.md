# 内存 4 区

1. 代码区：函数代码存放在代码区。函数名就是这个函数的地址。（妙用）
2. 全局区：全局变量 字符串常量 初始化 `int a;`
3. 栈区：定义变量
4. 堆区：自己开辟和释放，自己确定有多大，装什么数据，

```c++
#include <stdlib.h>
int *p;
p = (int *)malloc(size);
// 在堆区开辟 size 个字节的内存
// 指针 p 指向这段内存

// 主动释放内存
free(p);	// c
// c++ 用 new delete
```

# 链表

链表：一种数据结构

节点：每一块内存

数据：每个节点内存放的数据