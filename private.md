# Private
<div dir="rtl">
private تعتبر من Access modifers وحيث تقوم بتعريف امكانية الوصول للدالة او المتغيرات. بالنسبة  ل private  وهيا تقوم بجعل الوصول لدالتها و متغيراتها  صعب من الخارج و تكون معروفة فقط في مكان انشائها يمكن استخدامها من الخارج عن طريق بعض الدوال لكن لا يمكن التغير على قيمة الدالة الأصلية
 </div>

	#Using Private on variable:
	class  Employee { 
	private  int i; 
	double d; 
	// private access by default }
	 -------------------------------------------------------------
	 Full example:
	class  Employee2 { 
	private  string name = "FirstName,
	 LastName"; private  
	 double salary = 100.0; 
	 public string GetName() {
	  return name; }
	   public  double Salary { 
	   get { return salary; } } }
	    class  PrivateTest { 
	    static void Main() {
	     var e = new Employee2();
	      // The data members are inaccessible (private), so 
	       // they can't be accessed like this:  
	       // string n = e.name; 
	        // double s = e.salary;  
	        // 'name' is indirectly accessed via method:  
	        string n = e.GetName(); 
	        // 'salary' is indirectly accessed via property  
	        double s = e.Salary; } }
	
