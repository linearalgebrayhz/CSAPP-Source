Here are some supplementary notes for Ch2

size_t 是一个标准 C 语言数据类型,它用于表示对象的大小。以下是定义
```c
typedef unsigned long size_t;
```

也就是说,size_t 是一个无符号长整型(unsigned long)。它通常用于以下几种情况:

1. 表示数组的长度或者字符串的长度。
2. 作为 malloc() 和 calloc() 等动态内存分配函数的参数类型。
3. 作为 sizeof 运算符的返回类型。
4. 作为 memcpy() 、 memset() 等内存操作函数的参数类型。

使用 size_t 的好处是,它可以确保在不同的计算机架构(32位或64位)上,内存相关的操作都能正确地处理大小。这有助于编写可移植性更好的代码。