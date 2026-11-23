<div dir="rtl">

# رقم D-U-N-S لشركة مدار التمكين

توثيق طلب رقم D-U-N-S من Dun & Bradstreet لشركة مدار التمكين، وتحديثه، والخطوات التالية لفتح حسابي Apple Developer و Google Play Console كمنظمة.

## المراجع

| الدليل | المحتوى |
|---|---|
| 📱 **[دليل Google Play Console](docs/05-google-play-console.md)** | كل خطوات التسجيل بقيمها، والإيصال، وإثبات الهوية، والتحقق من الموقع والجوال، والروابط |
| 🍎 **[دليل Apple Developer](docs/06-apple-developer.md)** | حساب Apple للشركة ومشاكل إنشائه، والشروط قبل التسجيل، وخطوات التسجيل، والروابط |

باقي الخطوات بالتفصيل في مجلد [docs](docs/README.md):
[المستندات ونوع الكيان](docs/01-documents-and-legal-entity.md) ·
[طلب رقم جديد](docs/02-dnb-new-duns.md) ·
[تحديث الملف](docs/03-dnb-update-duns.md) ·
[التحقق بخطوتين](docs/04-google-workspace-2sv.md) ·
[المشاكل والحلول](docs/troubleshooting.md)

## الحالة الحالية

| البند | القيمة |
|---|---|
| رقم D-U-N-S | **986473058** |
| الاسم القانوني عند D&B | **MADAR ALTAMKEEN COMPANY** |
| رقم حالة الطلب الأول | 34923947 |
| رقم حالة طلب التحديث | 35015071 |
| Legal Status عند D&B | **Corporation** ✅ |
| الرقم الوطني الموحد | 7050078752 |
| الكيان القانوني | شركة مساهمة مبسطة (Simplified Joint Stock Company)، صفة: شخص واحد |
| العنوان | 7481 Ayesha Bint Abi Bakr St, Ar Rimal Dist., Additional No. 2515, Buraidah 52363, Al Qassim, Saudi Arabia |
| العنوان المختصر | QBPD7481 |
| الجوال | +966560509111 |
| البريد (بعد التحديث) | info@tmkeen.com.sa |
| الموقع (بعد التحديث) | tmkeen.com.sa |

| المرحلة | الحالة |
|---|---|
| 1. طلب رقم D-U-N-S جديد | ✅ مكتمل (صدر الرقم 2026-10-20) |
| 2. تحديث بيانات الاتصال في السجل التجاري | ✅ مكتمل (نسخة السجل رقم 4) |
| 3. تحديث بيانات التواصل في D-U-N-S | ⚠️ اكتمل جزئياً 2026-11-21 (الحالة 35015071): بريد D&B «DUNS Number Update Completed»، لكن المنطقة ما زالت **Ash Sharqiyah** بدل Al Qassim. المطلوب: الرد على البريد نفسه بطلب التصحيح |
| 4. فتح حساب Google Play Console | ✅ أُنشئ 2026-11-23 (حساب مؤسسة Madar alTamkeen، ودُفعت الرسوم). ⏳ بقي: إثبات الهوية بالسجل التجاري، والإقرار بالجهة التجارية، وإثبات ملكية الموقع، وتأكيد أرقام الهواتف |
| 5. فتح حساب Apple Developer | ▶️ حساب Apple للشركة أُنشئ 2026-11-22 باسم Khalid Alfouzan رغم رسالة الرفض. ⏳ التسجيل كـ Organization ينتظر تشغيل الموقع |

> **✅ تحديث بيانات التواصل في D-U-N-S (2026-11-15):** حدّثنا بيانات التواصل لملف D-U-N-S رقم 986473058 بطلب التحديث 35015071. حساب بوابة D&B والتواصل صار على البريد `info@tmkeen.com.sa`، وطُلب إضافة الموقع `tmkeen.com.sa` والبريد الجديد إلى ملف الشركة. الجوال `+966560509111` بدون تغيير.

> **⚠️ نتيجة التحديث (2026-11-21):** وصل بريد D&B «DUNS Number Update Completed - Case #35015071». الاسم والعنوان والمدينة والرمز البريدي و Legal Structure = Corporation كلها صحيحة، لكن **State ما زالت Ash Sharqiyah** (الصحيح Al Qassim). فحص الملف في البوابة أظهر أن الرئيس Bader Saleh Ali Alabdulmunim (Chairman) أُضيف. الموقع والبريد لا يظهران في أي مكان، فلا نعرف إن أُضيفا. التفاصيل ونص الرد في [المرحلة 3](#نتيجة-التحديث-2026-11-21).

> **تنبيه (2026-11-15):** النطاق `tmkeen.com.sa` لا يفتح، لأنه غير مربوط بخادم في إعدادات DNS (لا يوجد سجل A). البريد يعمل (MX على Google). Apple تشترط موقعاً عاماً يفتح، فيجب تشغيل الموقع قبل التسجيل.

## سجل الأحداث

| التاريخ | الحدث |
|---|---|
| 2026-10-11 | تجهيز المستندات: السجل التجاري (عربي وإنجليزي) وإثبات العنوان الوطني، وإعادة تسميتها بالإنجليزي |
| 2026-10-11 | بدء الطلب على بوابة D&B الخاصة بـ Apple، والبحث عن الشركة: No Match |
| 2026-10-12 | تعبئة نموذج Create D-U-N-S Number (عدد الموظفين عُدّل لاحقاً من 56 إلى 7) |
| 2026-10-13 | إرسال الطلب، ورقم الحالة 34923947 |
| 2026-10-14 | وصول بريد ملخص الحالة من D&B |
| 2026-10-20 | صدور رقم D-U-N-S: 986473058 باسم MADAR ALTAMKEEN COMPANY |
| 2026-10-22 | قرار تحديث النطاق والبريد في السجل التجاري قبل فتح حساب Google |
| 2026-11-15 | تحديث السجل التجاري (نسخة 4): البريد info@tmkeen.com.sa والموقع tmkeen.com.sa، والجوال بدون تغيير |
| 2026-11-15 | فتح ملف D&B للرقم 986473058: Legal Status مسجّل Corporation، والمنطقة مسجّلة خطأً Ash Sharqiyah، واسم الرئيس فارغ |
| 2026-11-15 | إرسال طلب التحديث، ورقم الحالة 35015071 |
| 2026-11-16 | فحص الحالة في بوابة D&B: In Progress، ونوع الطلب Change-Update Company Information، وتاريخ الرد المتوقع 30 نوفمبر 2026. الموقع tmkeen.com.sa ما زال لا يفتح |
| 2026-11-18 | فحص ثانٍ: لا تغيير (In Progress). الموقع ما زال لا يفتح |
| 2026-11-21 | بريد D&B «DUNS Number Update Completed - Case #35015071». State ما زالت Ash Sharqiyah، وباقي البيانات صحيحة. تجهيز رد بطلب تصحيح المنطقة |
| 2026-11-21 | فحص ملف D&B من نموذج التحديث بدون إرسال: أُضيف الرئيس Bader Saleh Ali Alabdulmunim (Chairman)، والمنطقة ما زالت Ash Sharqiyah |
| 2026-11-21 | قرار البدء في Google Play Console الآن، وتصحيح المنطقة في D&B بعده. السبب: نموذج العنوان السعودي عند Google يحتوي الاسم والعنوان والمدينة والرمز البريدي فقط، وكلها صحيحة في D&B. النطاق tmkeen.com.sa فيه سجل TXT من نوع google-site-verification، مما يسهّل التحقق من الموقع في Search Console |
| 2026-11-22 | بدء التسجيل في Play Console بحساب info@tmkeen.com.sa. Google يشترط تفعيل التحقق بخطوتين أولاً، ومحاولة التفعيل رُفضت برسالة «We couldn't verify it's you» |
| 2026-11-22 | الحل من لوحة Google Workspace: إيقاف «اختبار التحقق من تسجيل الدخول» 10 دقائق للمستخدم، ثم إضافة Authenticator وتفعيل التحقق بخطوتين. Play Console فتح صفحة اختيار نوع الحساب: مؤسسة ← شركة أو نشاط تجاري |
| 2026-11-22 | Play Console: اسم المطوّر `Madar alTamkeen`. ملف دفع Google الموجود (باسم tmkeen.com.sa، ومستخدم لـ Workspace) لا يطابق D&B. أُدخل رقم D-U-N-S، وGoogle جلب من D&B: MADAR ALTAMKEEN COMPANY, Building Number 7481,Ayesha Bint Abi Bakr Street, Buraidah 52363, Saudi Arabia، بدون منطقة |
| 2026-11-22 | إنشاء ملف دفع جديد في Play Console ببيانات D&B: Registry Dun & Bradstreet، D-U-N-S 986473058، MADAR ALTAMKEEN COMPANY |
| 2026-11-22 | الوصول إلى شاشة Your organization: الحجم 1 - 10، والجوال +966 560509111، والموقع https://tmkeen.com.sa |
| 2026-11-22 | إضافة مجلد `docs/` بمراجع الخطوات والمشاكل وحلولها |
| 2026-11-22 | Play Console: إكمال Public profile (الجوال +966560509111 والبريد info@tmkeen.com.sa بعد التحقق) و About you (إعلان حساب Google شخصي سابق والتحقق منه) و Apps (أكثر من 10 تطبيقات، We don't know yet، None of the above) و How Google contacts you (Khalid Alfouzan، info@tmkeen.com.sa، English، +966560509111) و Terms. التسجيل متوقف عند دفع 25 دولاراً بانتظار المالية |
| 2026-11-22 | بدء التجهيز لحساب Apple Developer أثناء انتظار الدفع. القرار: البدء الآن بكتابة المنطقة Al Qassim، لأن Apple تطلب الدفع بعد الموافقة فقط. الموقع قيد التجهيز |
| 2026-11-22 | إنشاء حساب Apple جديد للشركة باسم Khalid Alfouzan وإيميل info@tmkeen.com.sa، بدل الحساب الشخصي الذي استُخدم في الطلب السابق |
| 2026-11-22 | Apple: «Your account cannot be created at this time» مرتين، ورمز SMS لم يصل إلى +966560509111. البدائل: تطبيق Apple Developer على iPhone، أو رقم آخر، أو الانتظار |
| 2026-11-23 | Play Console: إعادة التسجيل باختيار ملف الدفع MADAR ALTAMKEEN COMPANY. بطاقة Visa مسبقة الدفع رُفضت (OR_CCR_61)، ثم نجح الدفع ببطاقة أخرى |
| 2026-11-23 | إيصال الرسوم من payments.google.com (ملف MADAR ALTAMKEEN COMPANY): Developer Registration Fee، 25.00 دولاراً، مكتملة، معرّف المعاملة PDS.9012-5319-2267-63316. لم يصل بالبريد. وظهر في بريد info@ أن حساب Apple أُنشئ وتحقق إيميله رغم رسالة الخطأ |
| 2026-11-23 | Apple: الموافقة على Apple Developer Agreement، ثم Enroll today ← Continue enrollment on the web ← بيانات Khalid Alfouzan ← **Company / Organization** ← MADAR ALTAMKEEN COMPANY و 986473058. ✅ Apple طابقت D&B وقبلت الكيان القانوني، ولا توجد خانة منطقة (Region: SA) |
| 2026-11-23 | إثبات الهوية في Play Console: تأكيد بيانات المؤسسة من D&B، ورفع السجل التجاري بالإنجليزي كـ «مُقتطف من السجلّ التجاري». حالة المؤسسة: مُرسلة. بقيت التفاصيل الشخصية |
| 2026-11-23 | ✅ إنشاء حساب مؤسسة Google Play Console باسم Madar alTamkeen. بقيت 4 إجراءات: إثبات الهوية بالسجل التجاري، والإقرار بالجهة التجارية، وإثبات ملكية الموقع، وتأكيد أرقام الهواتف |

## المرحلة 1: طلب الرقم الجديد

البوابة: https://support.dnb.com/?CUST=APPLEDEV

1. إدخال البريد: `khaled@ehsan.org.sa`
2. بيانات التواصل (Contact Info)
3. فئة المستخدم: **Developer Program** (وليس Apple Business Manager)
4. البحث عن الشركة (D-U-N-S Search): النتيجة No Match، ثم رابط إنشاء رقم جديد
5. نموذج Create D-U-N-S Number
6. المرفقات والملاحظة، ثم Submit
7. انتظار 7 إلى 14 يوم عمل

### بيانات التواصل المُرسلة

| الحقل | القيمة |
|---|---|
| First Name | Khalid |
| Last Name | Alfouzan |
| Company | Madar alTamkeen Company |
| Job Title | Board Member |
| Phone | +966560509111 |
| Email | khaled@ehsan.org.sa |
| Street | 7481 Ayesha Bint Abi Bakr St, Ar Rimal Dist., Additional No. 2515 |
| City | Buraidah |
| State / Province | Al Qassim |
| Zip / Postal Code | 52363 |
| Country | Saudi Arabia |

### نموذج Create D-U-N-S Number

| الحقل | القيمة |
|---|---|
| Full Legal Business Name | Madar alTamkeen Company |
| DBA / Tradestyle | فارغ |
| Company Phone | +966560509111 |
| Business Street Address | 7481 Ayesha Bint Abi Bakr St, Ar Rimal Dist. |
| Address Line 2 | Additional No. 2515 |
| Business City | Buraidah |
| Business State / Province | Al Qassim |
| Business Postal Code | 52363 |
| Business Country | Saudi Arabia |
| Business Structure / Legal Structure | Simplified Joint Stock Company (Corporation) |
| CEO Name | Bader Saleh Ali Alabdulmunim |
| CEO Title | Chairman |
| Company Website | فارغ (لم يكن في السجل وقتها) |
| Home-Based Business? | No |
| Number of Employees | 7 |
| Date Business Started | 5/15/2025 (تاريخ قيد السجل التجاري) |
| SIC / NAICS | فارغ |

### الملاحظة المُرسلة (Additional Details)

```
This D-U-N-S request is for Apple Developer Program and Google Play Console organization enrollment. Madar alTamkeen Company is a Simplified Joint Stock Company (a corporation with limited liability and its own legal personality), registered with the Saudi Ministry of Commerce under Unified National Number 7050078752 on 15 May 2025. It is managed by a Board of Directors of 5 members (Chairman: Bader Saleh Ali Alabdulmunim) and has 7 employees. Please record the legal structure as Corporation / Joint Stock Company, NOT as a Sole Proprietorship. The "One Person" note on the commercial registration means the company has a single shareholder; it is not an individual business. Attached: commercial registration (English and Arabic) and National Address proof. Contact: Khalid Alfouzan, khaled@ehsan.org.sa, +966560509111.
```

## درس من تجربة سابقة: رفض Apple للكيان القانوني

طلب سابق لحاتم لمؤسسة تجارية أخرى رفضته Apple برسالة:

> This organization could not be verified as a legal entity. If you are a sole proprietorship/single person company, enroll as an individual.

السبب أن ملف D&B كان بدون نوع كيان، وأن «المؤسسة» في السعودية مؤسسة فردية لا تقبلها Apple كمنظمة. شركة مدار التمكين شركة لها شخصية اعتبارية، لكن صفة «شخص واحد» في السجل قد تُفهم كمؤسسة فردية. لذلك:

- Legal Structure كُتب **Simplified Joint Stock Company (Corporation)**، وليس One Person أو Establishment أو Sole Proprietorship.
- CEO Title **Chairman**، وليس Owner.
- عدد الموظفين **7**، وليس 1.
- الملاحظة تطلب صراحة تسجيل الشركة **Corporation**.
- السجل بالإنجليزي مرفق لأنه يذكر *Simplified joint stock company*.

إذا ظهر الخطأ عند Apple: رابط **update your D&B profile** في رسالة الخطأ، وطلب تحديث Legal Structure مع إرفاق السجل، ثم إعادة المحاولة بعد يومين عمل. وإن تكرر: https://developer.apple.com/contact/phone/

## المرحلة 3: تحديث ملف D-U-N-S (الحالة 35015071، اكتمل جزئياً)

### المسار في البوابة
1. https://support.dnb.com/?CUST=APPLEDEV والدخول بالبريد `info@tmkeen.com.sa`
2. Contact Info: Khalid / Alfouzan / `MADAR ALTAMKEEN COMPANY` / Board Member / +966560509111 / `info@tmkeen.com.sa` / نفس العنوان / Saudi Arabia
3. User Group: **Developer Program**
4. سبب الطلب: **Update or Correct DUNS** (وليس Create New DUNS، حتى لا يُنشأ رقم مكرر)
5. **I know my DUNS Number** ← `986473058` ← Lookup by DUNS
6. نموذج Update or Correct D-U-N-S: وضع علامة «I want to update this value» على الحقول المطلوبة فقط
7. المرفقات والملاحظة ← Submit

### ما وجدناه في ملف D&B قبل التحديث

| الحقل | المسجّل | الملاحظة |
|---|---|---|
| Company Name | MADAR ALTAMKEEN COMPANY | صحيح |
| Local Company Name | شركة مدار التمكين | صحيح |
| Company Phone | 966 560509111 | صحيح |
| Business Physical Address | Building Number 7481,Ayesha Bint Abi Bakr Street | صحيح |
| Business City | Buraidah | صحيح |
| Region / Territory | Ash Sharqiyah | **خطأ**، بريدة في منطقة القصيم |
| Business Postal Code | 52363 | صحيح |
| Legal Status | Corporation | **صحيح، ومشكلة Apple للكيان القانوني لن تتكرر** |
| CEO / Owner / Principal | فارغ | لم يُسجَّل رغم إرساله في الطلب الأول |
| SIC | 07210400 - Crop cultivating services | من أول نشاط في السجل، تُرك كما هو |
| NAICS | 115112 - Soil Preparation, Planting, and Cultivating | تُرك كما هو |
| الموقع والبريد | لا توجد خانات لهما في نموذج التحديث | طُلبا في الملاحظة |

### ما طُلب تحديثه

| الحقل | القيمة الجديدة |
|---|---|
| Region / Territory | Al Qassim |
| CEO / Owner / Principal Name | Bader Saleh Ali Alabdulmunim |
| CEO / Owner / Principal Title | Chairman |
| Website (في الملاحظة) | tmkeen.com.sa |
| Email (في الملاحظة) | info@tmkeen.com.sa |

حقول العنوان الأخرى ظهرت عليها العلامة مع تعديل المنطقة، وبقيت قيمها كما هي.

المرفقات: الملفات الأربعة في `documents/` (السجل نسخة 4 بالإنجليزي والعربي، وشهادة السجل، وإثبات العنوان الوطني).

### الملاحظة المُرسلة (Additional Details)

```
Update request for D-U-N-S 986473058 (MADAR ALTAMKEEN COMPANY).
1) Region / Territory correction: the company is located in Buraidah, Al Qassim Region, not Ash Sharqiyah (Eastern Province). See the attached commercial registration and National Address proof (Buraidah 52363).
2) CEO / Principal: Bader Saleh Ali Alabdulmunim, Chairman of the Board of Directors, as listed in the attached commercial registration.
3) Contact details updated on our commercial registration (copy 4): Website: tmkeen.com.sa, Email: info@tmkeen.com.sa, Phone: +966560509111 (unchanged). Please add the website and email to our D-U-N-S profile.
The legal name, street address and Legal Status (Corporation) are correct and should remain unchanged. This profile is used for Google Play Console and Apple Developer Program enrollment.
```

### المتابعة
- المدة 7 إلى 14 يوم عمل. بوابة D&B تعرض تاريخ الرد المتوقع **30 نوفمبر 2026** (آخر فحص 2026-11-16: In Progress).
- رابط الفحص: https://support.dnb.com/?CUST=APPLEDEV، والدخول بالبريد `info@tmkeen.com.sa`، فتظهر الحالة المفتوحة في أعلى صفحة Submit Case.
- الردود تصل إلى `info@tmkeen.com.sa`، والحالة في تبويب Case Status Report.
- قد تتصل D&B بأحد مسؤولي الشركة المسجلين للتحقق.

### نتيجة التحديث (2026-11-21)

وصل إلى `info@tmkeen.com.sa` بريد من `globalcustomerservice@dnb.com` بعنوان «DUNS Number Update Completed - Case #35015071». يطلب البريد إدخال البيانات في Apple كما هي بالضبط:

| الحقل في بريد D&B | القيمة | الحكم |
|---|---|---|
| DUNS | 986473058 | ✅ |
| Company Name | MADAR ALTAMKEEN COMPANY | ✅ |
| Trade Style | فارغ | ✅ لا يوجد اسم تجاري مختلف |
| Street Address | Building Number 7481,Ayesha Bint Abi Bakr Street | ✅ |
| City | Buraidah | ✅ |
| State | **Ash Sharqiyah** | ❌ لم يُصحَّح، والصحيح Al Qassim |
| Zip | 52363 | ✅ |
| Legal Structure | Corporation | ✅ |
| Country | Saudi Arabia | ✅ |

مصدر Ash Sharqiyah ليس من طرفنا: اخترنا Al Qassim في نموذج الإنشاء (الحالة 34923947) وفي نموذج التحديث (الحالة 35015071)، وكل المستندات تذكر بريدة والقصيم. تكرار القيمة نفسها مرتين رغم ذلك يرجّح أن نظام D&B يحدد المنطقة تلقائياً من العنوان، لذلك يطلب الرد تصحيحها يدوياً.

### ملف D&B بعد التحديث (فحص 2026-11-21 من نموذج Update or Correct DUNS، بدون إرسال)

| الحقل | قبل التحديث | بعد التحديث | الحكم |
|---|---|---|---|
| Company Name | MADAR ALTAMKEEN COMPANY | بدون تغيير | ✅ |
| Local Company Name | شركة مدار التمكين | بدون تغيير | ✅ |
| Company Phone | 966 560509111 | بدون تغيير | ✅ |
| Business Physical Address | Building Number 7481,Ayesha Bint Abi Bakr Street | بدون تغيير | ✅ |
| Business City | Buraidah | بدون تغيير | ✅ |
| Region / Territory | Ash Sharqiyah | **Ash Sharqiyah** | ❌ لم يُصحَّح |
| Business Postal Code | 52363 | بدون تغيير | ✅ |
| Local Company Address | لم يُسجَّل | `52363 SA` فقط | ⚠️ ناقص، لكن Apple و Google يستخدمان العنوان الإنجليزي |
| Legal Status | Corporation | بدون تغيير | ✅ |
| CEO / Owner / Principal Name | فارغ | **Bader Saleh Ali Alabdulmunim** | ✅ أُضيف |
| CEO / Owner / Principal Title | فارغ | **Chairman** | ✅ أُضيف |
| SIC / NAICS | 07210400 / 115112 | بدون تغيير | كما طلبنا |

النتيجة: نُفّذ جزء الرئيس من الطلب، ولم يُنفَّذ تصحيح المنطقة. النموذج ليس فيه خانات للموقع والبريد.

الموقع والبريد لا يظهران في بريد الإتمام ولا في النموذج، فيطلب الرد من D&B تأكيدهما. وما تراه Apple يُفحص في https://developer.apple.com/enroll/duns-lookup/ بعد يومين عمل.

وصل بعده بريد استبيان رضا من `noreply@feedback.dnb.com`، وهو اختياري.

### الرد المطلوب على بريد D&B

يُرسل بالضغط على **رد (Reply)** في بريد «DUNS Number Update Completed» نفسه، مع ترك العنوان كما هو حتى يُربط بالحالة 35015071. المرفقات: `documents/Madar-alTamkeen-National-Address-Proof.png` و `documents/Madar-alTamkeen-CR-Details-English.pdf`.

```
Hello,

Thank you for updating D-U-N-S 986473058 (MADAR ALTAMKEEN COMPANY).

One correction from our request is still missing: the State is listed as "Ash Sharqiyah". Our company is located in Buraidah, which is in the Al Qassim Region, not Ash Sharqiyah (Eastern Province). Please change the State to "Al Qassim", as shown in the attached National Address proof and commercial registration.

We selected "Al Qassim" in both our original request (case 34923947) and our update request (case 35015071), but the record still shows "Ash Sharqiyah". If the region is set automatically from the address, please correct it manually.

The company name, street address, city (Buraidah), zip (52363) and Legal Structure (Corporation) are correct and should remain unchanged.

Could you also confirm that the following details from our request were added to the profile?
- Website: tmkeen.com.sa
- Email: info@tmkeen.com.sa

Thank you,
Khalid Alfouzan
Board Member, MADAR ALTAMKEEN COMPANY
+966560509111
```

## Google Play Console

- ✅ **حساب مؤسسة** باسم **Madar alTamkeen** بإيميل `info@tmkeen.com.sa`، ورقم تعريف الحساب `8165465758097733916`. الرسوم 25 دولاراً دُفعت، والإيصال في `documents/Google-Play-Registration-Receipt.pdf`.
- ⏳ **إثبات الهوية:** مستند المؤسسة (السجل التجاري) مُرسل، والتفاصيل الشخصية لخالد الفوزان بجوازه لم تكتمل.
- ⏳ بعده: الإقرار بالجهة التجارية، وإثبات ملكية الموقع، وتأكيد أرقام الهواتف.

**الدليل الكامل: [docs/05-google-play-console.md](docs/05-google-play-console.md)**

| الغرض | الرابط |
|---|---|
| لوحة Play Console | https://play.google.com/console/developers/8165465758097733916/home |
| إيصال الرسوم (اختر ملف MADAR ALTAMKEEN COMPANY) | https://payments.google.com/gp/w/home/activity |
| التحقق من ملكية الموقع | https://search.google.com/search-console |

## Apple Developer

- ✅ **حساب Apple للشركة** باسم Khalid Alfouzan وإيميل `info@tmkeen.com.sa`. أُنشئ رغم رسالة «Your account cannot be created at this time»، فلا يُنشأ حساب آخر.
- ⏳ **التسجيل كـ Organization لم يبدأ.** ينتظر تشغيل موقع `tmkeen.com.sa`، ويُفضّل تصحيح المنطقة في D&B إلى Al Qassim قبله.
- الرسوم 99 دولاراً سنوياً، وتُدفع بعد موافقة Apple فقط.

**الدليل الكامل: [docs/06-apple-developer.md](docs/06-apple-developer.md)**

| الغرض | الرابط |
|---|---|
| حساب Apple | https://account.apple.com |
| التسجيل في برنامج المطورين | https://developer.apple.com/programs/enroll/ |
| فحص رقم D-U-N-S كما تراه Apple | https://developer.apple.com/enroll/duns-lookup/ |
| تطبيق Apple Developer على iPhone | https://apps.apple.com/app/apple-developer/id640199958 |

## الملفات

| المسار | الوصف |
|---|---|
| `docs/` | مراجع الخطوات بالتفصيل، والمشاكل وحلولها |
| `docs/agreements/apple-developer-agreement-LYL207.md` | نص Apple Developer Agreement الذي وافق عليه حساب الشركة في 2026-11-23 |
| `documents/Madar-alTamkeen-CR-Details-English.pdf` | بيانات السجل بالإنجليزي، نسخة 4 (2026-11-15) |
| `documents/Madar-alTamkeen-CR-Details-Arabic.pdf` | بيانات السجل بالعربي، نسخة 4 (2026-11-15) |
| `documents/Madar-alTamkeen-CR-Certificate-Arabic.pdf` | شهادة السجل التجاري (وزارة التجارة) |
| `documents/Madar-alTamkeen-National-Address-Proof.png` | إثبات العنوان الوطني، صالح حتى 26/3/2027 |
| `documents/Google-Play-Registration-Receipt.pdf` | إيصال رسوم Google Play (25 دولاراً) للمالية، من لقطات مركز الدفع |
| `archive/2026-10-cr-copy-3/` | السجل نسخة 3، المُرفق في الطلب الأول (قبل تحديث بيانات الاتصال) |
| `forms/Madar-alTamkeen-DUNS-Case-34923947.pdf` | نموذج A4 بكل البيانات المُرسلة في الطلب 34923947 ورقم D-U-N-S |
| `pages/duns-steps-tracker.html` | صفحة الخطوات التفاعلية مع أزرار النسخ |
| `pages/duns-a4-record.html` | سجل A4 للقراءة فقط مع زر تحميل PDF |

> الريبو خاص لأنه يحوي مستندات الشركة وبيانات أعضاء مجلس الإدارة. لا تجعله عاماً.

</div>
