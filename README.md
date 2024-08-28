# module_2_3.py
# "Стиль кода часть II. Цикл While."
my_list = [42, 69, 322, 13, 0, 99, -5, 9, 8, 7, -6, 5]
i = 0
while i < len(my_list):
    print(my_list[i])
    i += 1
    if my_list[i] == -5:
        i += 1
    if my_list[i] == -6:
         i += 1


