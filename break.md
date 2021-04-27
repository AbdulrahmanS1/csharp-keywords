
# break
<div dir="rtl">
تساعدك للخروج من loop و تقوم  باخراجك الى الدالة التالية. </div>

	class  BreakTest { 
	static void Main() {
	 for (int i = 1; i <= 100; i++) { 
	 if (i == 5) { 
	 break; 
	 } 
	 Console.WriteLine(i); 
	 } 
	 Console.WriteLine("Press any key to exit.");
	  Console.ReadKey(); } }
