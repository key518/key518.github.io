#废话和准备 

~~来自一位不争气的蒟蒻~~

******

## 谈谈C++

`不得不说C++很优秀功能和全面，这也是我所接触到底第一种语言， 听说你们的信息技术会直接学习 python ，那么废话不多说我们直接开始C++的 ` ~~成仙之路~~

*****

## 了解C++

>~~以下内容全是抄的~~没有什么意义，建议跳过

>可以忽略不计

1. C++是从C语言发展而来的，而C语言的历史可以追溯到1969年。 在1969年，美国贝尔实验室的Ken Thompson为DECPDP-7计算机设计了一个操作系统软件，这就是最早的UNIX。接着，他又根据剑桥大学的Martin Richards设计的BCPL语言为UNIX设计了一种便于编写系统软件的语言，命名为B。

2.    B语言是一种无类型的语言，直接对机器字操作，这一点和后来的C语言有很大不同。作为系统软件编程语言的第一个应用，Ken  Thompson使用B语言重写了其自身的解释程序。                    1972—1973年间，同在贝尔实验室的Denis Ritchie改造了B语言，为其添加了数据类型的概念，并将原来的解释程序改写为可以在直接生成机器代码的编译程序，然后将其命名为C。

3. 1973年，Ken  Thompson小组在PDP-11机上用C重新改写了UNIX的内核。与此同时，C语言的编译程序也被移植到IBM 360/370、Honeywell 11以时VAX-11/780等多种计算机上，迅速成为应用最广泛的系统程序设计语言。 然而，C语言也存在一些缺陷，例如类型检查机制相对较弱、缺少支持代码重用的语言结构等，造成用C语言开发大程序比较困难。     

  4. 为了克服C语言存在的缺点，贝乐实验室的Bjarne Stroustrup博士及其同事开始对C语言进行改进和扩充，将“类”的概念引入了C语言，构成了最早的C++语言（1983）。后来，Stroustrup和他的同事们又为C++引进了运算符重载、引用、虚函数等许多特性，并使之更加精炼，于1989后推出了AT&T C++ 2.0版。随后美国国家标准化协会ANSI(American National Standard Instiute)和国际标准化组织ISO(International Standards Organization)一起进行了标准化工作，并于1998年正式发布了C++语言的国际标准ISO/IEC:98-14882。各软件商推出的C++编译器都支持该标准，并有不同程序的拓展。         

  5. C++支持面向对象的程序设计方法，特别适合于中型和大型的软件开发项目，从开发时间、费用到软件的重用性、可扩充性、可维护性和可靠性等方面，C++均具有很大的优越性。同时，C++又是C语言的一个超集，这就使得许多C代码不经修改就可被C++编译通过。

*****

##  准备工作

必须要做的

- 编译器：

>（PC）[Dev-C++](http://down10.zol.com.cn/bianchengtools/DevCpp.5.10.TDM.exe)   

>（PE）[C++编译器](https://pan.baidu.com/s/1Yc2AWOdLpkeujeVpIN1LMw)  提取码：s8ic

>[在线编译器](https://www.runoob.com/try/runcode.php?filename=helloworld&type=cpp)

- 测试平台：

> （必须注册！！！）[洛谷](https://www.luogu.org/)               

> (同上)[教材同步测评](http://ybt.ssoier.cn:8088/)

- 书籍资料：

> [信息学奥赛一本通（C++版）](https://detail.m.tmall.com/item.htm?id=571738858361&abtest=28&rn=4a4bec791362d5bba69b89a5082b40f6&sid=4ed0ba758b312c452b28bb8e771df97d)（可以只买两本但是建议三本买全）                         

>[计算机基础知识](https://pan.baidu.com/s/1VkyS9t5yuuVthKIutTzQnw )  提取码: tzej

>[自学网站](https://www.runoob.com/cplusplus/cpp-tutorial.html)

> [算法竞赛入门](https://pan.baidu.com/s/1I9cCnLEWJaaKKyK9PWB7gQ) 提取码：tj30 

>[C语言解惑](https://pan.baidu.com/s/1m-bLjTwQQVbziOqb21G4sw ) 提取码: x1zx

> 所有关于C++的文件：[文件](https://pan.baidu.com/s/1VsvncHgAp9EDbIIQkEMPiw ) 提取码: 4pvr

>闲书（关于信息技术）：[闲书](https://pan.baidu.com/s/1LJh2G5ursY5wz2Hx6Uo4Pg ) 提取码: dv5w

#### 看一个入门程序？
```
#include<iostream>  
  //头文件申明 ，预处理
 
using   namespace std;//命名空间 
 
int main()//主函数

{
	cout<<"你好，简书"<<endl;//输出内容 
      //也可以写成：cout<<"你好，简书\n";
        return 0; //程序结束 
}
```

*****

