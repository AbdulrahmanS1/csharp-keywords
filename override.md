# Override
<div dir="rtl">
يتم استخدام Override عندما يتم inhertance او abstract او عند استخدام virttual لإعادة صياغة دالة ما او مدخل  ويتم استعمالها بكثرة عندما يكون في ترابط بين الكلاسات 
 </div>

	#Class over-ride:
	abstract  class  Shape {
	 public abstract int GetArea(); 
	 } 
	 class  Square : Shape
	  { int side; public Square(int n) => side = n; 
	  // GetArea method is required to avoid a compile-time error.
	    public override int GetArea() => side * side;
	 -------------------------------------------------------------
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
	
