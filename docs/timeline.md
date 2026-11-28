<div dir="rtl">

# السجل الزمني الكامل

كل عملية تمت في طلب D-U-N-S وحسابي Google Play و Apple، مرتّبة بالتاريخ والوقت، من 2026-10-11 إلى 2026-11-24.

**عن الأوقات:**
- كل الأوقات **بتوقيت الرياض (UTC+3)** إلا إذا كُتب غير ذلك.
- **الوقت الدقيق** (مثل `10:35`) مأخوذ من ساعة الشاشة في الصور، أو وقت البريد، أو اسم الملف.
- **«قبل HH:MM»** يعني أن العملية تمت قبل هذا الوقت، لأنه وقت تسجيلها في الريبو (وقت الـ commit). الوقت الفعلي غير معروف بدقة.
- الخانة الفارغة تعني أن الوقت غير معروف.

| التاريخ | الوقت | النظام | العملية | المرجع |
|---|---|---|---|---|
| 2026-10-11 | | السجل التجاري | تجهيز المستندات: السجل التجاري نسخة 3 (عربي وإنجليزي) وشهادة السجل وإثبات العنوان الوطني، وإعادة تسميتها بالإنجليزي | [01](01-documents-and-legal-entity.md) |
| 2026-10-11 | | D&B | بدء الطلب في بوابة D&B لمطوري Apple بالبريد `khaled@ehsan.org.sa`: بيانات التواصل، و User Group: Developer Program | [02](02-dnb-new-duns.md) |
| 2026-10-11 | | D&B | البحث عن الشركة (D-U-N-S Search): **No Match**، ثم رابط طلب رقم جديد | [02](02-dnb-new-duns.md) |
| 2026-10-12 | | D&B | تعبئة نموذج Create D-U-N-S Number: Corporation، و CEO Chairman، و Date Business Started 05/15/2025، و SIC/NAICS فارغ | [02](02-dnb-new-duns.md) |
| 2026-10-12 | | D&B | تجهيز المرفقات الأربعة وملاحظة الكيان القانوني (Additional Details) | [02](02-dnb-new-duns.md) |
| 2026-10-13 | | D&B | تعديل عدد الموظفين من 56 إلى 7، ثم **إرسال الطلب: الحالة 34923947** | [02](02-dnb-new-duns.md) |
| 2026-10-14 | | D&B | بريد ملخص الحالة (Case Summary) 34923947 | [02](02-dnb-new-duns.md) |
| 2026-10-20 | | D&B | ✅ **صدور رقم D-U-N-S 986473058** باسم MADAR ALTAMKEEN COMPANY، صالح لـ Apple بعد 24 إلى 48 ساعة | [02](02-dnb-new-duns.md) |
| 2026-10-22 | | السجل التجاري | قرار تحديث النطاق والبريد في السجل التجاري قبل فتح حساب Google | [README](../README.md) |
| 2026-10-22 | | Workspace | إنشاء المستخدم `info@tmkeen.com.sa` في Google Workspace (تاريخ الإنشاء في صفحة المستخدم بلوحة المدير) | [00](00-account-reference.md) |
| 2026-11-05 | | DNS (dnet.sa) | آخر تعديل لإعدادات DNS للنطاق `tmkeen.com.sa` حسب الرقم التسلسلي للمنطقة (SOA serial 2026110512) | [00](00-account-reference.md) |
| 2026-11-15 | 10:35 | السجل التجاري | طباعة بيانات السجل التجاري **نسخة 4** من المركز السعودي للأعمال: البريد info@tmkeen.com.sa والموقع tmkeen.com.sa، والجوال بدون تغيير | [01](01-documents-and-legal-entity.md) |
| 2026-11-15 | قبل 10:39 | الريبو | إنشاء الريبو ورفع المستندات والتوثيق الأول على GitHub | [README](../README.md) |
| 2026-11-15 | | D&B | فتح ملف D&B للرقم 986473058 من نموذج التحديث: Legal Status = Corporation، والمنطقة **Ash Sharqiyah** خطأ، والرئيس فارغ | [03](03-dnb-update-duns.md) |
| 2026-11-15 | | DNS | فحص النطاق: `tmkeen.com.sa` بدون سجل A (لا يفتح)، و MX على Google (البريد يعمل) | [00](00-account-reference.md) |
| 2026-11-15 | قبل 10:51 | D&B | **إرسال طلب التحديث: الحالة 35015071** بالبريد `info@tmkeen.com.sa` (المنطقة، والرئيس، والموقع والبريد). تاريخ الرد المتوقع 2026-11-30 | [03](03-dnb-update-duns.md) |
| 2026-11-16 | قبل 11:01 | D&B | فحص الحالة: In Progress، ونوع الطلب Change-Update Company Information: Super 7 | [03](03-dnb-update-duns.md) |
| 2026-11-18 | | D&B | فحص ثانٍ: لا تغيير (In Progress) | [03](03-dnb-update-duns.md) |
| 2026-11-21 | 01:42 | D&B | بريد «**DUNS Number Update Completed** - Case #35015071» من globalcustomerservice@dnb.com: State ما زالت Ash Sharqiyah | [03](03-dnb-update-duns.md) |
| 2026-11-21 | 02:13 | D&B | بريد استبيان الرضا من noreply@feedback.dnb.com (اختياري) | [03](03-dnb-update-duns.md) |
| 2026-11-21 | قبل 09:38 | D&B | تجهيز رد على بريد D&B لتصحيح المنطقة (لم يُسجَّل في الريبو أنه أُرسل) | [03](03-dnb-update-duns.md) |
| 2026-11-21 | قبل 09:44 | D&B | قراءة ملف D&B بدون إرسال: أُضيف الرئيس Bader Saleh Ali Alabdulmunim (Chairman)، والمنطقة ما زالت Ash Sharqiyah | [03](03-dnb-update-duns.md) |
| 2026-11-21 | قبل 10:14 | Google Play | قرار البدء في Google Play قبل تصحيح المنطقة، لأن نموذج العنوان السعودي عند Google بدون منطقة | [05](05-google-play-console.md) |
| 2026-11-22 | قبل 17:35 | Google Play | بدء التسجيل في Play Console بحساب info@، وطلب تفعيل التحقق بخطوتين، ورفض التفعيل برسالة «We couldn't verify it's you» | [04](04-google-workspace-2sv.md) |
| 2026-11-22 | قبل 17:53 | Workspace | لوحة المدير: إيقاف «اختبار التحقق من تسجيل الدخول» 10 دقائق، ثم Authenticator (بعد مشكلة الرمز الخاطئ) و**تفعيل التحقق بخطوتين** | [04](04-google-workspace-2sv.md) |
| 2026-11-22 | قبل 17:53 | Google Play | نوع الحساب: مؤسسة ← شركة أو نشاط تجاري، والواجهة بالإنجليزي (`?hl=en`) | [05](05-google-play-console.md) |
| 2026-11-22 | قبل 17:57 | Google Play | اسم المطوّر `Madar alTamkeen`، وإدخال D-U-N-S 986473058، و Google يجلب بيانات D&B بدون منطقة | [05](05-google-play-console.md) |
| 2026-11-22 | قبل 18:02 | Google Play | ✅ إنشاء ملف الدفع **MADAR ALTAMKEEN COMPANY** (منفصل عن ملف Workspace `tmkeen.com.sa`)، وشاشة Your organization | [05](05-google-play-console.md) |
| 2026-11-22 | قبل 18:02 | الريبو | إضافة مجلد `docs/` بمراجع الخطوات | [README](README.md) |
| 2026-11-22 | قبل 18:23 | Google Play | Public profile (التحقق من info@)، و About you، و Apps، و How Google contacts you (تصحيح جوال ناقص رقماً)، و Terms. التوقف عند دفع 25 دولاراً بانتظار المالية | [05](05-google-play-console.md) |
| 2026-11-22 | قبل 18:27 | Apple | قرار البدء في Apple، وتحديد خالد الفوزان صاحباً للحساب، وجوال الشركة | [06](06-apple-developer.md) |
| 2026-11-22 | | Apple | محاولات إنشاء حساب Apple: «Your account cannot be created at this time»، ورمز الإيميل كُتب في شاشة الجوال بالخطأ، و SMS لم يصل إلى +966560509111 | [06](06-apple-developer.md) |
| 2026-11-23 | | Google Play | إعادة التسجيل: اختيار ملف الدفع MADAR ALTAMKEEN COMPANY، وإعادة إدخال الخانات | [05](05-google-play-console.md) |
| 2026-11-23 | | Google Play | رفض بطاقة Visa مسبقة الدفع بالخطأ `OR_CCR_61` | [05](05-google-play-console.md) |
| 2026-11-23 | ≈ 10:03 | Google Play | ✅ **دفع رسوم التسجيل 25 دولاراً** ببطاقة بنكية. مركز الدفع يعرضها «22 نوفمبر 11:03 م» بتوقيت Google (غالباً توقيت المحيط الهادئ الأمريكي، UTC-8)، وهذا يساوي تقريباً 10:03 صباح 23 نوفمبر بتوقيت الرياض. معرّف المعاملة PDS.9012-5319-2267-63316 | [05](05-google-play-console.md) |
| 2026-11-23 | قبل 10:06 | Google Play | ✅ **إنشاء حساب المؤسسة Madar alTamkeen** (8165465758097733916)، و4 إجراءات تحقق مطلوبة | [05](05-google-play-console.md) |
| 2026-11-23 | | Apple | بريد info@ يظهر أن حساب Apple أُنشئ رغم الخطأ: «تم التحقق من عنوان البريد الإلكتروني لحساب Apple» و «تم تحديث معلومات حساب Apple» | [06](06-apple-developer.md) |
| 2026-11-23 | 10:37 | Google Play | الطباعة من مركز الدفع لا تُظهر لوحة التفاصيل، فصُنع `documents/Google-Play-Registration-Receipt.pdf` من لقطتي الشاشة | [05](05-google-play-console.md) |
| 2026-11-23 | 10:38 | Google Play | إثبات الهوية، خطوة المؤسسة: «هل هذه المعلومات المؤكّدة لا تزال صحيحة؟» ← نعم | [05](05-google-play-console.md) |
| 2026-11-23 | قبل 10:44 | Google Play | رفع السجل التجاري بالإنجليزي كـ «مُقتطف من السجلّ التجاري»: **المؤسسة مُرسلة** | [05](05-google-play-console.md) |
| 2026-11-23 | قبل 11:07 | Apple | أول دخول إلى developer.apple.com: **الموافقة على Apple Developer Agreement** (LYL207)، و I'm not interested للملف الشخصي | [06](06-apple-developer.md) |
| 2026-11-23 | قبل 11:12 | Apple | Enroll today ← Continue enrollment on the web ← بيانات خالد ← **Company / Organization** ← MADAR ALTAMKEEN COMPANY و 986473058: ✅ **Apple طابقت D&B وقبلت الكيان القانوني** (Region: SA) | [06](06-apple-developer.md) |
| 2026-11-23 | 11:40 | Workspace | إنشاء مجموعة `bader@tmkeen.com.sa`: معلومات المجموعة | [06](06-apple-developer.md) |
| 2026-11-23 | 11:42 | Workspace | إعدادات المجموعة (النشر من الخارج، والانضمام بالدعوة، والأعضاء الخارجيون) ← ✅ إنشاء المجموعة، وإضافة info@ عضواً | [06](06-apple-developer.md) |
| 2026-11-23 | قبل 11:48 | Apple | صلاحية التوقيع: «My organization has given me the authority»، والمرجع بدر العبدالمنعم (Chairman of the Board) بإيميل bader@ | [06](06-apple-developer.md) |
| 2026-11-23 | قبل 11:57 | Apple | ✅ **إرسال طلب Apple Developer Program: Enrollment ID W25Z4X84PN** | [06](06-apple-developer.md) |
| 2026-11-23 | قبل 11:57 | Apple | بريد Apple بتأكيد الاستلام، والعنوان فيه بالمنطقة الخاطئة Ash Sharqiyah من D&B | [06](06-apple-developer.md) |
| 2026-11-24 | قبل 11:59 | Apple | مراسلة الدعم (Membership and Account ← Program Enrolment ← Email، الهاتف غير متاح): **Case 103023331470** | [06](06-apple-developer.md) |
| 2026-11-24 | 13:06 | Google Play | تصوير الهوية الوطنية لخالد (الوجهان) لإثبات الهوية | [05](05-google-play-console.md) |
| 2026-11-24 | قبل 16:15 | Apple | اكتشاف أن تاريخ الميلاد في حساب Apple لا يطابق الهوية الوطنية | [06](06-apple-developer.md) |
| 2026-11-24 | قبل 16:18 | Google Play | ✅ التفاصيل الشخصية: `ALFOUZAN, KHALID ABDULLAH A` وعنوان الشركة. «**تم التحقق من MADAR ALTAMKEEN COMPANY**» | [05](05-google-play-console.md) |
| 2026-11-24 | قبل 16:24 | Google Play | ✅ الإقرار بأن الحساب **جهة تجارية**، و «تم حفظ تسجيلك كجهة تجارية» | [05](05-google-play-console.md) |
| 2026-11-24 | قبل 16:30 | Search Console | ✅ إضافة النطاق `tmkeen.com.sa`: «**تم التحقق من الملكية تلقائياً**» عبر موفّر اسم النطاق | [05](05-google-play-console.md) |
| 2026-11-24 | 16:31 | Google Play | ✅ إرسال طلب إثبات الملكية: «**تم إثبات ملكية الموقع الإلكتروني**» | [05](05-google-play-console.md) |
| 2026-11-24 | 16:32 | Google Play | تأكيد أرقام الهواتف من تفاصيل جهة الاتصال (رسالة نصية) | [05](05-google-play-console.md) |
| 2026-11-24 | قبل 17:04 | Google Play | ✅ **حساب Google Play مكتمل**: اللوحة تعرض «إنشاء أول تطبيق لك» | [05](05-google-play-console.md) |
| 2026-11-24 | قبل 17:59 | Google Play | إشعار «**تم إثبات هويتك بنجاح**» (التأكيد النهائي)، وإشعار ترويجي اختياري عن رصيد Google Ads | [05](05-google-play-console.md) |
| 2026-11-24 | قبل 18:22 | الريبو | البطاقة المرجعية `docs/00-account-reference.md` وإضافات جدول المشاكل والحلول | [00](00-account-reference.md) |
| 2026-11-24 | 18:31 | الريبو | إضافة صلاحية `git push` المحلية (`.claude/settings.local.json`، خارج الريبو) والرفع على GitHub | [README](../README.md) |
| 2026-11-24 | قبل 20:11 | Apple | ملاحظة: developer.apple.com يقبل أي جهاز برمز OTP، أما account.apple.com فيحتاج موافقة الـ iPhone الموثوق | [06](06-apple-developer.md) |
| 2026-11-25 | | Apple | محاولة الاتصال: Membership and Account ← Program Enrolment. **الهاتف ما زال غير متاح** («Due to high call volumes»). الصفحة تعرض الحالة المفتوحة Case 103023331470 مع زر **Get more help**. لم تُرسل رسالة جديدة حتى لا تتكرر الحالات | [06](06-apple-developer.md) |
| 2026-11-26 | | Apple | توثيق طريقة تصحيح تاريخ الميلاد في حساب Apple (من الـ iPhone الموثوق). لم يُنفَّذ التصحيح بعد | [06](06-apple-developer.md) |
| 2026-11-28 | | Apple | ⚠️ صفحة developer.apple.com/account تعرض **«Join the Apple Developer Program / Enroll today»** بدل حالة الطلب W25Z4X84PN. زر التسجيل فتح نموذجاً جديداً، وأُوقف **قبل Continue** في شاشة صلاحية التوقيع حتى لا يُرسل طلب مكرر. جارٍ التأكد من الحساب المستخدم ومن بريد Apple | [06](06-apple-developer.md) |
| 2026-11-28 | | Apple | ❌ **السبب:** في صندوق `info@` بريد من Apple Developer بتاريخ **2026-11-23**: **«Your enrollment has been withdrawn»** للطلب W25Z4X84PN. لم ننتبه له يوم وصوله. الطلب انتهى، ولا دفع منتظر. جارٍ قراءة سبب السحب قبل طلب جديد | [06](06-apple-developer.md) |
| 2026-11-28 | | Apple | **سبب السحب: الموقع.** «Your organization's website must be publicly available, functional, and its domain name must be associated with your organization... Please resubmit your enrollment». `tmkeen.com.sa` لم يكن يفتح. الخطوة التالية: تشغيل الموقع بمحتوى حقيقي، ثم طلب جديد | [06](06-apple-developer.md) |
| 2026-11-28 | | الموقع | فحص `https://tmkeen.com.sa`: **يعمل** بشهادة صالحة، وفيه اسم الشركة ومشروع Maslak والتواصل والعنوان ونسخة عربية. ملاحظتان: الاتصال متقطع من شبكة المكتب (نصف المحاولات فشلت)، ولا توجد صفحة سياسة خصوصية | [06](06-apple-developer.md#فحص-الموقع-2026-11-28) |

## ما لم يحدث بعد

| العملية | الحالة |
|---|---|
| رد D&B على طلب تصحيح المنطقة | لم يُسجَّل إرسال الرد |
| تحقق Apple من صلاحية التوقيع، ورابط دفع 99 دولاراً | بانتظار Apple (الطلب W25Z4X84PN) |
| رد دعم Apple على Case 103023331470 | بانتظار Apple. إن لم يصل حتى 2026-11-30 أو 2026-12-01، تُرسل المتابعة الجاهزة في [06](06-apple-developer.md) من صفحة الحالة ← Email (2026-11-26 عيد الشكر في أمريكا) |
| تصحيح تاريخ الميلاد في حساب Apple | يُعمل من الـ iPhone الموثوق |
| تشغيل الموقع `tmkeen.com.sa` | لم يبدأ |

</div>
