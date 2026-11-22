<div dir="rtl">

# 5. حساب Google Play Console

- **الحالة:** التسجيل جارٍ منذ 2026-11-22. ملف الدفع أُنشئ ومطابق لـ D&B.
- **الحساب:** `info@tmkeen.com.sa` (حساب Google Workspace للشركة).
- **الرسوم:** 25 دولاراً مرة واحدة.

## قبل البدء

1. **التحقق بخطوتين** يجب أن يكون مفعّلاً على حساب Google. انظر [التحقق بخطوتين في Google Workspace](04-google-workspace-2sv.md).
2. **رقم D-U-N-S** للشركة: `986473058`.
3. **صاحب جوال الشركة** `+966560509111` قريب منك، لأن Google يرسل رمز SMS.
4. **المستندات** في `documents/`: السجل التجاري بالإنجليزي وإثبات العنوان الوطني.
5. **بطاقة دفع** للرسوم.

## الخطوة 1: فتح صفحة التسجيل

افتح https://play.google.com/console/signup?hl=en وادخل بحساب `info@tmkeen.com.sa`.

أضفنا `?hl=en` لتظهر الواجهة بالإنجليزي، لثلاثة أسباب:
- أسماء الخانات تطابق ملف D&B، فتنقل البيانات بدون ترجمة.
- رسائل الخطأ تطابق صفحات مساعدة Google، فيسهل البحث عنها.
- الترجمة العربية في Play Console أحياناً غير دقيقة.

لغة الواجهة لا تغيّر بيانات الحساب. أما البيانات التي تكتبها فتكون **بالإنجليزي وكما في D&B** دائماً.

## الخطوة 2: نوع الحساب (Account type)

| الخانة | القيمة | السبب |
|---|---|---|
| نوع الحساب | **An organization** | الحساب للشركة، وليس لشخص (Yourself) |
| Organization type | **A company or business** | مدار التمكين شركة مساهمة مبسطة، وD&B تسجّلها Corporation |

الخيارات الأخرى في القائمة: A nonprofit، A government organization، An educational institution. لا تنطبق على الشركة.

## الخطوة 3: ما تحتاجه (What you'll need)

Google يعرض قائمة بما يلزم لحساب المنظمة:

| المطلوب | التفاصيل |
|---|---|
| D-U-N-S number | Google يجلب بيانات الشركة من D&B، ثم يطلب **مستنداً رسمياً** يثبتها |
| Phone and email for your public profile | يظهران للمستخدمين في Google Play. يُتحقق من الإيميل أثناء التسجيل، ومن الجوال بعد إنشاء الحساب |
| Contact phone and email for Google | لا يظهران للناس، ويستخدمهما Google للتواصل معك. يُتحقق منهما بنفس الطريقة |
| A form of payment | لرسوم 25 دولاراً مرة واحدة |

استمر فقط إذا كانت لديك صلاحية كاملة لإنشاء حساب باسم الشركة.

## الخطوة 4: اسم المطوّر (Developer name)

| الخانة | القيمة |
|---|---|
| Developer name | `Madar alTamkeen` |

- هذا **الاسم العام** الذي يظهر تحت كل تطبيق في Google Play. ليس الاسم القانوني، ويمكن تغييره لاحقاً.
- اخترنا الإنجليزي وبنفس كتابة السجل التجاري، لأنه يتطابق مع الاسم القانوني عند D&B، ويظهر صحيحاً لكل المستخدمين، وسيكون نفس الاسم في Apple.
- العربي `مدار التمكين` مقبول أيضاً.

## الخطوة 5: ملف الدفع (Payments profile)

Google يربط حساب المطوّر بملف دفع، ويشترط أن **يطابق الاسم القانوني والعنوان فيه ملف D&B**.

### اختيار الملف

ظهر في نافذة **Select a payments profile** ملف موجود:

| | الملف الموجود | ملف D&B |
|---|---|---|
| الاسم | `tmkeen.com.sa` | `MADAR ALTAMKEEN COMPANY` |
| العنوان | 7481 Ayesha Bint Abi Bakr St., Ar Rimal Dist., Unit 2515 (QBPD7481), Buraidah 52363 | Building Number 7481,Ayesha Bint Abi Bakr Street, Buraidah 52363 |
| الاستخدام | فواتير Google Workspace | — |
| التنبيه | *A D-U-N-S number is required* | — |

اخترنا **Create new payments profile** لأن الملف الموجود لا يطابق D&B في الاسم ولا العنوان، ولأنه مستخدم لفواتير Workspace.

### إدخال رقم D-U-N-S

| الخانة | القيمة |
|---|---|
| D-U-N-S number | `986473058` |

- عدد المحاولات **محدود**، فتأكد من الرقم قبل **Next**.
- الرقم 9 أرقام فقط، بدون شرطات أو مسافات.

### تأكيد بيانات D&B (Confirm your D-U-N-S info)

Google جلب هذه البيانات من D&B:

```
D-U-N-S: 986473058
MADAR ALTAMKEEN COMPANY
Building Number 7481,Ayesha Bint Abi Bakr Street
Buraidah 52363
Saudi Arabia
```

- **لا تظهر منطقة.** نموذج العنوان السعودي عند Google يحتوي الاسم والشركة والعنوان والمدينة والرمز البريدي فقط ([بيانات Google للعناوين السعودية](https://chromium-i18n.appspot.com/ssl-address/data/SA)). لذلك خطأ المنطقة Ash Sharqiyah في ملف D&B **لا يؤثر على Google**. انظر [تحديث ملف D-U-N-S](03-dnb-update-duns.md#النتيجة).
- العبارة *Changes affect all accounts that use this payments profile* تعني أن أي تعديل على الملف يظهر في كل خدمات Google التي تستخدمه.
- Google ينبّه أنك ستحتاج بعد التسجيل إلى **مستندات تطابق هذه البيانات**.

اضغط **Confirm**.

### النتيجة

ظهرت نافذة **You're all set**: *Your payments profile was created and added to your account.* اضغط **Got it**.

صفحة ملف الدفع تعرض الآن:

| البيان | القيمة |
|---|---|
| Registry | Dun & Bradstreet |
| D-U-N-S number | 986473058 |
| Organization name | MADAR ALTAMKEEN COMPANY |
| Organization address | Building Number 7481,Ayesha Bint Abi Bakr Street, Buraidah - 52363, Saudi Arabia (SA) |

اضغط **Next**.

## الخطوة 6: معلومات المنظمة (Your organization)

هذه المعلومات لا تظهر للناس، ولا تؤثر على الخدمات المتاحة لك.

| الخانة | القيمة | السبب |
|---|---|---|
| Organization size | `1 - 10` | عدد الموظفين 7، كما في طلب D&B |
| Organization phone number | `+966 560509111` | جوال الشركة في السجل التجاري و D&B |
| Organization website | `https://tmkeen.com.sa` | موقع الشركة في السجل التجاري نسخة 4 |

خيارات Organization size الأخرى: 11 - 100، 101 - 500، 501 - 1,000، 1,001 - 5,000، More than 5,000، Don't know.

## الخطوات المتبقية (لم تُنفَّذ بعد)

تُكمَل هذه الأقسام عند تنفيذها.

| الخطوة | ما نعرفه مسبقاً | الحالة |
|---|---|---|
| Public profile | إيميل وجوال يظهران للمستخدمين: `info@tmkeen.com.sa` و `+966560509111`. يُتحقق من الإيميل برمز أثناء التسجيل | ⏳ |
| About you | بيانات الشخص المسؤول عن الحساب | ⏳ |
| Apps | أسئلة عن التطبيقات المخطط نشرها | ⏳ |
| How Google contacts you | إيميل وجوال لا يظهران للناس. يفضّل أن يكونا لشخص مسؤول تصل إليه بسرعة | ⏳ |
| Terms | الموافقة على اتفاقية المطوّر | ⏳ |
| دفع الرسوم | 25 دولاراً مرة واحدة | ⏳ |
| التحقق من ملكية الموقع | انظر القسم التالي | ⏳ |
| التحقق من الجوال (OTP) | رمز SMS يصل إلى الجوال **بعد إنشاء الحساب**. في حسابات المنظمات يأتي بعد التحقق من الموقع | ⏳ |
| التحقق من المستندات | السجل التجاري بالإنجليزي للاسم، وإثبات العنوان الوطني للعنوان (رقم المبنى 7481 وشارع عائشة بنت أبي بكر) | ⏳ |

### التحقق من ملكية الموقع

Google يشترط في حسابات المنظمات إثبات ملكية الموقع عبر **Google Search Console**:

1. افتح https://search.google.com/search-console بنفس حساب Google الذي أنشأت به Play Console.
2. أضف خاصية من نوع **Domain** واكتب `tmkeen.com.sa`.
3. النطاق فيه **سجل TXT من نوع `google-site-verification` موجود مسبقاً**، غالباً من وقت إعداد Workspace. قد يتحقق Search Console فوراً. وإن لم يتحقق، يعطيك سجل TXT جديداً يضيفه مسؤول النطاق عند مزوّد DNS (dnet.sa).
4. في Play Console أرسل طلب التحقق من الموقع من صفحة الهوية. إذا كان الحساب نفسه في Search Console و Play Console، يُقبل الطلب تلقائياً.

التحقق من الملكية يعمل عبر DNS حتى لو كان الموقع لا يفتح. لكن `tmkeen.com.sa` حالياً **بدون سجل A** ولا يفتح، وGoogle قد يراجع الموقع، فالأسلم تشغيل صفحة بسيطة عليه فيها اسم الشركة والعنوان والتواصل.

## المصادر

- [Required information to create a Play Console developer account](https://support.google.com/googleplay/android-developer/answer/13628312?hl=en)
- [Verify your developer identity information](https://support.google.com/googleplay/android-developer/answer/10841920?hl=en)
- [Verify your Android developer identity information](https://support.google.com/android-developer-console/answer/16641416?hl=en)
- [Choose a developer account type](https://support.google.com/googleplay/android-developer/answer/13634885?hl=en)
- [Contact information requirements for developer accounts](https://support.google.com/googleplay/android-developer/answer/10840893?hl=en)
- [Update developer identity details managed by a Google payments profile](https://support.google.com/googleplay/android-developer/answer/16260648?hl=en)
- [Google address data for Saudi Arabia](https://chromium-i18n.appspot.com/ssl-address/data/SA)

</div>
