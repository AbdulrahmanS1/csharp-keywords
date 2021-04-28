# Virtual
<div dir="rtl">
يتم استخدام virtual  عندما نريد ان نعيد صياغة الدالة او المدخلات  في مكان اخر بطريقة أخرى
 </div>

	#Class over-ride:
	public virtual double Area() {
	 return x * y; 
	 }
	 	-----------------------------------------------------------	

	 Full example:
	 class  MyBaseClass
	 public  virtual  string Name { get; set; }
	  // ordinary virtual property with backing field
	    private  int num; 
	    public  virtual  int Number { 
	    get { return num; } 
	    set { num = value; }
	     }
	     class  MyDerivedClass : MyBaseClass { 
	     private  string name; 
	     // Override auto-implemented property with ordinary property 
	      // to provide specialized accessor behavior. 
	       public  override  string Name {
	        get { return name; } 
	        set { if (!string.IsNullOrEmpty(value)) { 
	        name = value; } 
	        else { name = "Unknown"; } 
	        }
	 	-----------------------------------------------------------	
	#Variable over-ride
	public  virtual  int Number;
