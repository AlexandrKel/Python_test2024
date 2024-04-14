# Python_test2024
Python_test2024
print('hello, world!') #=>Hello, world!
print('Motherof Dragons.')
print('Dracarys!')
print('Mother of Dragons.'); print('Dracaris!')
print('Robert'); print('Stannis');print('Renly')

# + - | * || ** % -операрторы
# 1 2 3 4 5 6 7 8 9 - операнды
# бинарные требуют наличие двух операндов

print(-3) # унарные позволяют наличие одного операндо (оператор с операндом)


# тернарные с тремя операндоми


#"-" выяитание
#"*" умножение
#"**" возвдение в степень
#"/" деление
#"//" целочисленное деление
#"%" остаток от деления




print(3+4)  #=>7
print(9/3)
print(8/2)
print(3*2)
print(3**2)
print(9%2)

print(3+2=2+3) #коммутативный закон (от перемены мест слагаемых сумма не меняется) 
#2-3 не равно 3-2 коммутативный зкаон работает только при сложениии 


print(2 * 4 * 5 * 10) #приоритет операций

print (2 + 2 * 2)
print (2 ** 3 * 2)
print (2 + 2) * 2
print (3 ** (4 - 2)) #=>9
print (7 * 3 (4 / 2) - (8 + (2 - 1))) #=>14

#было
print (8 / 2 + 5 -- 3 / 2) #=>10.5
#стало
print (((8 / 2) + 5) - (-3 / 2)) #=>10.5

print (3**5)
print(-8/-4)
print(100%3)
print(3**5+(-8/-4+(100%3)))

#стандарт кодирования в Python - PEP8
#линтератор - проверяет код на соответствие стандартам fklake8

#КАВЫЧКИ

print("Dracarys!")

print("Dragon's mother")

#экранируем кавычки вокруг "No", чтобы интепритатор распознал их как часть строки
print("Dragon's mother said \"No\"")
#=>Dragon's mother said "No"

print("\\")
#=>\

#ЭКРАНИРОВАННЫЕ ПОСЛЕДОВАТЕЛЬНОСТИ

print("-Are you hungry?- Aaaarrrgh!")
#=> -Are you hungry? - Aaaarrrgh!

print("-Are you hungry?\n- Aaaarrrgh!") #\n-escape sequence (пример экранированной последовательности)
#=> -Are you hungry?
#=> - Aaaarrrgh!

#LF LINE FEED
#\t табуляция
#\r возврат каретки

print("Gregor Clegane\nDunsen\nPolliver\nchiswyck")

print('Gregor Clegane')# строка с текстом
print("\n")# строка с невидимыми символами перевода строки
print('Dunsen')#строка с текстом

print("Joffrey loves using \\n")
#=>Joffrey loves using \n

#25.03.2024 Конкатенация Conkatinate

#оператор такой же, как и при сложении чисел
#но здесь он имеет другой смысл (семантику)
print('Dragon'+"stone") #=> Dragonstone

print('Kings'+'wood') #=>Kingswood

print('Kings'+'road') #=>Kingsroad

print("Kings's" + 'Landing') # => King'sLanding

#пробел - сколько поставите с какой стороны, столько получите с той стороны

#Ставим пробел в левой части
print("King's " + "Landing")

# Ставим пробел в правой части
print("King's" + ' Landing')

print('- Did Joffrey agree?')
print('- He did. He also said "I love using \\n".')


#29.03.2024 ПЕРЕМЕННЫЕ

print('Father!')
print('Father!')

#greeting - переводится как "приветствие"
greeting=('Father!') #greeting (имя переменной) = оператор присваивания 'Father!' (значение)
print(greeting)
print(greeting)
#=> Father!
#=> Father!

# в имени переменной нельзя ставить цифру вначале

#регистр в Python имеет большое значение
print('hello')
print('HELLO')

greeting1 = 'Father!'
print(greeting1)
print(greeting1)

greeting2 = 'Mother!'
print(greeting2)
print(greeting2)

#greeting - переводится как "приветствие"
greeting = 'Father!'
print(greeting) #=> Father!

greeting = 'Mother!'
print(greeting) #=> Mother!

print(greeting)
greeting = 'Father!'

#КОНСТАНТЫ -название константы большими буквами с разделителем _

PI = 3.14
print(PI) #=>3.14

name1 = "Bill"
name2 = "James"
name1 = "Fill"
print(name1)

# password$ - неправильно символ $
# user_name - правильно
# 1first  - неправильно символ 1 в начале
# mother - правильно
# _hello - правильно

family = 'Targaryen'
# BEGIN (write your solution here)
# END
greeting = ('Dragon')

print('Targaryen')
print(' and ')
print(greeting)

#30.03.2024
#выражения в определениях

#сложные вычисления через переменную

dollars_count = 50 * 1.25 # выражения 62.5 и 50 * 1.25
print(dollars_count) #=> 62.5

#Python различает выражения (expressions) и инструкции (statements)

62.5
50 * 1.25
120 / 10 * 2
int('100')

'hello'
'Good' + 'will'

# if, while, for -примеры инструкций (производят и контролируют действия, но не превращают значения)

a = 42 # это инструкция (statment) 
a + 1 # a это выражение

# выражения могут сделать любые вычисления, не только математические, но и строковые, как конкатенация

who = "dragon's " + "mother"
print(who)

rubles_per_dollar = 60
dollars_count = 50 * 1.25 # 62.5
rubles_count = dollars_count * rubles_per_dollar # 3750,0

print(rubles_count)

rubles_per_dollar = 60
dollars_count = 50 * 1.25 #62.5
rubles_count = dollars_count * rubles_per_dollar #3750.0

#функция str() превращает число в строку.
# 0 таких превращениях будет отдельный урок.

print('The price is ' + str(rubles_count) + ' rubles')  #=> The price is 3750.0 rubles

#ПЕРЕМЕННЫЕ И КОНКАТЕНАЦИЯ

what = "Kings" + "road"
print(what) #=> Kingsroad

first = "Kings"
what = first + "road"

print(what) #=> Kingsroad

first = "Kings"
last = 'road'

what = first + last
print(what) # => Kingsroad

euros_count = 100
euros_per_dollar = 100 * 1.25
print(euros_per_dollar)
rubles_per_dollar = 60
rubles_count = euros_per_dollar * rubles_per_dollar # 3750,0
print(rubles_count)


euros_count = 100
# BEGIN (write your solution here)
# END
euros_per_dollar = 100 * 1.25
print(euros_per_dollar)
rubles_per_dollar = 60
rubles_count = euros_per_dollar * rubles_per_dollar # 7500,0
print(rubles_count)

#31.03.2024

#именование

x = 'Father'
print(x)

# именование переменных
# kebab-case соотавные части перемененой разделяются дефисом (my-super-var)
# snake_case для разделения используется подчеркивание (my_super_var)
# CamelCase  каждое слово в переменной пишется с заглавной буквы (MySuperVar)

#Магические числа MAGIC NUMBERS

euros_count = 1000
# BEGIN (write your solution here)
dollar_count = euros_count * 1.25 # 1250.0
rubles_count = dollar_count * 60 # 75000,0

print(rubles_count)

dollars_per_euro = 1.25
rubles_per_dollar = 60

euros_count = 1000
dollars_count = euros_count * dollars_per_euro # 1250.0
rubles_count = dollar_count * rubles_per_dollar # 75000,0

print(rubles_count)

#используется именование snake_case 
#две  новые переменные отделяются от последующих вычеслений пустой строчкой. код должен быть читабельным.

#вы столкнулись с таким кодомб который выводит на экран общее количество комнат во владении нынешнего короля.
# king = 'King Balon the 6 th'
# функция str() превращает число в строку 
# 0 таких превращениях  будет отдельный урок
# print(king + ' has ' + str(6*17) + ' rooms.')  => King Balon the 6th 102 rooms. 

name_king = 'King Balon 6th '

generation = 6 # every next generation + 1
number_of_rooms_for_one_generation = 17

print(name_king + ' has ' + str(generation * number_of_rooms_for_one_generation) + ' rooms.')  #=> King Balon the 6th 102 rooms. 

#05.04.2024 ИНТЕРПОЛЯЦИЯ

#конкатенация

first_name = 'Joffrey'
greeting = 'Hello'

print(greeting + ", " + first_name + "!") #=> Hello, Joffrey!

# альтернатива конкатенации - интерполяция (буква f указываетб что мы создаем f-строку)

first_name = 'Joffrey'
greeting = 'Hello'

print(f'{greeting}, {first_name}!') #=> Hello, Joffrey!

school = 'Hexlet'

what_is_it= f'{school} - online courses'
print(what_is_it) #=> Hexlet - online courses

#Multi-line строки

# перевод строки \n

text = 'Пример текста, \nсостоящего из \nнескольких строк'
print(text)

#multi-line строки

text = '''Пример текста,
состоящегго из
нескольких строк
'''

print(text)

#пустая строка в конце (можно убратьб если поставим закрытие ковычек в последней строке текста)

text = '''Пример текста,
состоящегго из
нескольких строк''' #благодаря тройным ковычкам multi-line строки позволяют не экранированть кавычки внутри строки (не нужно экранировать 'одинарные'  и "двойные" кавычки)

print(text)

#еще multi-line строки могут становиться f-строками для интерполяции

a = 'A'
b = 'B'

#Слева добавился f

text = f'''{a} и {b}
сидели на трубе
'''

print(text)

stark = 'Arya'

print(f'''{"Do you want to eat,"} {stark}?
{"Yes, I'm hungry, mom."}''')


#07.04.2024 Извлечение символов из строки

# Извлечение элемента по индексу 

first_name = 'Alexandr'

print(first_name[0]) #=> A

#длина строки 9б поэтому последний индекс - это 8

first_name = 'Alerxandr'

print(first_name[8]) #=> r

# print(first_name[9])
#---------------------------------------------------------------------------
#IndexError                                Traceback (most recent call last)
#<ipython-input-5-1886f12f2362> in <cell line: 7>()
#      5 print(first_name[8]) #=> r
#      6 
#----> 7 print(first_name[9])
#
#IndexError: string index out of range

magic = '\nyou'
print(magic) #=> you
print(magic[1])

#отрицательные индексы
#отрицательные индексы начинаются с -1 

first_name = 'Alexandr'

print(first_name[-1])

# индексом может быть не только число, но и значение переменной

first_name = 'Alexandr'
index = 0

print(first_name[index]) #=> A

name1 = "John"
name2 = "Tom"
name3 = "Emily"

print(name1[0] + name3[2] + name2[2])  #=> Jim

one = 'Naharis'
two = 'Mormont'
three = 'Sand'

text = f'''{one[2]}{two[1]}{three[3]}{two[4]}{two[2]}
'''

print(text)


#08.04.2024
#Срезы строк

#Подстрока ип срезы для строк
# Подстрока - это некоторая часть строки. которую нужно найти и извлечь.

# найдем год из даты

value = '12-08-2024'

print(value[6]) #=> 2
print(value[9]) #=> 4

print(value[6] + value[9]) #=> 24

value = '12-08-2024'

year = value [6:10]

print(year)  #=> 2024

# str[начальный индекс : конечный индекс]

#for example

value = '01-12-2023'

#Срез строки - это всегда строка, даже если внутри строки было число

value[1:2] # '1'

value[3:5] # '12'

# Срезы - механизм с большим количеством вариаций (если не указать вторую границу, то извлечение произойдет до конца строки, тоже самое с первой границей- началом строки)

value = 'Hexlet'

value[3:] # 'let'

value[:3] #=> 'Hex'

#также и с отрицательными индексами

value [3:-1] #'le'

value [-5:3] # 'ex'

# ШАГ извлечения (третий необязательный параметр извлечения), по умолчанию =1, но это можно изменить

value = 'Hexlet'
value[1:5:2] #el #1:5 -это 'exle', шаг 2 -значит через одинб то есть 'e' и 'l'

# можно комбинировать с открытыми границами, без указания начал и конца

value = 'Hexlet'
value[:5:2] # 'Hxe' # символы берутся от начала до 5 индекса через один

value = 'Hexlet'
value[1::2] # 'elt' # символы берутся от 1 индекса до конца через один

# ПЕРЕВОРОТ СТРОКИ - отрицательный шаг, он берется с конца

value = 'Hexlet' # пропускаем обе границы
value[::-1] # 'telxeH'

#  отрицательны шаг в случае со срезами извлекаются в обратном порядке. Превой указывается правая граница среза, второй левая.

value = 'Hexlet' #  символ с индексом 1 не будет включен в подстроку

value [4:1:-1] # 'elx'

# срезы можно указывать не только через числа. но и с использованием переменных

value = 'Hexlet'
begin =1 
end = 5

value[begin:end] # 'exle'

value = 'Hexlet'

value = 'Hexlet' # вся строка
value[::] # 'Hexlet'

value = 'Hexlet' # вся строка
value[:] # 'Hexlet'

value = 'Hexlet' # нечетные по порядку символы
value[::2] # 'Hxe'

value = 'Hexlet' # четные по порядку символы
value[1::2] # 'elt'

value = 'Hexlet' # вся строка в обратном порядке
value[::-1] # 'telxeH'

value = 'Hexlet' # Строка, начиная с шестого символа
value[5:] # 't'

value = 'Hexlet' # строка до шестого символа
value[:5] # 'Hexle'

value = 'Hexlet' # все символы с предпоследнего до третьего в обратнгом порядке
value[-2:1:-1] # 'elx'

text = 'Hexlet' # вывести 'xeH'
print(text[2::-1]) # 'xeH'

value = 'Hexlet' # вывести 'xle'
begin = 2 
end = 5

value[begin:end] # 'xle'

value = 'Hexlet' # вывести 'xle'


value [2:5] # 'xle'

value = 'Hexlet' # вывести 'xle'
begin = -4
end = 5

print(value[begin:end]) # 'xle'



#09.04.2024
# ТИПЫ ДАННЫХ

"hELLO, WORLD" #  строки
'1','-198','0' # целые числа

# тип данных определяет, что можно делать с эллементами конкретного множества информации.

# Примитивные типы данных

print(5) # => 5 в отличие от строк, числа заключаются в кавычки

print(1,34,-19) #целые числа

print(1.3,1.0,-14.324) # рациональные числа

print(10.324)

# line - строчка
# strings - строка

# Сильная типилизация -строгая типизация 

# PHP, JavaScript - слабая типизация

# // Как тебе такое, Илон Маск?
# // Число 1 + Строка 7 = Строка 17
# 1+'7';//'17'
# 
#  File "<ipython-input-8-d6f9ba084ba6>", line 6
#     // Число 1 + Строка 7 = Строка 17
#     ^
# SyntaxError: invalid syntax

# Неизменяемость примитивных типов  (ключевая причина - производительность)

# изменить символ в строке 'str'

# frist_name = 'Alexander'
# first_name[0] = 'B' 
# 
# NameError                                 Traceback (most recent call last)
# <ipython-input-13-a91784f3afba> in <cell line: 4>()
#       2 
#       3 frist_name = 'Alexander'
# ----> 4 first_name[0] = 'B'
# 
# NameError: name 'first_name' is not defined

first_name = 'Alexandr'
first_name = 'Blexandr'

print(first_name)

# примитивные типы в Python поменять нельзя, а составные можно. Также можно без проблем заменитьб значение переменной.

# Явное преобразование типов данных

# str станет int

number = int('345')

print(number)

value = '0' # внутри скобки можно указывать переменную

convered_value = int(value)

print(convered_value) #=> 0 

convered_value2 = int('10')

print(convered_value2) #=> 10 

convered_value3 = int(False)

print(convered_value3) #=> 0 

convered_value4 = int(True)

print(convered_value4) #=> 1 

# если перобразуется число с плавающей точкойб то отбрасывается вся дробная часть

convered_value5 = int(3.5)

print(convered_value5) #=> 3

# точно так же можно преобразовать данные в строки str() и число с плавающей точкой float()

value = str(10)
print(value) #=> 10

value2 = str(True)
print(value2) #=> 'True'

value3 = float(5)
print(value3) #=> 5.0

# где встречаются одновременнно целое число и число с плавающей точкой, Python автоматически все приводит к float - числу с плавающей точкой

value = 3 +1.2

print(value)  # => 4.2

0.2 + 0.1

print(0.2 + 0.1) #операции с плавающей точкой не точны по причине ограничений вычислительных мощностей

value = '2' 

# НЕИЗМЕНЯЕМОСТЬ И ПРИМИТИВНЫЕ ТИПЫ

# функция abs() делает число неотрицательным

balanse = - 200
amount = abs(balanse)

print(amount) #=> 200

print(balanse) # примитивные  типы (простые типы данных) в Python неизменыемы 

balance = -200
balance = abs(balance)

print(balance)

num = -55
print(abs(num))

value = "-42"

convered_value = int(value)
value = abs(convered_value)
print(value)


#11.04.2024
# ФУНКЦИИ И ИХ ВЫЗОВ 

# ФУНКЦИЯ len() считает длину той строки, которую ей передали.

result = len('Hello!') #=> result это переменная
print(result) #=> 6


# ФУНКЦИЯ pow() возводит указанное число в нужную стпепень.

result = pow(2, 3) #=> 2 * 2 * 2
print(result) #=> 8

#в коде программы определены две переменные, посчитайте их общую длину в символах и выведите на экран.

company1 = "Apple"
company2 = "Samsung"

value1 = len('company1')
value2 = len('company2') 

result = value1 + value2

print(result)

company1 = "Apple"
company2 = "Samsung"

result = len('company1') + len('company2')

print(result)

company1 = "Apple"
company2 = "Samsung"

value = len(company1) + len(company2)

print(value) #привильно

company1 = 'Apple'
company2 = 'Samsung'

value = len(company1) + len(company2)

print(value) # Apple (5 букв) + Samsung (7 букв)

convered_value = str(value)+' times'

print(convered_value) #=> 2 times


# 12.04.2024
# СИГНАТУРА ФУНКЦИИ

#pow(x, y[,z]) # возвращает x в степени y; если z присутствует, возвращает x в степень y

#функция round() округляет переданное ей число

result = round(10.25, 0) #10.0 (число которое нужно округлить и точно округления)

print(result)

result = round(10.25, 1)

print(result) #10.2

result = round(10.25, 2)

print(result) #10.25

result = abs(-20)

print(result)

num1 = 10
num2 = -13

value = abs(num1 + -13)

print(value)


#13.04.2024

# ВЫЗОВ ФУНКЦИИ - ВЫРАЖЕНИЕ

# Что принимается за выражение

1 + 5 * 3

'He' + 'Let'

# переменные могут быть частью выражения

# rate * 5

sum = 1 + 5 # тут выражение - это 1 + 5
print(1 + 5)

print(sum)

# бессмысленный кодб который не работает
# 10 + sum = 1 + 5

# можно ли сччитать вызов функции выражением

name = 'python'
#индексы начинаются с нуля
#Вызов функции и вычитание вместе

last_index = len(name) - 1

print(last_index) #=> 5

name = 'python'
#используется интерполяция

print(f'Последний символ: {name[len(name) - 1]}') # = > 'Последний символ: n'

def get_one():
  return 1

print(get_one)

#result = sum_(sum_(1, 3), sum_(sum_(4, 2), 3))
#
#print(result) # =>13

hex(10) # => 0xa


number = 10.1234 # => 0xa
number_hex = int(round(number, 0)) #10.0 (число которое нужно округлить и точно округления)
hex(number_hex)
print(number_hex)

#number = 10.1234
#
#hex('number')
#
#print(hex)

number = 10.1234 # => 0xa
number_hex = int(round(number, 0)) #10.0 (число которое нужно округлить и точно округления)
hex(number_hex)
print(number_hex)

#number = 10.1234
#
#hex('number')
#
#print(hex)


number = 10.1234
hex_string = hex(int(number))

print(hex_string)  # 0xa
