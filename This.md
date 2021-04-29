# This
<div dir="rtl">
تشير الى المتغير الحالي من الدالة , تساعد في انشاء متغيرات خاصة لكي لا يتم الخلط فيما بين المتغيرات و هيا ايضا تساعد في تغير متغيرات الدالة التي يتم اخذ منها معلومات  </div>

	#This:
	public  class  Employee {
	 private  string  alias; 
	 private  string name;
	  public Employee(string name, string alias) { 
	  // Use this to qualify the members of the class 
	   // instead of the constructor parameters.  
	   this.name = name; 
	   this.alias = alias; 
	   } }

Ref:
https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/this
