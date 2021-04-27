
# in
<div dir="rtl">
تساعد في نقل المعلومات عن الطريق التاشير على المتغير, تقوم بالتأكيد ان قيمة المتغير لا يمكن تغيرها عند نقلها خارج الدالة وهذا الي يفرق عن ref. تسخدم في امكان كثير ومنها الدوال لتساعد في نقل معلومات الدلة للدالة الأساسية لجراء تشغيل البرنامج
 </div>

	int readonlyArgument = 44;
	 InArgExample(readonlyArgument); 
	 Console.WriteLine(readonlyArgument); 	
	  InArgExample(in int number) { 
	  }
