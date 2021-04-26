
# as
The `as` operator explicitly converts the result of an expression to a given reference or nullable value type. If the conversion is not possible, the `as` operator returns `null`. Unlike a [cast expression](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/type-testing-and-cast#cast-expression), the `as` operator never throws an exception.
>for example:

	IEnumerable<int> numbers = new[] { 10, 20, 30 }; 
	IList<int> indexable = numbers as IList<int>; 
	if (indexable != null) { Console.WriteLine(indexable[0] + indexable[indexable.Count - 1]); // output: 40 }
