Обработка ошибок в программировании

Задание 1. Преобразование строки в число
Реализуйте метод convertAndSum, который принимает массив строк, каждая
из которых должна быть преобразована в целое число. Метод возвращает
сумму всех чисел. Если хотя бы одна строка не может быть преобразована в
число, метод должен выбросить исключение NumberFormatException.
Дополнительно, если сумма чисел превышает 100, выбрасывайте
ArithmeticException с сообщением "Превышен лимит суммы".

Задача 2. Объединение массивов с проверкой длины и содержимого
Реализуйте метод mergeAndValidateArrays, который принимает два
массива целых чисел. Метод должен объединить массивы и вернуть новый
массив. Если длины массивов не равны, выбрасывайте исключение
IllegalArgumentException. Если хотя бы один элемент объединенного
массива отрицательный, выбрасывайте исключение RuntimeException с
сообщением "Обнаружен отрицательный элемент".

Задача 3. Обработка исключений для разностных массивов
Реализуйте метод subArraysWithExceptionHandling, который принимает
два массива целых чисел. Метод должен возвращать новый массив, где
каждый элемент является разностью соответствующих элементов двух входных
массивов. Если длины массивов не равны, выбрасывайте
IllegalArgumentException с сообщением "Массивы разной длины". Если
результат разности оказывается отрицательным, выбрасывайте
RuntimeException с сообщением "Отрицательный результат разности".

Задача 4. Поиск и замена строк
Реализуйте метод findAndReplace, который принимает массив строк, строку
для поиска и строку для замены. Если искомая строка не найдена, добавьте
сообщение об ошибке в список. Верните новый массив строк с выполненной
заменой.
