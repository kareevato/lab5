Варіант 1 - Лабіринт
Дано лабіринт у формі двійкової прямокутної матриці, знайдіть найкоротший шлях у лабіринті від заданої точки до вказаного пункту призначення.

Шлях можна побудувати лише з використанням комірок, які містіть 1.  В будь-який момент ми можемо рухатися лише на один крок в одному з чотирьох напрямків:
Go Top: (x, y) ——> (x – 1, y)
Go Left: (x, y) ——> (x, y – 1)
Go Down: (x, y) ——> (x + 1, y)
Go Right: (x, y) ——> (x, y + 1)

Наприклад, розглянемо наступну двійкову матрицю. Якщо початкова точка  має координати (0, 0), а  пункт призначення = (6, 6), тоді найкоротший шлях від джерела до пункту призначення має довжину 12

 [ 1  1  1  1  1  0  0  1  1  1 ]
 [ 0  1  1  1  1  1  0  1  0  1 ]
 [ 0  0  1  0  1  1  1  0  0  1 ]
 [ 1  0  1  1  1  0  1  1  0  1 ]
 [ 0  0  0  1  0  0  0  1  0  1 ]
 [ 1  0  1  1  1  0  0  1  1  0 ]
 [ 0  0  0  0  1  0  0  1  0  1 ]
 [ 0  1  1  1  1  1  1  1  0  0 ]
 [ 1  1  1  1  1  0  0  1  1  1 ]
 [ 0  0  1  0  0  1  1  0  0  1 ]

Вхідні дані містяться у файлі input.txt у форматі:
0, 0 #початкова точка
6, 6 #точка призначення
10,10 # кількість рядків та стовпчиків у матриці
 [ 1  1  1  1  1  0  0  1  1  1 ]
 [ 0  1  1  1  1  1  0  1  0  1 ]
 [ 0  0  1  0  1  1  1  0  0  1 ]
 [ 1  0  1  1  1  0  1  1  0  1 ]
 [ 0  0  0  1  0  0  0  1  0  1 ]
 [ 1  0  1  1  1  0  0  1  1  0 ]
 [ 0  0  0  0  1  0  0  1  0  1 ]
 [ 0  1  1  1  1  1  1  1  0  0 ]
 [ 1  1  1  1  1  0  0  1  1  1 ]
 [ 0  0  1  0  0  1  1  0  0  1 ]


Результуючий файл має містити значення найкоротшого шляху від початкової точки до точки призначенн\\
