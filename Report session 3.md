
# Stack:


حافظه ای است برای مدیریت فراخوانی متدها، متغییرهای محلی و اطلاعات مربوط به اجرای برنامه استفاده می شود. هرمتد هنگام اجرا برنامه استفاده می شود. هرمتد هنگام اجرا فضای مربوط به خودش را دارد و با پایان اجرای فضای مربوط به خودش را دارد و با پایان اجرای آن، این فضا آزاد می شود.

# Heap:

حافظه ای است که معمولا اشیای ساخته شده با class  و آرایه ها در آن قرار می گیرند. مدیریت آزادسازی حافظه این اشیا عمدتا توسط Garbage Collector  انجام می شود.

### تفاوت Value Type و Reference Type

#### Value Type

نمونه ها: int,double,bool,struct

رفتار متغیر:

مقدار را نگه می دارد

هنگام کپی:

مقدار کپی می شود 

محل ذخیره سازی:

بسته به نوع استفاده ممکن است Stack یا Heap باشد 

#### Reference Type

نمونه ها:class,string,،آرایه 

رفتار متغیر:

ارجاع به ش را نگه می دارد

هنگام کپی:

ارجاع کپی می شود

محل ذخیره سازی :

شی معمولا در Heapاست خود ارجاع بسته به محل تعریف می تواند در Stack یا  Heap باشد 

#### مثال Value Type :

C#

Int a =10;

Int b= a;

b=20;

Console.WriteLine(a);//10

Console.WriteLine(b);//20

در این مثال int یک Value Type است وقتی a را در b کپی می کنیم مقدار آن کپی می شود بنابراین تغییر b روی a تاثیری ندارد.

#### مثال Reference Type:

C#

Class person

{

Public string Name =””;

}

Person p1 = new person();

P1.name= new person();

P1.Name = “Ali”;

Person p2 = p1;

P2.Name =”Reza “;

Console.WriteLine(p1.Name):// Reza

