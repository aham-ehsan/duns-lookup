<div dir="rtl">

# 6. حساب Apple Developer

- **الحالة:** ⏳ لم يبدأ.
- **الرسوم:** 99 دولاراً سنوياً.
- **رابط التسجيل:** https://developer.apple.com/programs/enroll/

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
