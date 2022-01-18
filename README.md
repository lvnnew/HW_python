```py
Str = "Murrzik" #1) Создать переменную типа String
Int = 22 #2) Создать переменную типа Integer
Flt = 1.02 #3) Создать переменную типа Float
Bts = b"bytes" #4) Создать переменную типа Bytes
Lst = list('list') #5) Создать переменную типа List
Tpl = tuple('hello world') #6) Создать переменную типа Tuple
St = set('Murrzik') #7) Создать переменную типа Set
FrznSt = frozenset('Murrzik') #8) Создать переменную типа Frozen set
Dct = {'first': 1, 'second': 2} #9) Создать переменную типа Dict
# или Dct = dict(first = 1, second = 2)

#10) Вывести в консоль все выше перечисленные переменные с добавлением типа данных.
somelist = [Str, Int, Flt, Bts, Lst, Tpl, St, FrznSt, Dct]
for i in somelist:
    print(i, type(i))

#11) Создать 2 переменные String, создать переменную в которой сканкатенируете эти переменные. Вывести в консоль.
a = "Hello "
b = "world!"
c = a + b
print(c)

#12) Вывести в одну строку переменные типа String и Integer используя “,” (Запятую)
print(Str,Int,sep=',')

#13) Вывести в одну строку переменные типа String и Integer используя “+” (Плюс)
print(Str,Int,sep='+')
```
