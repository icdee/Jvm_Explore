# 商汤科技

简单的表达式计算(CalculateWithMixedFormatNumber)

时间限制：C/C++语言 1000MS；其他语言 3000MS

内存限制：C/C++语言 65536KB；其他语言 589824KB

题目描述：

给你一个合法的算术表达式，只包含整数和加号，减号。但整数不一定都是十进制的数，可能是八进制，十六进制，规定包含前缀0x的是十六进制，包含前缀0的是八进制，其他情况是十进制。现在你能计算出这个式子最终的值吗？

输入的表达式式子只会是 整数 +(-) 整数 +(-) 整数 …… +(-) 整数

保证给定的整数不会超过6位（包括前缀0或者前缀0x）

输入

输入有且只有一行，是一个字符串，保证是合法的表达式式子

输出

输出仅一行，表示最终的运算结果，要求以10进制的格式输出答案


样例输入

027555+692-0xD32C

样例输出

-41227

Hint

样例的是（27555）<8-base> + 682<10-base> - D32C<16-base>，最终答案是-41227

