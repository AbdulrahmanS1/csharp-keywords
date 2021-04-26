


# goto
Jumb statement .
Most of thr time will make the program go on infinte loop, to prevent this you need a counter.
>for example:

	 public static void isSeven(string seven)
	        {
	        hi:
	 Console.WriteLine("Write till you put number 7 in the string");
	            seven = Console.ReadLine();

            if (!seven.Contains('7'))
                goto hi;
        }
           
