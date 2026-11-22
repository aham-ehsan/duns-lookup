<div dir="rtl">

# 6. حساب Apple Developer

- **الحالة:** ▶️ بدأ 2026-11-22 بإنشاء حساب Apple للشركة.
- **صاحب الحساب:** خالد الفوزان (Khalid Alfouzan)، عضو مجلس الإدارة.
- **الرسوم:** 99 دولاراً سنوياً، وتُدفع **بعد** موافقة Apple على المنظمة، فالبدء لا يكلف شيئاً.
- **رابط التسجيل:** https://developer.apple.com/programs/enroll/

## قرار: البدء قبل اكتمال الشروط

بدأنا 2026-11-22 قبل تصحيح المنطقة وقبل تشغيل الموقع، لأن Apple لا تطلب الدفع قبل الموافقة. المنطقة تُكتب **Al Qassim** لأنها الصحيحة. إذا قالت Apple إن البيانات لا تطابق D&B، ننتظر تصحيح D&B ثم نعيد المحاولة. الموقع قيد التجهيز.

## درس من التجربة السابقة: لا تستخدم حساب Apple الشخصي

في طلب حاتم السابق لمؤسسة أخرى، أُنشئ حساب Apple شخصي، وسُجّلت المؤسسة من داخله. هذه المرة:

- **حساب Apple جديد خاص بالشركة** على إيميلها `info@tmkeen.com.sa`، وليس حساباً شخصياً قديماً فيه مشتريات و iCloud وتسجيلات سابقة.
- **حساب Apple يكون دائماً باسم شخص حقيقي.** هذا طبيعي، فالذي يحدد أن الحساب للشركة هو **نوع العضوية Organization** في Apple Developer.
- **صاحب الحساب له صلاحية قانونية لإلزام الشركة** (مالك، أو عضو في الإدارة، أو مفوّض من أحدهم)، لأن Apple قد تتصل به للتحقق.

## إنشاء حساب Apple للشركة (2026-11-22)

https://account.apple.com ← **Create Your Apple Account**، ويفضّل في نافذة تصفح خاصة حتى لا يدخل حساب شخصي تلقائياً.

| الخانة | القيمة | ملاحظة |
|---|---|---|
| First name | `Khalid` | كما في هويته بالإنجليزي |
| Last name | `Alfouzan` | كما في هويته بالإنجليزي، فإن كانت الكتابة فيها مختلفة تُستخدم كتابة الهوية |
| Country/Region | Saudi Arabia | |
| Date of birth | تاريخ ميلاد خالد | لا يُسجَّل هنا |
| Email | `info@tmkeen.com.sa` | إيميل الشركة |
| Password | كلمة مرور قوية تحفظها الشركة | لا تُكتب في الريبو |
| Phone | جوال خالد مع +966 | يستقبل رموز الدخول دائماً، فيجب أن يبقى معه |
| Announcements / Apps, Music, TV and More | بدون علامة | رسائل تسويقية اختيارية |

بعدها رمز تحقق على الإيميل، ثم رمز على الجوال.

## الشروط قبل التسجيل

| الشرط | الوضع الحالي | المطلوب |
|---|---|---|
| ملف D&B: Legal Status = Corporation | ✅ | لا شيء. انظر [نوع الكيان](01-documents-and-legal-entity.md#لماذا-يهم-نوع-الكيان) |
| ملف D&B: المنطقة Al Qassim | ❌ مسجّلة Ash Sharqiyah | الرد على بريد D&B بطلب التصحيح. انظر [تحديث ملف D-U-N-S](03-dnb-update-duns.md#الرد-على-dnb-لتصحيح-المنطقة) |
| موقع عام يفتح | ❌ `tmkeen.com.sa` بدون سجل A في DNS | ربط النطاق بخادم وتشغيل صفحة فيها اسم الشركة والعنوان والتواصل |
| إيميل عمل على نطاق الشركة | ✅ `info@tmkeen.com.sa` يعمل (MX على Google) | استخدامه أو إيميل آخر على `tmkeen.com.sa` لحساب Apple |

**لماذا المنطقة مهمة لـ Apple وليست مهمة لـ Google؟** بريد D&B بإتمام التحديث يقول:

> When enrolling in Apple, please enter the information exactly as it is listed below.

والبيانات فيه تتضمن **State: Ash Sharqiyah**. نموذج Apple فيه خانة منطقة، فلو تركنا الخطأ إما أن نكتب منطقة خاطئة، أو يختلف العنوان عن ملف D&B. أما Google فليس عنده خانة منطقة للعناوين السعودية.

## الخطوة 1: فحص الرقم في أداة Apple

افتح https://developer.apple.com/enroll/duns-lookup/ وسجّل الدخول بحساب Apple، ثم ابحث بهذه البيانات:

| الخانة | القيمة |
|---|---|
| Legal Entity Name | `MADAR ALTAMKEEN COMPANY` |
| Address | `Building Number 7481, Ayesha Bint Abi Bakr Street` |
| City | `Buraidah` |
| Postal Code | `52363` |
| Country | Saudi Arabia |

- أي تعديل في D&B يحتاج **يومي عمل** حتى يصل إلى Apple. افحص بعد يومين من بريد D&B.
- تأكد أن الأداة تعرض الرقم `986473058` والمنطقة **Al Qassim** قبل أن تسجّل.

## الخطوة 2: التسجيل

1. افتح https://developer.apple.com/programs/enroll/ وسجّل بحساب Apple على إيميل الشركة.
2. اختر التسجيل كـ **Organization**، وليس Individual.
3. أدخل الرقم `986473058` والبيانات **كما في ملف D&B حرفياً**.
4. أدخل الموقع `https://tmkeen.com.sa`.
5. Apple قد تتصل بأحد مسؤولي الشركة للتحقق من صلاحيته لتسجيل الشركة.
6. ادفع 99 دولاراً.

تُكمَل هذه الخطوات بالقيم الفعلية عند التنفيذ.

## إذا رفضت Apple الكيان القانوني

الرسالة:

> This organization could not be verified as a legal entity. If you are a sole proprietorship/single person company, enroll as an individual.

1. اضغط رابط **update your D&B profile** في رسالة الخطأ.
2. اطلب تحديث **Legal Structure** إلى Corporation، وأرفق السجل التجاري بالإنجليزي.
3. أعد المحاولة بعد يومي عمل.
4. إن تكرر الخطأ، تواصل مع Apple Developer Support: https://developer.apple.com/contact/

ملف D&B الحالي مسجّل **Corporation**، فلا نتوقع هذا الخطأ. انظر [المستندات ونوع الكيان](01-documents-and-legal-entity.md).

</div>
