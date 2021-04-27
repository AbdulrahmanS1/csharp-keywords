# Out

<div dir="rtl">
معلومات الدلة للدالة الأساسية لجراء تشغيل البرنامج ,و غالبا ما تسخدم 	عند ارجاع عدة معلومات و لاتنقل الخاصية الى مستدعيها. </div>

	example:
	 using System;
	 class GFG {
			static public void Main()
			{
			int  i;
			Addition( out i);
			Console.WriteLine("The addition of the value is: {0}", i);
			}
			public static void Addition( out int i)
			{
			i = 30;
			i += i;
			}
			}
