# Params
<div dir="rtl">
من اسمها لها دخل في ال Parameter  ,يتم استخدامها في بداية الدالة  اذا لم اكن متأكد من عدد المدخلات  ومني عارف كم حيجيني . تسخدم على الدوال ولازم المدخلات تكون من نفس النوع.

1. I need to identify the type : string , int , double , bool , etc ...
2. it should be used in array [ ] or list []
 </div>

	#Params example:
	Paramas int[]
	
	#Another full Example:
	public  class  MyClass { 
	public static void UseParams(params int[] list) {
	 for (int i = 0; i < list.Length; i++)
	  { 
	  Console.Write(list[i] + " "); 
	  } 
	  Console.WriteLine(); 
	  } 
	  public static void UseParams2(params object[] list) {
	   for (int i = 0; i < list.Length; i++) 
	   { 
	   Console.Write(list[i] + " "); 
	   } 
	   Console.WriteLine(); }


Ref:
https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/params
