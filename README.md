```py
aa = "Murrzik" #1) Создать переменную типа String
bb = 22 #2) Создать переменную типа Integer
cc = 1.02 #3) Создать переменную типа Float
dd = bytes(8) #4) Создать переменную типа Bytes
ee = list('list') #5) Создать переменную типа List
ff = tuple('hello world') #6) Создать переменную типа Tuple
gg = set('Murrzik') #7) Создать переменную типа Set
hh = frozenset('Murrzik') #8) Создать переменную типа Frozen set
ii = {'first': 1, 'second': 2} #9) Создать переменную типа Dict
# или Dct = dict(first = 1, second = 2)

#10) Вывести в консоль все выше перечисленные переменные с добавлением типа данных.
# Большое спасибо, за подсказку, одному очень доброму человеку!)
somelist = [aa, bb, cc, dd, ee, ff, gg, hh, ii]
for i in somelist:
    print(i, type(i))

#11) Создать 2 переменные String, создать переменную в которой сканкатенируете эти переменные. Вывести в консоль.
a = "Hello "
b = "world!"
c = a + b
print(c)

#12) Вывести в одну строку переменные типа String и Integer используя “,” (Запятую)
print(aa,bb,sep=',')

#13) Вывести в одну строку переменные типа String и Integer используя “+” (Плюс)
print(aa,bb,sep='+')
```
