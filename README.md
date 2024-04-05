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
