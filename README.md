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


 print "YES"

 # Детерменированная функция

len = ('hexlet') # 6
print(len)

len = ('wow') # 6
print(len)

from random import random

random( ) # функция random( ) возвращает случайное число

random( )

print(random() * 10)

print(random() * 10)

from random import randint

import random

print(random.randint(1, 10))

randint(1,10)
print(random.randint)

random.randint(1, 10)

from random import randint

print(random.randint(1, 10))

from random import randint
print(random.randint(1, 10))

from random import randint
r1 = random.randint(0, 10)
print("Random number between 0 and 10 is % s" % (r1))

beg,end=1,1000
for i in range(5):
    print(random.randint(beg, end))



# importing randint function
# from random module
from random import randint
 
# Function which generates a new 
# random number everytime it executes
def generator():
    return randint(1, 10)
     
# Function takes user input and returns
# true or false depending whether the
# user wins the lucky draw!
def rand_guess():
 
    # calls generator() which returns a
    # random integer between 1 and 10
    random_number = generator()
     
    # defining the number of
    # guesses the user gets
    guess_left = 3
 
    # Setting a flag variable to check
    # the win-condition for user
    flag = 0
 
    # looping the number of times
    # the user gets chances
    while guess_left > 0:
 
        # Taking a input from the user
        guess = int(input("Pick your number to "
                    "enter the lucky draw\n"))
 
        # checking whether user's guess
        # matches the generated win-condition
        if guess == random_number:
 
            # setting flag as 1 if user guesses 
            # correctly and then loop is broken
            flag = 1
            break
         
        else:
             
            # If user's choice doesn't match
            # win-condition then it is printed
            print("Wrong Guess!!")
 
        # Decrementing number of 
        # guesses left by 1 
        guess_left -= 1
 
    # If win-condition is satisfied then,
    # the function rand_guess returns True
    if flag is 1:
        return True
 
    # Else the function returns False
    else:
        return False
 
# Driver code
if __name__ == '__main__':
    if rand_guess() is True:
        print("Congrats!! You Win.")

#15.04.2024

print("Hello world")

# Addition Метод add добавляет элементы в множество. Если элемент уже есть в множестве, то он не дублируется и множество остается в исходном состоянии.

num1 = float(input("Enter first number: ")) #float -предоставляет возможность преобразования объекта в число с плавающей точкой (дробными числами или операции, требующие точности до десятичных знаков.
num2 = float(input("Enter second number: ")) #input() , функция которая возвращает в программу введённую пользователем строку.
sum_result = num1 + num2

print(f"sum: {num1} + {num2} = {sum_result}")

# Division - выполняет целочисленное деление над значениями

num3 = float(input("Enter the divided for division")) # divide - деление с остатком — самая простая для понимания операция деления в Python
num4 = float(input("Enter the divisor for division:")) #divisor for division
if num4 == 0:
  print("error: Division by zero is not allowed. ")
else: 
  div_result = num3 / num4

  print(f"Division: {num3} / {num4} = {div_result}")

  # Обычное деление

print(5 / 2) # 2.5 

print(int(5) / int(2)) # 2.5

print(1 / 3) # 0.3333333333333333

# Деление без остатка

print(5 // 2) # 2

print(5 // 2.0) # 2.0

print(5 // int(2.0)) # 2

print(int((5.0) // 2)) # 2

# Как найти остаток или деление по модулю

print(10 % 3) # 1

def is_even(number):
    # Если остаток от деления на 2 равен нулю, то число чётное
    if number % 2 == 0:
        print('Число чётное')
    else:
        print('Число нечётное')

is_even(12) # Число чётное
is_even(13) # Число нечётное

# Деление на ноль

a = 10
b = 0

try:
    result = a / b
except ZeroDivisionError:
    print("Делить на ноль нельзя!")
else:
    print(result)

    # Сокращённая запись

a = 10
a = a // 2 # В итоге в переменной a будет храниться число 5

print(a)

a = 10
a //= 2 # В этом случае в переменной a тоже будет число 5

print(a)
    else :
        print("Sorry, You Lost!")
      

#16.04.2024

# Write program to find the area of a triangle // Напишите программу для нахождения площади треугольника 

# Input the base and height from the user
base = float(input("Enter the length of the base of the triangle: "))
height = float(input("Enter the height of the triangle: "))

area = 0.5 * base * height # Calculate the area of the triangle 

print(f"The area of the triangle is: {area} ") # display the result

# Write program to swap two variables // Напишите программу, чтобы поменять местами две переменные


a = input("Enter the value of the first variable (a): ") # input two variables
b = input("Enter the value of the first variable (b): ")

print(f"Original values: a = {a}, b = {b}") # display the original values

# swap the values using a temporary variable

temp = a
a = b
b = temp

print(f"Swapped values: a = {a}, b = {b}") # display the swapped values


#17.04.2024

# Write program to generate a random number

import random
print(f"Random number: {random.randint(1, 100)}")

# Write program to convert kilometers to miles

kilometers = float(input("Enter distance in kilometers: ")) 
conversation_factor = 0.621371 # Conversation factor: 1 kilometer = 0.621371 miles

miles = kilometers * conversation_factor

print(f"{kilometers} kilometers is equal to {miles} miles")

# Write program to convert Celsius to Farenheit

Celsius = float(input("Enter temperature in Celsius: ")) 
fahrenheit = (Celsius * 9/5) + 32 # Conversation formula: Fahrenheit = (Celsius * 9/5) + 32

print(f"{Celsius} degrees Celsius is equal to {fahrenheit} degrees Fahrenheit")

# 18.04.2024
# write program to display calendar

import calendar

year = int(input("Enter year: "))
month = int(input("Enter month: "))

cal = calendar.month(year, month)

print(cal)

# Write program to solve quadratic equation // Напишите программу для решения квадратного уравнения 

#         the standart form of a quadratic equation is:
#         ax² + bx + c = 0
#           where
#         a, b and c real numbers
#         a ≠ 0
#         the solutions of this quadratic equation is given by:

#        ( -b ±(b¹/² - 4ac)²)/(2a)  

import math

# input coefficients
a = float(input("Enter coefficients a: "))
b = float(input("Enter coefficients b: "))
c = float(input("Enter coefficients c: "))

discriminant = b**2 - 4*a*c # calculate the discriminant

# Check if the discriminant is positive, negative, or zero

if discriminant > 0:
  # two real and distinct roots
  root1 = (-b + math.sqrt(discriminant)) / (2*a)
  root2 = (-b - math.sqrt(discriminant)) / (2*a)
  print(f"Root 1: {root1}")
  print(f"Root 2: {root2}")
elif discriminant == 0:
  # one real root (repeated)
  root = -b / (2-a)
  print(f"Root: {root}")
else:
  #complex roots
  real_part = -b / (2*a)
  imaginary_part = math.sqrt(abs(discriminant)) / (2*a)

  # 20.04.2024

# write program to swap two variables without temp variable // Напишите программу для замены двух переменных без временной переменной

a = 5
b = 10

a, b = b, a # swapping without a tyemporary variable // Замена без временной переменной

print("After swapping")
print("a=", a)
print("b", b)

# write program to cheak if a number is Positive, Negative or Zero //написать программу для проверки, является ли число положительным, отрицательным или нулевым


num = float(input("Enter a number"))

if num > 0:
  print("Positive number")
elif num == 0:
  print("Zero")
else:
  print("NHegative number")

  # write program to cheack if a Number is Add or Even // напишите программу для проверки того, является ли число четным или нечетным

num = int(input("Enter a number"))

if num%2 ==0:
  print("This is a even number")
else:
  print("This is a odd number")

# Write program to cheack Leap Year

year = int(input("Enter a year: "))
# divided by 100 means century tear (ending with 00) # деленное на 100 означает столетний разрыв (заканчивается на 00)
# century year divided by 400 is leap year # Вековой год, деленный на 400, является високосным 

if (year % 400 == 0) and (year % 100 == 0):
  print("{0} is not leap year".format(year))

# if not divided by both 400 (century year) and 4 (not century year) 
# year is not Leap year

else:
  print("{0} is a leap year".format(year))

  print(f"Root1: {real_part} + {imaginary_part}i")
  print(f"Root2: {real_part} - {imaginary_part}i")

# 21.04.2024

# write program to check prime number # написать программу для проверки простого числа 

# Prime number # простое число 

# A prime number is a whole number that cannot be venly divided by any other number # Простое число - это целое число, которое не может #делиться на любое другое число 
# except for 1 and itself. For example,  2,3,5,7,11 and 13 are prime number because they #кроме 1 и самого себя. Например, 2, 3, 5, 7, 11 и 13 #являются простыми числами, потому что они
# cannot be divided by any other positive integer except for 1 and their own value # не может делиться ни на какое другое целое положительное #число, кроме 1 и собственного значения

num =  int(input("Enter a number: "))

flag = False #Define a flag variable

if num == 1:
  print(f"{num}, is not a prime number")
elif num > 1: # check for factors
  for i in range (2, num):
    if (num % i) == 0:
      flag = True  # if factor is found, set flag True
      break # break out of Loop

  # check if flag is True
  if flag:
    print(f"{num}, is not a prime number")
  else:
    print(f"{num}, is a prime number")

# write program to print all prime numbers in an interval of 1-10

#przyklad_1

def liczba_pierwsza(x):
    if x==2:
        return True
    if x%2 ==0 or x<=1:
        return False
    perw=int (x**0.5)+1
    
    for i in range (3, perw, 2):
        if x%i ==0:
            return False
    return True

def liczby_mniejsze (y):
    list_ = []
    for i in range(1,y+1):
        if liczba_pierwsza(i):
            list_.append(i)

    return list_

liczby_mniejsze (10)

#przyklad_2
def liczba_pierwsza_2 (x):

    for num in range(2,x):
        for i in range(2,num):
        
            if (num%i==0):
                break
        else:
            print(num)
            
liczba_pierwsza_2 (10)

def prime_number (x):

   for num in range(2,x):
        for i in range(2,num):
        
            if (num%i==0):
                break
        else:
            print(num)
            
prime_number(10)

# Python program to display all the prime numbers within an interval

lower = 1
upper = 10

print("Pirme numbers between", lower, "and" , upper, "are:")

for num in range (lower, upper + 1):   # all prime numbers are greater than 1 # все простые числа больше 1
  if num > 1:
    for i in range (2, num):
      if (num % i) == 0:
        break

      else:
        print(num)


# write program to find the Factorial of a Number # Программа для нахождения факториала числа

num = int(input("Enter a number: "))
factorial = 1

if num < 0:
  print("Factorial does not exist fot negative numbers") #Факториал не существует для отрицательных чисел
elif num == 0:
  print("Factorial of 0 is 1") # Факториал 0 равен 1
else: 
  for i in range(1, num +1 ):
    factorial = factorial * i
  print(f'The factorial of {num} is {factorial}')

  # Replit - day 21

day = 21
temp = -15
weight = 190.432623

print(day + 3)
print(weight  * 2)
print(weight  / 2)

# find something around you in yuor life to represent an int and a float. put them in variables

age = 32

bitcoin = 0.00435


# 22.04.2024

# Write program to Display the multiplication Table #Напишите программу для отображения таблицы умножения

num = int(input("Display multiplication table of: "))

for i in range(1, 11):
  print(f"{num} X {i} = {num*i}")

# Write program to Display the multiplication Table #Напишите программу для отображения таблицы умножения

num = int(input("Display multiplication table of: "))

for i in range(1, 27):
  print(f"{num} X {i} = {num*i}")

# Write program to Print the Fibonacci sequence # Напишите программу для печати последовательности Фибоначчи 

# Fibonacci sequence # Последовательность Фибоначчи 
  # the Fibonacci sequence is a series of numbers where each number is the sum of the two precending ones, typical starting with 0 and 1,
  # and the next number is obtained by adding the privious two numbers. This pattern continues indefinitely, generating a sequence that looks like this:
  # 
  # Последовательность Фибоначчи - это ряд чисел, в котором каждое число является суммой двух предыдущих, обычно начинающихся с 0 и 1,
  # и следующее число получается путем сложения двух предыдущих чисел. Эта схема продолжается бесконечно, создавая последовательность, которая выглядит следующим образом:
  #
  # 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144 and so on
  #
  # Matematically , the Fibonacci sequence can be defined using following recurrence relation: 
  #Математически последовательность Фибоначчи можно определить с помощью следующего рекуррентного соотношения: 
  #
  #       F(0) = 0 F(1) = 1 F(n) =F(n - 1) + F(n - 2)f orn >1


nterms = int(input("How many terms? "))
n1, n2 =0, 1  # first two terms
count = 0
#check if the number of terms is valid
if nterms <=0:
  print("Please enter a positive integer") #if there is only one term, return n1
elif nterms == 1:
  print("Fibonacci sequence upto", nterms, ":")
  print(n1)
#generate Fibonacci sequence 
else:
  print("Fibonacci sequence:")
  while count < nterms:
      print(n1)
      nth = n1 + n2
      # update values
      n1 = n2
      n2 = nth
      count += 1

def Fibonaci(fbncc):
    fib1 = 0
    fib2 = 1

    for i in range(fbncc):
        fib1, fib2 = fib2, fib1 + fib2

# 23.04.2024

# Write a programm to Check Armstrong number # Напишите программу для проверки номера Armstrong

# Armstrong number
#it is number that is equal to the sum of its own digits, each raised to a power equal to the number of digits in the number.
#это число, которое равно сумме своих цифр, каждая из которых возведена в степень, равную количеству цифр в числе.
#
#     for example, let's consider the number 153:
#   it has three digits (1,5 and 3)
#   if we calculate 1^{3}+5^{3}+3^{3}, we get 1 + 125 + 27, which is equal to 153
#
#so, 153 is an Armstrong number because it equals the sum of it's digits raised to the power of the number of digits in the number
#
#Another example is 9474:
#   it has four digits (9, 4, 7 , asnd 4)
#   if we calculate 9^{4}+4^{4}+7^{4}+4^{4}, we get 6561 + 256 + 2401 +256, which is also equal to 9474.
#
# therefore, 9474 is an Armstrong number as well
#

# example 1
num = int(input("enter a number: "))

#calculate the number of digits in num
num_str = str(num)
num_digits = len(num_str)

# Initialize variables
sum_of_powers = 0
temp_num = num

# calculate the sum of digits raised to the power of num digits

while temp_num > 0:
  digit = temp_num % 10
  sum_of_powers += digit ** num_digits
  temp_num //= 10

# check if if's an Armstrong number
if sum_of_powers == num:
  print(f"{num} is an Armstrong number.")
else:
  print(f"{num} is not Armstrong number.")


# example 2

def is_armstrong(num):

    # Step 2

    num_str = str(num)
    num_digits = len(num_str)

    # Step 3

    sum_of_powers = sum(int(digit)**num_digits for digit in num_str)

    # Step 4

    return sum_of_powers == num

# Example usage

number_to_check = 9474
result = is_armstrong(number_to_check)

if result:
    print(f"{number_to_check} is an Armstrong number.")

else:
    print(f"{number_to_check} is not an Armstrong number.")

# example 3

# Python program to determine whether
# the number is Armstrong number or not
 
# Function to calculate x raised to 
# the power y
def power(x, y):
     
    if y == 0:
        return 1
    if y % 2 == 0:
        return power(x, y // 2) * power(x, y // 2)
         
    return x * power(x, y // 2) * power(x, y // 2)

# Function to calculate order of the number
def order(x):
 
    # Variable to store of the number
    n = 0
    while (x != 0):
        n = n + 1
        x = x // 10
         
    return n

# Function to check whether the given 
# number is Armstrong number or not
def isArmstrong(x):
     
    n = order(x)
    temp = x
    sum1 = 0
     
    while (temp != 0):
        r = temp % 10
        sum1 = sum1 + power(r, n)
        temp = temp // 10
 
    # If condition satisfies
    return (sum1 == x)
 
# Driver code
x = 153
print(isArmstrong(x))
 
x = 1253
print(isArmstrong(x))

# example 4

# python 3 program
# to check whether the given number is armstrong or not
# without using power function
 
n = 153  # or n=int(input()) -> taking input from user
s = n  # assigning input value to the s variable
b = len(str(n))
sum1 = 0
while n != 0:
    r = n % 10
    sum1 = sum1+(r**b)
    n = n//10
if s == sum1:
    print("The given number", s, "is armstrong number")
else:
    print("The given number", s, "is not armstrong number")
 
# This code is contributed by Gangarajula Laxmi

    return fib1

Fibonaci(10)


# 24.04.2024

    #To find an Armstrong number python in an interval, we can take the help of two Python concepts, include:
    #
    #if-else statements
    #The while loop
    #An Armstrong number is a positive integer that has a base of n such that:
    #
    #PQR= P^n+Q^n+R^n
    #
    #From the above equation, we can derive that an Armstrong number is a number whose sum of individual digits to the power of n is equal to the original number itself. 


    #Чтобы найти число Армстронга python в интервале, мы можем воспользоваться двумя концепциями Python, включая:
    #
    #операторы if-else
    #цикл while
    #Число Армстронга - это целое положительное число с основанием n, такое, что:
    #
    #PQR= P^n+Q^n+R^n
    #
    #Из приведенного выше уравнения можно сделать вывод, что число Армстронга - это число, сумма отдельных цифр которого в степени n равна самому исходному числу. 



# write a Program to find Armstrong number in an interval # Напишите программу для нахождения числа Армстронга в интервале

# input the interval from the user #ввод интервала от пользователя

lower = int(input("Enter the lower limit of the intervval: "))
upper = int(input("Enter the upper limit of the intervval: "))

for num in range (lower, upper + 1): #iterate through the numbers # перебирайте числа
  order = len(str(num)) # find the number of digits in 'num' # найдите количество цифр в числе 'num'
  temp_num = num
  sum = 0

  while temp_num > 0:
    digit = temp_num % 10
    sum += digit ** order
    temp_num //= 10

  # check if 'num' is Armstrong number # проверить, является ли 'num' числом Армстронга
  if num ==sum:
    print(num)

# example 2

lower = 100
upper = 2000

for num in range(lower, upper + 1):

   # order of number
   order = len(str(num))
    
   # initialize sum
   sum = 0

   temp = num
   while temp > 0:
       digit = temp % 10
       sum += digit ** order
       temp //= 10

   if num == sum:
       print(num)


# 25.04.2024

# Wirte program to Find the Sum of Natural Numbers

# Natural numbers are a set of positive integers that are used to count and order objects.
# They are the numbers that typical start from 1 and continue indefinitely, including all the whole numbers greater than 0.
#In mathematical notation, the ste of natural numbers is often denoted as "N" and can be expressed as:
#
#         N = 1,2,3,4,5,6,7,8,9...
#
# Натуральные числа - это набор целых положительных чисел, которые используются для подсчета и упорядочивания объектов.
# Это числа, которые типично начинаются с 1 и продолжаются бесконечно, включая все целые числа, большие 0.
# В математической нотации множество натуральных чисел часто обозначается как "N" и может быть выражено как:
#


limit = int(input("Enter the limit: "))

sum = 0 # initialize the sum

# use a for loop to calculate the sum of natural numbers # используйте цикл for для вычисления суммы натуральных чисел

for i in range(1, limit +1):
  sum += i

  #print the sum
  print ("The sum of natural numbers up to", limit, "is:", sum)

  limit = int(input("Enter the limit: "))

sum = 0 # initialize the sum

# use a for loop to calculate the sum of natural numbers # используйте цикл for для вычисления суммы натуральных чисел

for i in range(2, limit +1):
  sum += i

  #print the sum
  print ("The sum of natural numbers up to", limit, "is:", sum)

  limit = int(input("Enter the limit: "))

sum = 0 # initialize the sum

# use a for loop to calculate the sum of natural numbers # используйте цикл for для вычисления суммы натуральных чисел

for i in range(3, limit +1):
  sum += i

  #print the sum
  print ("The sum of natural numbers up to", limit, "is:", sum)

  # Sum of natural numbers up to num

num = 16

if num < 0:
   print("Enter a positive number")
else:
   sum = 0
   # use while loop to iterate until zero
   while(num > 0):
       sum += num
       num -= 1
   print("The sum is", sum)

   n = int(input("Enter a number: "))
i = 1
while i<n:
    print(i)
    i = i + 1

    n = int(input("enter a number: "))
i = 1
sum = 0
while (i <= n):
    sum = sum + i
    i = i + 1
print("The sum is: ", sum)

num = 20
sum_of_numbers = 0
while(num > 0):
    sum_of_numbers += num
    num -= 1
print("The sum is", sum_of_numbers)

def natural(n):
    sumOfn = (n * (n + 1))/2

terms = int(input("Enter number of terms: "))
natural(terms)

if terms < 0:
  print("Enter a positive number: ")
else:
  totalSum = 0
while (terms > 0):
    totalSum += terms
    terms -= 1
    print ("The sum is" , totalSum)

num = int(input('Enter the number : '))
sum = 0
while 0<num:
    sum += num
    num -= 1
print(f'The sum of the number is {sum}')


# 27.04.2024

# write a program to find LCM (least Common Multiplane)
#
#LCM is the smallest multiple that is exactly divisible by two or more numbers
# 
#       {lcm} (a,b)={\frac {|ab|}{\gcd(a,b)}}.} 
#
# for more than two numbers, you can find the LCM step by step, talking the LCM of pairs of numbers at a time until you reach the last pair.
#
# Note: GCD stands for Greatest Common Divisor
#
#
# написать программу для нахождения LCM (наименьшего общего мультиплана)
# LCM - наименьшее кратное, которое в точности делится на два или более чисел.
# Для более чем двух чисел вы можете находить LCM шаг за шагом, по очереди называя LCM пар чисел, пока не дойдете до последней пары.
#   Примечание: GCD означает наибольший общий делитель.
#

    #EXAMPLE 1
# Python Program to find the L.C.M. of two number

def compute_lcm(x, y):
  if x > y:
    greater = x
  else:
    greater = y
  while(True):
    if((greater % x == 0) and (greater % y == 0)):
      lcm = greater
      break
    greater += 1
  return lcm

nym1 = int(input('Enter the number: '))
nym2 = int(input('Enter the number: '))

print("The L.C.M. is", compute_lcm(num1, num2))


  #EXAMPLE 2

def LCM(a, b):
    greater = max(a, b)
    smallest = min(a, b)
    for i in range(greater, a*b+1, greater):
        if i % smallest == 0:
            return i

# Driver program to test above function
if __name__ == '__main__':
    a = 54
    b = 24
    print("LCM of", a, "and", b, "is", LCM(a, b))

  #EXAMPLE 3

import math

def lcm_using_gcd(a, b):
    gcd = math.gcd(a, b)
    lcm = (a * b) // gcd
    return lcm

# Example usage:
num1 = 54
num2 = 24
print("LCM of", num1, "and", num2, "is:", lcm_using_gcd(num1, num2))

  #EXAMPLE 4

def prime_factors(n):
    factors = []
    divisor = 2
    while n > 1:
        while n % divisor == 0:
            factors.append(divisor)
            n //= divisor
        divisor += 1
    return factors

def lcm_using_prime_factors(a, b):
    factors_a = prime_factors(a)
    factors_b = prime_factors(b)
    lcm = 1
    for factor in set(factors_a + factors_b):
        lcm *= factor ** max(factors_a.count(factor), factors_b.count(factor))
    return lcm

# Example usage:
num1 = 54
num2 = 24
print("LCM of", num1, "and", num2, "is:", lcm_using_prime_factors(num1, num2))


# 28.04.2024

# write program to find Highest Common Factor # Наибольший общий фактор

# HCF is the largest positive integer that divides two or more numbers withiut leaving a remainder
# Formula: for two numbers a and b,  the HCF can be found using the formula:
# 
#           HCF(a,b) = GCD(a,b)
# 
# for more than two numbers, you can find the HCF by taking the GCD of pairs of numbers at a time until you reach the last pair.
# 
#  HCF - это наибольшее положительное целое число, которое делит два или более чисел без остатка.
#   Формула: для двух чисел a и b можно найти HCF по формуле:
# 
# Для более чем двух чисел вы можете найти HCF, взяв GCD пар чисел за один раз, пока не дойдете до последней пары.
# 


# Python program to find H.C.F. of two numbers

def compute_hcf(x,y): #define a function

# choose the smaller number
  if x > y:
    smaller = y
  else:
    smaller = x
  for i in range(1, smaller+1):
    if((x % i == 0) and (y % i == 0)):
      hcf = i
  return hcf

num1 = int(input('Enter the number: '))
num2 = int(input('Enter the number: '))

print("The H.C.F. is", compute_hcf(num1, num2))

#example 2

# Python code to demonstrate naive
# method to compute gcd ( recursion )
 
def hcfnaive(a, b):
    if(b == 0):
        return abs(a)
    else:
        return hcfnaive(b, a % b)
 
a = 54
b = 24
 
# prints 12
print("The gcd of 54 and 24 is : ", end="")
print(hcfnaive(54, 24))

# example 3
# Python code to demonstrate naive
# method to compute gcd ( Loops )
 
def computeGCD(x, y):
 
    if x > y:
        small = y
    else:
        small = x
    for i in range(1, small + 1):
        if((x % i == 0) and (y % i == 0)):
            gcd = i
             
    return gcd
 
a = 54
b = 24
 
# prints 12
print ("The gcd of 54 and 24 is : ", end="")
print (computeGCD(54,24))

# example 4
# Python code to demonstrate naive
# method to compute gcd ( Euclidean algo )
 
 
def computeGCD(x, y):
    while(y):
       x, y = y, x % y
    return abs(x)
 
a = 54
b = 24
 
# prints 12
print ("The gcd of 54 and 24 is : ",end="")
print (computeGCD(54, 24))
