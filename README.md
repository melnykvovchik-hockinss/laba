main_list = [23, 18, 1, 25, 14, 9,
             "Банана", "яблуко", "виноград", "вишня", "апельсин",
             "груша", "ківі", "слива", "персик", "манго"]

ints = [x for x in main_list if isinstance(x, int)]
strings = [x for x in main_list if isinstance(x, str)]
sorted_list = sorted(ints) + sorted(strings)

multiples_of_two = [x for x in ints if x % 2 == 0]
uppercased_strings = [x.upper() for x in strings]

print("Основний список:", main_list)
print("Відсортований список:", sorted_list)
print("Елементи, кратні двом:", multiples_of_two)
print("Рядки капсом:", uppercased_strings)
