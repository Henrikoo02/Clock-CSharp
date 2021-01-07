using System;
using System.Threading;
using System.Threading.Tasks;
using System.Collections.Generic;
using System.Text;
namespace Clocktestagain
{
    class Program
    {
        static void Main(string[] args)
        {
        a:
            Console.Clear();
            Console.WriteLine(DateTime.Now.ToString());
            Task.Delay(1000).Wait();
            goto a;
        }
    }
}
