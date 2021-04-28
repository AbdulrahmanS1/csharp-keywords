# Public
<div dir="rtl">
Public تعتبر من Access modifers وحيث تقوم بتعريف امكانية الوصول للدالة او المتغيرات. بالنسبة  ل Public وهيا تقوم بجعل الوصول لدالتها و متغيراتها  سهل من داخل ال  NameSpace و تكون معروفة في مكان انشائها يمكن استخدامها من الخارج عن طريق بعض الدوال.
يمكن الوصول لاي دالة او متغير يحتوي كلمة public من اي مكان بدون اي مشاكل.
 </div>

	#Using Public on variable:
	
	class  SampleClass { 
	public  int x; 
	// No access restrictions. }
	---------------------------------------------------------
	Full example :
	
	class  PointTest {
	 public  int x;
	  public  int y;
	   } 
	   class  Program {
	    static void Main() {
	     var p = new PointTest(); 
	     // Direct access to public members.
	      p.x = 10; 
	      p.y = 15; 
	      Console.WriteLine($"x = {p.x}, y = {p.y}"); } }
	       // Output: x = 10, y = 15
	
