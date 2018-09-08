^ مالذي سيطبعه البرنامج:

```python
def func():
    print('hello')
```

* سيطبع

```
hello
```

** لن يطبع شيء

$ لم يتم استدعاء الدالة... فقط تعريفها موجود

-

^ مالذي سيطبعه البرنامج التالي:

```python
func():
    print('hello')

func()
```

* سيطبع

```
hello
```

** تحصل مشكلة SyntaxError بسبب عدم وجود def

$ تحتاج الدالة لتعريفها لاستعمال def قبل اسم الدالة

-

^ مالذي سيطبعه البرنامج التالي:

```python
def func():
    print('hello')

func()
func()
```

* سيطبع

```
hello
```

** سيطبع

```
hello
hello
```

* تحصل مشكلة SyntaxError بسبب عدم وجود def

$ يمكن استدعاء الدالة أكثر من مرة

-

^ مالذي سيطبعه البرنامج التالي:

```python
def check_age(age):
    if age > 18
        print("You're allowed to enter")

check_age(30)
check_age(5)
check_age(20)
```

* لن يطبع شيء

** سيطبع

```
You're allowed to enter
You're allowed to enter
```

$ حاول مرة أخرى أو راجع الدرس السابق