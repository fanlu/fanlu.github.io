 [gcc编译C++程序](http://blog.csdn.net/shanxiao528/article/details/5578743)
 
 
```
g++ -c hellospeak.cpp -o hspk1.o
g++ hellospeak.cpp speak.cpp -o hellospeak
```

 [C++ 对象和实例的区别，以及用new和不用new创建类对象区别 ](http://blog.csdn.net/tham_/article/details/44906571)
 
 传参 
 ```
 std::string a(std::string& p){
    cout << p << endl;
    p = "chage it";
    return p;
}

std::string cc = "555";
a(cc);
cout << cc << endl;

输出：chage it
 ```
