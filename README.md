# Дз 2. Декодирование PNG
Техническое задание: [КТ_2022_2.pdf](КТ_2022_2.pdf)

Тестирующей системы нет(

## Ошибки

Обозначения: * - не мешает раскодировать файл, но не по стандарту

1. [Исходное фото](cases/errors/1.png)
2. [Неправильная подпись](cases/errors/2.png)
3. [Неправильная подпись](cases/errors/3.png)
4. [Неправильная длина IHDR](cases/errors/4.png)
5. [Неправильное название IHDR](cases/errors/5.png)
6. [Неправильный метод сжатия, метод фильтрации в IHDR](cases/errors/6.png)
7. [Неправильная высота, ширина в IHDR](cases/errors/7.png)
8. [*Неправильная подпись (CRC) IHDR](cases/errors/8.png)
9. [**Добавлен "левый" правильный чанк phtq с неправильной подписью](cases/errors/9.png)
10. [*Добавлен "левый" правильный критический чанк HMI\ с неправильной подписью](cases/errors/10.png)
11. [Отсутствует IDAT](cases/errors/11.png)
12. [Неправильный размер IDAT](cases/errors/12.png)
13. [*Заканчивается не на IEND](cases/errors/13.png)
14. [**IEND имеет ненулевой размер](cases/errors/14.png)
15. [После IEND есть "левый" чанк](cases/errors/15.png)
16. [IHDR после IEND](cases/errors/16.png)
17. [IHDR после IDAT](cases/errors/17.png)
