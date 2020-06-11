# TypeGettingLanguage
《编译原理》小练习

语法：

![tbXXU1.jpg](https://s1.ax1x.com/2020/06/11/tbXXU1.jpg)

示例程序：
```cpp
{
	int x;
	char y;
	{
		y;
		bool y;
		x;
		y;
	}
	y;
}
```
输出结果：
```cpp
{
	{
		y: char;
		x: int;
		y: bool;
	}
	y: char;
}
```
