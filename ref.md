# ref
<div dir="rtl">
تساعد في نقل المعلومات عن الطريق التاشير على المتغير. تسخدم في امكان كثير ومنها الدوال لتساعد في نقل معلومات الدلة للدالة الأساسية لجراء تشغيل البرنامج
 </div>

	void Method(ref int refArgument) 
	{ refArgument = refArgument + 44; } 
	int number = 1; Method(ref number); 
	Console.WriteLine(number);
