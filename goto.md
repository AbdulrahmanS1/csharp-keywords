


# goto
<div dir=rtl>تساعدك على تخطي الدالة الحالية و الرجوع الى مكان معين و في اغلب الأحيان تكون غير مفيدة لانها سوف تدخلك في loop .
</div>
>for example:

	 public static void isSeven(string seven)
	        {
	        hi:
	 Console.WriteLine("Write till you put number 7 in the string");
	            seven = Console.ReadLine();

            if (!seven.Contains('7'))
                goto hi;
        }
           
