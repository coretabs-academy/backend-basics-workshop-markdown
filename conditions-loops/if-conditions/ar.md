## كيف تكتب شرط ؟

```python
if condition:
    statements
```

* مكان condition تكتب قيمة منطقية boolean إما True أو False, مثل `name == 'Yaser'`.
* مكان statments تكتب جميع الأسطر التي تريد تنفيذها.

## مدخلات المستخدم user input

بإمكانك جلب ما يدخله المستخدم باستعمال `input()` ثم تخزين القيمة الراجعة منها في متغير مثل:

```python
name = input()
```

## بإمكانك استعمال elif أكثر من مرة

بإمكانك كتابة أكثر من شرط باستعمال elif (أو إذا) مثلاً:

```python
name = input()

if name == 'Yaser':
    print('Hello Yaser')
elif name == 'Ahmed':
    print('get out')
elif name == 'Mohammed':
    print('No Mohammed you cant enter')
elif name == 'Omar':
    print('Hi Omar')
```