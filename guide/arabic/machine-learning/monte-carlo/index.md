---
title: Monte Carlo
localeTitle: مونت كارلو
---
## مونتي كارلو

يعد Monte Carlo فئة من تقنيات المحاكاة تسمح لك باستكشاف المساحة الحل لمشكلة تحتوي على مدخلات يمكن أن تأخذ قيمًا متعددة. من خلال تشغيل عمليات المحاكاة باستخدام المدخلات العشوائية ومعلمات النموذج ، يمكنك مراقبة النتائج التي تنتج عن المدخلات التي قد تكون أخرى لم يتم اختبارها. هذه الطريقة مفيدة في حل المشكلات التي قد يصعب حلها بشكل تحليلي. إنها ليست طريقة دقيقة ، ولكنها طريقة تجريبية ، وعادة ما تستخدم العشوائية والإحصاء للحصول على نتيجة. تنتهي الخوارزمية بإجابة صحيحة مع الاحتمالية.

إنها عملية حسابية تستخدم أرقامًا عشوائية لإنتاج نتيجة (نتائج). بدلاً من وجود مدخلات ثابتة ، يتم تعيين توزيعات الاحتمال لبعض أو كل المدخلات. سيؤدي ذلك إلى إنشاء توزيع احتمالي للمخرجات بعد تشغيل المحاكاة.

على سبيل المثال ، يمكن استخدام خوارزمية Monte Carlo لتقدير قيمة π. يعتمد مقدار المساحة داخل دائرة نصف قطر نصف قطر 1 على قيمة π. يعتمد احتمال أن النقطة المختارة عشوائيًا في دائرة ربع الدائرة هذه على مساحة الدائرة. إذا تم وضع النقاط عشوائياً في مربع ذي جوانب طول 1 ، فإن النسبة المئوية للنقاط التي تقع ضمن دائرة نصف قطر نصف قطرها 1 تعتمد على قيمة π. تضع خوارزمية مونت كارلو عشوائيا النقاط في المربع وتستخدم النسبة المئوية للنقاط التي تقع داخل الدائرة لتقدير قيمة Th.وهذه طريقة فعالة لصنع التقريب.

في أنظمة الاتصالات الحديثة ، يتم تحديد جودة تبادل المعلومات من خلال وجود ضوضاء في القناة. المصدر الرئيسي للضوضاء - يمكن وصف خاصية الضوضاء الغوسية البيضاء المضافة (AWGN) بطبيعتها باستخدام خوارزمية مونت كارلو في محاكاة نظام الاتصالات.

### معلومات اكثر:

*   [ويكيبيديا](https://en.wikipedia.org/wiki/Monte_Carlo_method)
*   [ولفرام ماثوورلد](http://mathworld.wolfram.com/MonteCarloMethod.html)
*   [مقالة Minitab - مونتي كارلو ليست صعبة كما تظن](http://blog.minitab.com/blog/understanding-statistics/monte-carlo-is-not-as-difficult-as-you-think)
*   [خوارزمية مونتي كارلو (4:41)](https://www.youtube.com/watch?v=Q2-FH36LuT0)