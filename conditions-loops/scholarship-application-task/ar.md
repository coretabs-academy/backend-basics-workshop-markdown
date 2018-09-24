## مالذي تعرفنا عليه ؟

تعرفنا على الأنواع الثلاثة في بايثون string, integer, boolean... ثم عرفنا كيفية عمل برنامج يقوم بالتحقق من الشروط وتشغيل الأوامر على أساسها.

لنقم بجمع الأفكار التي تعلمناها في برنامج بسيط.

## دولتك تريد عمل برنامج للمنح الطلابية

![launch](./assets/select.png =350x350)

تخيل معي أن دولتك تريد عمل برنامج للتقديم على المنح الطلابية للجامعات.

بحيث الطالب يجب أن يكون عمر بين 18 و 22 ليكون مؤهل للحصول على المنحة.

أي أنه يحصل على عمر المستخدم مما يدخله على input:

```python
age = input()
```

**لا تنسى** أن input ترجع لنا دائماً string, أي يجب عليك تحويلها إلى integer لعمل المقارنات (وللتحقق أن المستخدم أصلاً أدخل رقم).

سنقوم بتحويلها كما بالتالي:

```python
age = input()
age = int(age)
```

ثم يقوم بمقارنة العمر بين 18 و 22, ولدينا هذه الثلاث الأمثلة (لدولة مصر مثلاً):

1. عمر المستخدم 15 سيظهر له:

```
You are too young
```

2. عمر المستخدم 25 سيظهر له:

```
You are too old
```

3. عمر المستخدم 20 سيظهر له:

```
Welcome to Egypt scholarship program
```


بمعنى لدينا ثلاث خطوات :

1. الحصول على عمر المستخدم

2. تحويل عمر المستخدم إلى رقم integer

3. إظهار الرسالة المناسبة حسب عمر المستخدم المدخل

## كيفية تجربة الأكواد ؟

قبل أن تشارك حلك, قم بالتأكد بأن الكود يعمل أمامك من خلال بيئة العمل هذه:

<a href="https://coretabs.net/classroom/backend/أساسيات-البرمجة/الشروط/بيئة-العمل-مهمة-تطبيق-التقديم-على-المنح" style="display: block; width: 200px; background-color: #5355e8; background-image:linear-gradient(to left, #2d43e7, #9042e8); color:#fff; padding: 10px; margin: 30px auto; border-radius:100px; text-decoration: none; font-size: 18px; text-align: center;">بيئة العمل</a>


حاول بقدر ما تريد, ولا تنسى:

> ما يصنع منك محترف هو كثرة الأخطاء :wink:

## كيف تقوم بمشاركة الحلول ؟

بإمكانك مشاركة الحلول في مجتمع كورتابز على هذا الرابط:

<a href="https://forums.coretabs.net/t/مشاركة-حلول-عمل-تطبيق-للتقديم-على-المنح-scholarship-program/871" style="display: block; width: 200px; background-color: #5355e8; background-image:linear-gradient(to left, #2d43e7, #9042e8); color:#fff; padding: 10px; margin: 30px auto; border-radius:100px; text-decoration: none; font-size: 18px; text-align: center;">مشاركة الحل</a>