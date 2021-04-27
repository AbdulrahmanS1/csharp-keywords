
# base
<div dir="rtl"T> تساعد في نسهيل استنساخ دوال او مدخلات الاب للابناء و تسهل عميلة object orianted programing .
	</div>
>for example:
	
	public  class  BaseClass { 
	int num; 
	public BaseClass() {
	Console.WriteLine("in BaseClass()"); 
	 } 
	 public BaseClass(int i)
	  { 
	  num = i;
	  Console.WriteLine("in BaseClass(int i)");
	    } 
	    public int GetNum() { return num; } 
	    }
	     public  class  DerivedClass : BaseClass {
	     // This constructor will call BaseClass.BaseClass()  
	      public DerivedClass() : base() { }
	       // This constructor will call BaseClass.BaseClass(int i)  
	       public DerivedClass(int i) : base(i) { }
