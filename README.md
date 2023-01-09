# A-set-of-methods-for-working-with-a-string

on English:
 A simple set of methods for easier interaction with strings in C++

на Русском:

 Простая обновляемая библиотека для упрощенного взаимодействия со строками в C++
 
 Все новые методы находятся в заголовочном файле "SStrings.h" в папке "Resource Files"
 
  Функционал каждого метода:
   
   Split() - метод, который делит строку по указанному вами символу. Пример:
    ![image](https://user-images.githubusercontent.com/115891577/211301295-0523190e-0a53-4153-81e9-e72d51c852cf.png)
    
    Где ":" - символ, по которому метод "режет строку", "Allow:3214" - сама строка, "f" - режим, в котором работает метод (на момент 01.09.23 поддерживается лишь один       режим, в котором возвращается строка ДО ключевого символа)
    
   StartWith() - метод, который проверяет, начинается ли строка с того же содержания, что и вторая строка. Пример:
   ![image](https://user-images.githubusercontent.com/115891577/211302064-d04cc881-60e6-4a9f-a5da-1f10393d907d.png)
   
   Где "desired" - искомая часть, наличие которой в начале строки и проверяет метод. "text" - в котором метод ищет искомую часть.
   
