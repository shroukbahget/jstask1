var vs let vs const

	
var vs let:
بعمل بيهم متغيرات ينفع اعدل عليهم بعد كدا 
Const :
بعمل بيهم ثوابت معرفش اغير قيمتهم بعد كدا 
Var :
يمكن للمتغيرات المعلنة تكون محلية او عالمية المحلية بتكون مخصصة للمتغيرات اللي داخل الدوال انما العاليمة بتكون مخصصة للمتغيرات اللي خارج الدوال 
نقدر كمان نعيد اعلان المتغيرات و نعدل عليها 
Let:
يمكن للمتغيرات المعلنة تكون محلية او عالمية او كتلة و الكتلة دي بتكون في  {}
 للعثور ع المتغيرات داخل الكتلة  باستخدام الكلمة الاساسيةlet  ممكن استخدم فيها  if , loop , switch  
لا يمكن الوصول للمتغيرت خارج الكتلة 
Const:
المتغيرات المعلنة باستخدام const تشبه let فيما يتعلق بالنطاق. يمكن أن يكون لهذه المتغيرات نطاق عالمي أو محلي أو كتلي

 

















































alert vs prompt vs confirm

alert : 
وظيفة تنبيه بيكون عبارة عن مربع حوار بسيط و فيه زرار "موافق" بيظهر لليوزر و بيتم استخدامه عشان يظهر معلومة او اشعار 
اليوزر مينفعش يتفاعل مع الصفحة او يعمل أي حاجة الا بعد م يدوس ع الزرار 
بتحتوي ع زرار واحد بس لخيار واحد و مش ممكن تجمع أي ادخال من اليوزر 

  Prompt:
 وظيفة مطالبة بيكون عبارة عن مربع حواريحتوي ع رسالة وفيه مكان  ادخال لليوزر  و زرارين "موافق و الغاء" يستخدموا لجمع الادخال 
بتاخد نوعين : اول نوع الرسالة اللي بتتعرض 
و التانية بتكون اختيارية و بتكون هي القيمة الافتراضية اللي بتتعرض 
بتعيد النص اللي اللي اليوزر دخله او تظهرله null لو داس ع زر " الغاء"

Confirm    :
وظيفة تأكيد مربع حوار يحتوي ع رسالة و زرارين " موافق و الغاء"
بتسخدم لطلب عملية تأكيد من اليوزر قبل اجراء معين و يمكن لليوزر اختيار التأكيد او الغاء الاجراء 
و بترجع قيمة منطقية  (  لو ضغط ع موافق true , false لو ضغط ع  إلغاء )
