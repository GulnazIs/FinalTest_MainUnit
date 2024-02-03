# Задача

 Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

### Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

[“1234”, “1567”, “-2”, “computer science”] → [“-2”]

[“Russia”, “Denmark”, “Kazan”] → []

# Описание решения

Сначала была составлена блок-схема. Для решения задачи задаем массив строк, с которым будем работать, и массив, в который пойдут символы с длиной строк меньше или равно (первый и второй массивы соответственно). Затем с помощью цикла перебираем все элементы первого массива и находим те, которые соответствуют условию. Этими элементами заполняется второй массив, который затем выходит на печать.

![Блок - схема](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1#R7VpRj6M2EP41kdqHrAAHSB43m922UrZquye19%2BgEL3AFTI3ZJPfra4MdMCYsl1vC3ipSpOBhbOyZ%2BcafBybgLt7%2FQmAaPGIPRRPL8PYTsJpYlmnYBvvjkkMpsYEQ%2BCT0hFIleAq%2FItlTSPPQQ5miSDGOaJiqwi1OErSligwSgneq2jOO1Kem0Eea4GkLI136d%2BjRoJTOLbeS%2F4pCP5BPNp1FeSeGUlmsJAugh3c1EbifgDuCMS2v4v0dirjxpF3Kfg8n7h4nRlBC%2B3QAufuYur9l67%2FWL7fJ4yL%2F01lOTSAmRw9yxchjBhBNTGiAfZzA6L6SLgnOEw%2FxYQ3WqnTWGKdMaDLhF0TpQXgT5hQzUUDjSNxF%2B5D%2Bw7vf2KL1uXZntRcjF42DbCSUHGqdePNz%2FV7VrWjJfuX6%2BKJO2k2IMpyTLeoylog%2FSHxEO%2FTA0bsMFgjHiM2H9SMogjR8UecBRXz6R73KhexCePFbPFqO%2BwKjXDzpIWS%2B%2BQSzf3VXRxHDEXfpLggpekphsf4dg7LqMDEmIhTtu82oL1t0ABL4IhFIWOwqVJlSFtQQNTeGMtTsGvq9Qx%2F0DP3ZmKEPtNBnOwA8sMc5EZv0ckMUdzv%2F5bgQY%2BIhMt3iCJMJuC1GID9Np3X5z4U5ZQ925fP%2FYnhLCyM1SC4ArZkKLRO0YMtowdZsMGy5V2z1xtasJ7acMbE107AVsmZxxSOrAliJjC3zJa0rjA0Ru7n76BCZXxQh8ytCeiPE6YkQd1TitdAgcmAnlzYvr%2BGGHZMUz8Ao9BN2vWXGQWwbWvJwD9k55FbciEPPK4MAZeFXuCnG43ZOcZjQYjH2cmKvuvAiDkmi8%2BTIweo%2B6YjWk%2BiaGjemqeBrKnbF3qYXY%2F%2FBF1NTwc%2FPGXN50zfHKZzvLmsxJgDNGvwqMLYDcAQgmUa7vy%2FE43Qil%2BCPAaQy6rqA5LBNR2Vz7x1JjuYtyQdSbqoIZpnCtx8z%2FDsmMYx0Ql1wCsuBMWcAUXnHKEn8zRolPt%2BqH%2BTobLKp7KgTjADHmzy7DLkwbJVcuC38221hF%2B5Q7MLSGdeVXXSyhh5J8QR0L5MTLb2u82HYhXVit6mxC0dlF%2B8%2BJ1rOj8IufiAAWtZ3IrDoesu3k5qCiHA9SkT42Y3qysy06xHzqr7tGJ36YNGpzy7KGb9tfLofl2KdqJNU2WTuuK66Yb%2F3dKJ7S1Q2bUaZ7JXkRhp5AitQEKZRyZEa3mDeQo7aSi%2FDkaNr4b9%2Fbl5cKjd%2Fl0v10svZRxC9ltl%2B3jhzePHKwBYVUpuXR4u%2BhoLoN32mKMYui9%2Bgq%2Bs7%2FNjVYKuxpS9actKsJSfZQ%2BUk8I4ObMc0NHQ1Sn7j8Xo56oQ7hyV%2BjqNGidv8wOIVItfQH4bISRs2qYGlxVMWwJRfenibx4WvXkPapoyv9eYNoec06IA9t3XoXfY7AP1kfWRRySbjf%2FeJp8NzxG8nXLslX13UaNa4r6%2FOOt8qDKoiVMNzKHm%2BGPwN71lpzmoElwO601xTX1Y%2Fhz2vWhpIQ8loxiYTjfO%2BY7aA842%2BvmDN6oPB0rbVZ5fg%2Fn8%3D)
