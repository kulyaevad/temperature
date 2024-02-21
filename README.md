x = input('Введите температуру:\n')
x = int(x)
if x > 25:
    print('Африка')
else:
    if x > 15:
        print('Тепло')
    if x < 5:
        print('Холодно')
    else:
        print('Нормально')
