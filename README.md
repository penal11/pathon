
num_1 = input(str("введите слово"))
num_2 = 0
num_3 = 0
for num_2 in num_1:
    if num_2 in 'а' or num_2 in 'е' or num_2 in 'ё' or num_2 in 'и' or num_2 in 'о' or num_2 in 'у' or num_2 in 'ы' or num_2 in 'э' or num_2 in 'ю' or num_2 in 'я':
        num_3 += 1
        print(num_3)
