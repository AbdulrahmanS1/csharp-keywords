
# Abstract
The `abstract` modifier indicates that the thing being modified has a missing or incomplete implementation.
its an object orianted featuer that enforce the childern to override it methods, so everyone of them has his own signature on the method
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
    

      
   

  
  
  



