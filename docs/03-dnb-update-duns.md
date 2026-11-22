<div dir="rtl">

# 3. تحديث ملف D-U-N-S

استخدمنا هذا المسار لتصحيح المنطقة، وإضافة رئيس مجلس الإدارة، وإضافة الموقع والبريد الجديدين بعد تحديث السجل التجاري.

- **الحالة:** 35015071، أُرسلت 2026-11-15.
- **النتيجة:** «DUNS Number Update Completed» في 2026-11-21. أُضيف الرئيس، **ولم تُصحَّح المنطقة**.

## المسار في البوابة

1. افتح https://support.dnb.com/?CUST=APPLEDEV وادخل بالبريد `info@tmkeen.com.sa`.
2. **Contact Info:** Khalid / Alfouzan / `MADAR ALTAMKEEN COMPANY` / Board Member / +966560509111 / `info@tmkeen.com.sa` / نفس العنوان / Saudi Arabia.
3. **User Group:** Developer Program.
4. **سبب الطلب:** اختر **Update or Correct DUNS**، وليس Create New DUNS، حتى لا يُنشأ رقم مكرر.
5. اختر **I know my DUNS Number**، واكتب `986473058`، ثم **Lookup by DUNS**.
6. في نموذج **Update or Correct D-U-N-S** ضع علامة **I want to update this value** على الحقول المطلوب تغييرها فقط.
7. أرفق المستندات، والصق الملاحظة، ثم **Submit**.

## قراءة الملف بدون إرسال

النموذج في الخطوة 6 يعرض **القيم المسجلة حالياً** داخل الخانات. استخدمه لفحص الملف في أي وقت:

1. نفّذ الخطوات 1 إلى 5.
2. صوّر النموذج كاملاً.
3. **لا تضع أي علامة ولا تضغط Next**، ثم أغلق الصفحة.

النموذج لا يعرض الموقع والبريد، فليس فيه خانات لهما.

## ما طلبناه

| الحقل | قبل | المطلوب |
|---|---|---|
| Region / Territory | Ash Sharqiyah | Al Qassim |
| CEO / Owner / Principal Name | فارغ | Bader Saleh Ali Alabdulmunim |
| CEO / Owner / Principal Title | فارغ | Chairman |
| Website (في الملاحظة) | — | tmkeen.com.sa |
| Email (في الملاحظة) | — | info@tmkeen.com.sa |

- حقول العنوان الأخرى تظهر عليها العلامة تلقائياً مع تعديل المنطقة. اترك قيمها كما هي.
- لا تغيّر SIC و NAICS إلا إذا كنت متأكداً من الكود.
- **المرفقات:** الملفات الأربعة في `documents/`.

### الملاحظة المُرسلة (Additional Details)

```
Update request for D-U-N-S 986473058 (MADAR ALTAMKEEN COMPANY).
1) Region / Territory correction: the company is located in Buraidah, Al Qassim Region, not Ash Sharqiyah (Eastern Province). See the attached commercial registration and National Address proof (Buraidah 52363).
2) CEO / Principal: Bader Saleh Ali Alabdulmunim, Chairman of the Board of Directors, as listed in the attached commercial registration.
3) Contact details updated on our commercial registration (copy 4): Website: tmkeen.com.sa, Email: info@tmkeen.com.sa, Phone: +966560509111 (unchanged). Please add the website and email to our D-U-N-S profile.
The legal name, street address and Legal Status (Corporation) are correct and should remain unchanged. This profile is used for Google Play Console and Apple Developer Program enrollment.
```

## متابعة الحالة

- ادخل البوابة بنفس البريد. إذا كان عندك طلب مفتوح، يظهر في أعلى صفحة **Submit Case** جدول فيه رقم الحالة والحالة وتاريخ الرد المتوقع.
- **In Progress** تعني أن موظفاً يراجع الطلب، وهي الحالة الطبيعية أثناء الانتظار.
- العبارة الحمراء «*Your request has not met or exceeded the Expected Response date*» تظهر مع كل طلب لم يصل تاريخه المتوقع، ولا تعني وجود مشكلة.
- «Super 7» في خانة السبب تصنيف داخلي عند D&B لطلبات تحديث بيانات الشركة.
- الردود تصل إلى البريد المستخدم في الطلب. يكفي الفحص مرة كل بضعة أيام.

| التاريخ | الحالة |
|---|---|
| 2026-11-15 | أُرسل الطلب. تاريخ الرد المتوقع 2026-11-30 |
| 2026-11-16 و 18 | In Progress |
| 2026-11-21 | بريد «DUNS Number Update Completed - Case #35015071»، أي قبل التاريخ المتوقع بتسعة أيام |

بعد الإتمام يصل بريد استبيان رضا من `noreply@feedback.dnb.com`، وهو اختياري.

## النتيجة

| الحقل | بعد التحديث | |
|---|---|---|
| Company Name | MADAR ALTAMKEEN COMPANY | ✅ |
| Street Address | Building Number 7481,Ayesha Bint Abi Bakr Street | ✅ |
| City / Zip | Buraidah / 52363 | ✅ |
| Legal Status | Corporation | ✅ |
| CEO | Bader Saleh Ali Alabdulmunim (Chairman) | ✅ أُضيف |
| Region / State | **Ash Sharqiyah** | ❌ لم يُصحَّح |
| Local Company Address | `52363 SA` فقط | ⚠️ ناقص، ولا يؤثر لأن Google و Apple يستخدمان العنوان الإنجليزي |
| الموقع والبريد | لا يظهران | ❓ |

**لماذا بقيت Ash Sharqiyah؟** اخترنا Al Qassim في طلب الإنشاء وفي طلب التحديث، ومع ذلك رجعت القيمة نفسها مرتين. الأرجح أن نظام D&B يحدد المنطقة تلقائياً من العنوان. هذا استنتاج منّا، وD&B لم تؤكده.

**هل تؤثر على Google؟** لا. نموذج العنوان السعودي عند Google ليس فيه خانة منطقة، وGoogle جلب من D&B الاسم والعنوان والمدينة والرمز البريدي فقط. **لكنها تؤثر على Apple**، لأن بريد D&B يطلب إدخال البيانات في Apple كما هي، وفيها State.

## الرد على D&B لتصحيح المنطقة

اضغط **Reply** على بريد «DUNS Number Update Completed» نفسه، واترك العنوان كما هو حتى يرتبط بالحالة. أرفق `Madar-alTamkeen-National-Address-Proof.png` و `Madar-alTamkeen-CR-Details-English.pdf`.

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

إذا لم يردوا خلال 5 أيام عمل تقريباً، افتح نموذج التحديث وضع علامة على **Region / Territory** فقط. لا تعمل الاثنين معاً.

</div>
