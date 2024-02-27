# Rose
class Rose:
    def __init__(self, color, length, fragrance):
        self.color = color
        self.length = length
        self.fragrance = fragrance

    def bloom(self):
        return "Роза расцвела"

    def __str__(self):
        return f"Роза ({self.color}, Длина: {self.length} см, Аромат: {self.fragrance})"

# Пример использования класса Rose
rose1 = Rose("Красная", 30, "Сильный")
print(rose1)

print(rose1.bloom())
