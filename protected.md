# Protected
<div dir="rtl">
Protected تعتبر من Access modifers وحيث تقوم بتعريف امكانية الوصول للدالة او المتغيرات. بالنسبة  ل Proteced وهيا تقوم بجعل الوصول لدالتها و متغيراتها  سهل من داخل ال  NameSpace فقط  و تكون معروفة في مكان انشائها يمكن استخدامها من الخارج عن طريق بعض الدوال.
يمكن الوصول لمعلوماتها عن طريق class و drived class من الكلاس الي سوانا منه derived.
 </div>

	#Using Protected on variable:
	class  A {
	 protected  int x = 123;
	  } 
	  class  B : A {
	   static void Main() {
	    var a = new A(); 
	    var b = new B();
	     // Error CS1540, because x can only be accessed by
	       // classes derived from A. 
	        // a.x = 10; 
	         
	        // OK, because this class derives from A.
	         b.x = 10; } }
	
