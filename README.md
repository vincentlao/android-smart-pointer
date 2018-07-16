## android-smart-pointer
Android智能指针，强指针，弱指针，轻量级智能指针使用，其实很简单，就几个头文和一个cpp源文件，这是Android自己实现的一套用于内存管理的解决方案，如果你不想使用C++11提供的智能指针，这是一个很好的选择，当然了智能指针也是有缺陷的，毕竟它是对象，会占用更多的内存，同时运行效率也没有普通指针高！

这些源文件在android-8.1/system/core/libutils下，有兴趣的可以自己看看源码，写得很精妙！

##### 构建
```
mkdir build
cd build
cmake ..
#或者
clang++ -Iinclude -o main main.cpp RefBase.cpp
```

