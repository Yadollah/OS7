### &emsp; &emsp; به نام خدا ###
### &emsp; یدالله حبیب کاظمی ###
### تمرین 7 آزمایشگاه سیستم های عامل ###
<br>

__توضیح دهید ln سوال 1 : تفاوت بین لینک سخت و لینک سمبولیک را در دستور__

لینک سخت ورودی است که به محل فیزیکی یک فایل اشاره دارد 

در حقیقت ما تنها یک فایل داریم ، اما ورودی ۲ یا بیشتر دایرکتوری به محل فیزیکی آن بر روی دیسک سخت اشاره دارند

برای مثال با دستور زیر ما یک لینک سخت میسازیم

`ln test.sh test1.sh`

لینک های سمبولیک بسیار شبیه به شورتکات ها در ویندوز هستند ، که برخلاف لینک های سخت 

آدرس سخت افزاری خودشان را دارند و تنها یک فایل هستند که به یک فایل دیگر اشاره می کنند

برای مثال با دستور زیر یک لینک سمبولیک (نرم) میسازیم

`ln -s test.sh test2.sh`
<br><br>

__استفاده کنیم چه مزیتی دارد -r سوال 2 : اگر در این دستور از آرگومان__

برای استفاده از این دستور حتما باید از دستور سمبولیک استفاده شود

که بصورت زیر میشود

`ln -s -r` Or `ln -sr`

این دستور سمبولیک لینک را وابسته به مکان لینک میسازد 
<br><br>

__را توضیح دهید ln سوال 3 : سه مورد از گزینه های دستور__

ln -s :

بجای لینک های سخت ، لینک های سمبولیک میسازد

ln -P :

لینک های سخت را مستقیما در لینک های سمبولیک میسازد

ln -i :

می پرسد که آیا لینک جدید را جایگزین لینکی که وجود دارد بکند یا نه
<br><br>

__دستور زیر را بررسی نمایید whatis سوال 4 : با کمک دستور__

chmod :

"تغییر حالت بایت های یک فایل"

برای ایجاد دسترسی ها به هر فایل 9 بیت اضافه میشود ، این 

دستور برای مدیریت دسترسی فایل ها و دایرکتوری ها کاربرد دارد
