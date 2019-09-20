# hello-world
using System;
namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args)
        {
               int i = 1, j ;
               Console.WriteLine("输出初始i的值：{0}", i);
               j=i++;            
               Console.WriteLine("执行后加运算后，输出i的值为：{0}", i);
               Console.WriteLine("输出j的值：{0}", j );
               j = ++i;          
               Console.WriteLine("执行前加运算后，输出i的值为：{0}", i);
               Console.WriteLine("输出j的值：{0}", j);
               Console.Read();

        }
    }
}
