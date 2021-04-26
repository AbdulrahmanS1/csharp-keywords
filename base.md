
# base
The  `base`  keyword is used to access members of the base class from within a derived class:

-   Call a method on the base class that has been overridden by another method.
    
-   Specify which base-class constructor should be called when creating instances of the derived class.
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
