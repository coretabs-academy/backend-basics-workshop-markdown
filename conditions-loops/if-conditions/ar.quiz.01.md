^ مالذي سيطبعه البرنامج:

```
x = 'hello'

print('hola is Spanish')

if x == 'hello':
    print('hello equals hello !')

print('merhaba is Turkish')
```

* سيطبع

```
hola is Spanish
hello equals hello !
```

** سيطبع

```
hola is Spanish
hello equals hello !
merhaba is Turkish

```

$ حاول مرة أخرى أو قم بمراجعة الدرس السابق

-

^ مالذي سيطبعه البرنامج:

```
x = 100

if x > 50:
    print('It is larger than 50')
elif x < 500:
    print('It is smaller than 500')    
```

** ```It is larger than 50```

* ```It is smaller than 500```

* ```
It is larger than 50
It is smaller than 500
```

$ الشروط if و elif فقط منهما سيتحقق بالترتيب

-

^ مالذي سيطبعه البرنامج:

```
x = 100

if x > 50:
    print('It is larger than 50')

if x < 500:
    print('It is smaller than 500')    
```

* ```It is larger than 50```

* ```It is smaller than 500```

** ```
It is larger than 50
It is smaller than 500
```

$ الشروط if و if كلاهما سيتحققان

-


^ ماهي قيمة x:

```
x = 100

if x > 50:
    x = x * 5

if x < 500:
    x = 77   
```

* 77

** 500

* 100

$ x ليست أصغر من 500 ولكنها (أصغر أو تساوي 500)