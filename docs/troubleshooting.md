<div dir="rtl">

# المشاكل والحلول

كل مشكلة واجهتنا أثناء طلب D-U-N-S وتسجيل Google Play و Apple، وسببها وحلها. التفاصيل في المرجع المذكور في كل سطر.

| المشكلة | السبب | الحل | المرجع |
|---|---|---|---|
| بحث D&B يعرض *No Match found for the given input criteria* | الشركة ليس لها رقم D-U-N-S سابق | ليست مشكلة. اضغط رابط *click here to submit a request to create a new D-U-N-S* | [2](02-dnb-new-duns.md#الشاشة-4-البحث-عن-الشركة-d-u-n-s-search) |
| خطر رفض Apple: *could not be verified as a legal entity* | ملف D&B بدون نوع كيان، أو الشركة مسجّلة كمؤسسة فردية. صفة «شخص واحد» في السجل قد تُفهم خطأً | Legal Structure = Corporation، و CEO Title = Chairman، وعدد الموظفين الفعلي، وملاحظة صريحة، وإرفاق السجل الإنجليزي. النتيجة: Legal Status = Corporation ✅ | [1](01-documents-and-legal-entity.md#لماذا-يهم-نوع-الكيان) |
| D&B سجّلت المنطقة Ash Sharqiyah بدل Al Qassim، مرتين | اخترنا Al Qassim في الطلبين. الأرجح أن نظام D&B يحدد المنطقة تلقائياً من العنوان | الرد على بريد «DUNS Number Update Completed» بطلب تصحيحها يدوياً مع إثبات العنوان الوطني. لا يؤثر على Google، لكنه يؤثر على Apple | [3](03-dnb-update-duns.md#الرد-على-dnb-لتصحيح-المنطقة) |
| اسم الرئيس فارغ في ملف D&B بعد الطلب الأول | D&B لم تسجّله رغم إرساله في نموذج الإنشاء | طلب تحديث بعلامة على CEO / Owner / Principal Name و Title. أُضيف في التحديث ✅ | [3](03-dnb-update-duns.md#ما-طلبناه) |
| الموقع والإيميل لا يظهران في ملف D&B | نموذج التحديث ليس فيه خانات لهما، وبريد الإتمام لا يعرضهما | طلبناهما في الملاحظة، ونطلب من D&B تأكيدهما في الرد. Google و Apple يتحققان من الإيميل بنفسيهما، فلا يمنع التسجيل | [3](03-dnb-update-duns.md#النتيجة) |
| عبارة حمراء في بوابة D&B: *Your request has not met or exceeded the Expected Response date* | تظهر مع كل طلب لم يصل تاريخ رده المتوقع | ليست مشكلة. انتظر البريد، ولا تفتح طلباً ثانياً | [3](03-dnb-update-duns.md#متابعة-الحالة) |
| الموقع `tmkeen.com.sa` لا يفتح | النطاق بدون سجل A في DNS، و `www` غير موجود. الإيميل يعمل لأن سجل MX على Google | ربط النطاق بخادم وتشغيل صفحة بسيطة. شرط لـ Apple، والأسلم لـ Google | [6](06-apple-developer.md#الشروط-قبل-التسجيل) |
| Google: *We couldn't verify it's you* عند تفعيل التحقق بخطوتين | Google لم يتعرف على الجهاز أو الشبكة، والحساب جديد | من لوحة Workspace: المستخدم ← الأمان ← اختبار التحقق من تسجيل الدخول ← إيقاف 10 دقائق، ثم التفعيل فوراً | [4](04-google-workspace-2sv.md#المشكلة-الأولى-we-couldnt-verify-its-you) |
| Authenticator: الرمز صحيح لكن Google يقول خطأ | وقت الجوال غير مضبوط، أو السطر من رمز QR قديم، أو انتهت مدة الرمز | ضبط الوقت تلقائياً، وحذف الأسطر القديمة من التطبيق، ومسح QR الجديد، وإدخال الرمز فوراً. أو استخدام SMS بدلاً منه | [4](04-google-workspace-2sv.md#المشكلة-الثانية-authenticator-يقول-إن-الرمز-خطأ) |
| Play Console ما زال يطلب تفعيل التحقق بخطوتين بعد إضافة الوسائل | الوسائل أُضيفت لكن الميزة نفسها لم تُفعَّل | الضغط على الزر الأزرق **تفعيل ميزة "التحقق بخطوتين"** في أسفل صفحة الإعداد، ثم تحديث Play Console | [4](04-google-workspace-2sv.md#المشكلة-الثالثة-play-console-ما-زال-يطلب-التفعيل) |
| ملف الدفع الموجود يعرض *A D-U-N-S number is required* ولا يطابق D&B | الملف أُنشئ لفواتير Workspace باسم `tmkeen.com.sa` وعنوان مكتوب بصيغة مختلفة | **Create new payments profile** وإدخال رقم D-U-N-S، فيجلب Google الاسم والعنوان من D&B | [5](05-google-play-console.md#الخطوة-5-ملف-الدفع-payments-profile) |
| إعادة التسجيل في Play Console تعرض ثلاثة ملفات دفع، والمحدد افتراضياً `tmkeen.com.sa` | الملف الذي أُنشئ ببيانات D&B محفوظ في حساب Google | اختر **MADAR ALTAMKEEN COMPANY** (فيه D-U-N-S 986473058)، وليس `tmkeen.com.sa` ولا Create new | [5](05-google-play-console.md#الخطوة-11-الشروط-والدفع-terms) |
| الدفع مرفوض: *Unable to complete transaction: prepaid cards can't be used [OR_CCR_61]* | Google لا يقبل البطاقات المسبقة الدفع لرسوم التسجيل | بطاقة بنكية عادية: Credit، أو Debit/مدى مرتبطة بحساب بنكي وعليها Visa أو Mastercard. بطاقات المحافظ الرقمية غالباً Prepaid | [5](05-google-play-console.md#الخطوة-11-الشروط-والدفع-terms) |
| مركز الدفع يعرض «لا تتوفّر أيّ أنشطة» | الملف المختار أعلى الصفحة `tmkeen.com.sa`، والدفع تم على ملف آخر | من السهم ▼ اختر **MADAR ALTAMKEEN COMPANY** | [5](05-google-play-console.md#إيصال-الرسوم) |
| إيصال الرسوم لا يصل بالبريد، و Ctrl + P يطبع قائمة النشاط فقط بدون التفاصيل | التفاصيل في لوحة جانبية لا يطبعها المتصفح | لقطتا شاشة للوحة كاملة جُمعتا في `documents/Google-Play-Registration-Receipt.pdf` | [5](05-google-play-console.md#إيصال-الرسوم) |
| Apple: *Your account cannot be created at this time* | رفض عام: الرقم مربوط بحسابات كثيرة، أو محاولات كثيرة، أو VPN أو إضافات المتصفح | Call me، أو رقم آخر، أو التوقف يوماً، أو تطبيق Apple Developer على iPhone. **تبيّن لاحقاً أن الحساب أُنشئ**، فلا تنشئ غيره | [6](06-apple-developer.md#مشاكل-إنشاء-الحساب-2026-11-22) |
| Apple: رمز SMS لا يصل إلى `+966560509111` | غالباً Apple أوقفت الطلب قبل الإرسال، فالشاشة لا تعرض الرقم | Call me، أو Use a different phone number ثم إضافة رقم الشركة كرقم موثوق ثانٍ | [6](06-apple-developer.md#مشاكل-إنشاء-الحساب-2026-11-22) |
| Apple: رمز الإيميل كُتب في شاشة **Verify phone number** | الرمزان يصلان في وقت متقارب | شاشة Verify phone number تطلب رمز SMS. رمز الإيميل يصل في بريد «Verify your Apple Account email address» | [6](06-apple-developer.md#مشاكل-إنشاء-الحساب-2026-11-22) |
| `git push` مرفوض أثناء توثيق الريبو | نظام الصلاحيات في Claude Code يمنع إرسال بيانات الشركة إلى خدمة خارجية بدون موافقة | الـ commits محفوظة على الجهاز. شغّل `git push` بنفسك من مجلد `C:\duns-lookup`، أو وافق على الأمر | — |

</div>
