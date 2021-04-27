# Continue
<div dir="rtl">
تساعدك للخروج من loop و الانتقال الى الخطوة الثانية من الدالة. </div>

	class  ContinueTest {
	 static void Main() {
	  for (int i = 1; i <= 10; i++)
	   {
	    if (i < 9) {
	     continue; 
	     } 
	     Console.WriteLine(i); 
	     } 
	      Console.WriteLine("Press any key to exit."); 
	      Console.ReadKey(); } }
