# delegate

<div dir="rtl"> فائدتها انها تساعدك على استخدام كثير من الدوال في دالة واحد وهياdelegat بشرط ان يكون المدخلات و المخرجات نفس الشيء في الدوال الثانية
	</div>
>for example:

	public static int sum(int a, int b) { return a + b; }
            public static int sub(int a, int b) { return a - b; }
            public static int mul(int a, int b) { return a * b; }
            public static int div(int a, int b) { return a / b; }
            public static int mod(int a, int b) { return a % b; }
            public delegate int MyAction(int a, int b);
             static void Main(string[] args)
            { 
            MyAction[] operations =
                {
                mul,div,sum,sub,mod
            };
                int r = 0;
                foreach (var operation in operations)
                {
                    r += operation(5, 6);
                }
                }
