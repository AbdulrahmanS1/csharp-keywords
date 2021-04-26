



# Class
A type that is defined as a [class](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/class) is a _reference type_. At run time, when you declare a variable of a reference type, the variable contains the value [null](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/null) until you explicitly create an instance of the class by using the [new](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/new-operator) operator, or assign it an object of a compatible type.
It helps the programer to easily to manipulate the data and do the oop.
>for example:
	
	class Car 
	{
	  string color = "red";
	  static void Main(string[] args)
	  {
	    Car myObj = new Car();
	    Console.WriteLine(myObj.color);
	  }
	}

    

      
   

  
  
  



