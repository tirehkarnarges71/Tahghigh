
# 1-شرط ها (Conditions)
<div dir="rtl" align="Right">
If: برای برسی یک شرط استفاده می شود،اگر شرط درست باشد،کد داخل آن اجرا می شود.


Int age =20;

If age (age>=18)

{

Console.writeLine(“Adult”);

}
<div dir="rtl" align="Right">
Else if:وقتی می خواهیم چند شرط مختلف را بررسی کنیم.

Int score=15;

If (score >=10)

{

Console.WriteLine(“Excellent”);

}

Else if (score>=10)

{

Console.WriteLine(“Pass”);

}

Else

{

Console.WriteLine(“Fail”);

}
<div dir="rtl" align="Right">
Switch: برای انتخاب یک حالت مختلف استفاده می شود.

Int day=2;

Switch (day)

{

Case 1:

Console.writeLine(“Saturday”);

Break;

Case 2:

Console.WriteLine(“Sunday”);

Break;

Default:

Console.WritLine(“Unknown”);

Break;

}
<div dir="rtl" align="Right">
2-حلقه ها (Loop):

حلقه ها برای اجرای مکرر یک دستور استفاده می شود.

For:

زمانی مناسب است که تعداد تکرارها مشخص باشد.

For (int i=1; i<=5; i++)

{

Console.WriteLine(i)

}
<div dir="rtl" align="Right">
Foreach:برای پیمایش عناصر یک مجموعه مثل آرایه یا لیست استفاده می شود.

Int[] number={10,20.30};

Foreach (int number in numbers)

{

Console.WriteLine(number);

}

در هر تکرار یک عنصر از مجموعه دریافت می شود.

While

تا زمانی که شرط درست باشد حلقه اجرا می شود، ممکن است اصلا اجرا نشود .

Int i=1;

While (i<=5)

{

While(i<=5)

{

Console.WriteLine(i);

I++;

}
<div dir="rtl" align="Right">
Do While: ابتدا دستورات اجرا می شوند و سپس شرط بررسی می شود.
بنابراین حداقل یک بار اجرا خواهد شد.

Int i=1;

Do

{

Console.WriteLine(i);

I++;

}

While (i<=5);

3-دستور Break:

برای خروج فوری از حلقه یا پایان دادن به اجرای یک بخش از switch استفاده می شود.

For (int i=1 ; i,=10; i++)

{

If (i==5)

{

Breal;

}

Consol.writeLine(i);

}


