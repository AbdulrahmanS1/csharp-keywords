
# Abstract
<div dir= "rtl"> اي class يتم اضافة عليه كلمة abstract يتم اجبار الأبناء بإعادة كتاب ما تم كتابة عليه abstract في حالة ما كان مدخل او دالة, لجعل الأبناء في وضع التعديل الكامل و الخاص على الدالة و المدخل و مما يؤدي للالتزام الكامل ب OOP 
	</div>
	
>for example:

	abstract class Animal
	  {
	      public abstract void animalSound();
	      }
	    public void sleep()
	    {
	      Console.WriteLine("Zzz");
	    }
	  }
	    class Cat: Animal
	  {
	    public override void animalSound()
	    {
	       Console.WriteLine("Meow");
	    }
	  }
    

      
   

  
  
  



