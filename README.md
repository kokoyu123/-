# -
C语言学习
//包含一个叫stdio.h的文件
//std-标准 standard input output
//#include <stdio.h>
//int main()//主函数-程序的入口-main函数有且仅有一个
//{






	//printf("hello world\n");
   // return 0;
//}
//int 是整型的意思
//main前面的int表示main函数调用返回一个整型

////int main()
//{
    //这里完成任务
	//在屏幕上输出hello world
	//函数-print function-printf-打印函数
	//库函数-C语言本身提供的函数
	//别人的东西-打招呼
	//#include
	//printf("hehe\n");
    //return 0;//返回0   
//}

//char-字符类型
//#include <stdio.h>
//int a = 100;
//int num2 = 20;//全局变量定义在代码块（{}）之外的变量
//int main()
//{   
	//int a = 10;
	//局部变量和全局变量的名字建议不要相同-容易误会，产生bug
	//当局部变量和全局变量名字相同时，局部变量优先
	//printf("%d\n",a);
	//int num1 = 10;//局部变量定义在代码块（{}）内部的变量
	//年龄
	//short age =20;//向内存申请2byte=16bit用来盛放20
    //float weigh=95.6f;//向内存申请4bytte存放小数
	//char ch = 'A';//内存
	//%d-打印整型
	//%c-打印字符
	//%f-打印浮点数字-打小数
	//%p-以地址的形式打印
	//%x-打印16进制数字
	//%o...
	//printf("%c\n",ch);//%c--打印字符格式的数据
	//short int-短整型
	//int-整型
	//int age = 20;
	//printf("%d\n",age);//--打印整型十进制数据
	//long-
	//long num = 100;
    //double d = 3.14;

	//printf("%lf\n",d);
    // printf("%d\n",sizeof(char));//1
	// printf("%d\n",sizeof(short));//2
	 //printf("%d\n",sizeof(int));//4
	 //printf("%d\n",sizeof(long));//4
	// printf("%d\n",sizeof(long long));//8
	// printf("%d\n",sizeof(float));//4
	// printf("%d\n",sizeof(double));//8
	
	 //int age =20;(int32bit可表示的数字范围非常大，有些浪费，故用shortage比较合理)
	 //short age =20;(2byte=16bit 最大数字2^16-1=65555)
	//return 0;


//}
#include <stdio.h>

//int main()\
//{
//	{
//	int a = 10;
//    printf("a = %d\n",a);//ok
//	} 
//	printf("a = %d\n",a);//error
//
//    return 0;
//}
//int main()
//{
//
//	//未声明的标识符
//	//声明extern外部符号的
//	extern int g_val;
//	printf("g_val = %d\n",g_val);
//    return 0;
//}
// int global = 2020;
// void test()
//{
//
//
//	printf("test()-- %d\n",global);
// }
// int main()
// {
//    test();
//	printf("%d\n",global);
//    return 0;
//}
//{
//
//
//	//局部变量的作用域
//
//	{
//		int num = 0;
//		printf("num = %d\n",num);
//	}
//	
//    return 0;
//
//}
//
////int main()
////{

	//计算两个数的和
	//int num1 = 0;
	//int num2 = 0;
	//int sum = 0;
	//输入数据-使用输入函数scanf
	//scanf("%d%d",&num1,&num2);
	
	//C语言语法规定，变量要定义在当前代码块的最前面
	//sum = num1 + num2;
	//printf("sum=%d\n",sum);
        //return 0;
//}
