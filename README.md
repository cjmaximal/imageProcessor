# imageProcessor
Программа для преобразования изображений в битмап код. Для работы нужна [Java](https://www.java.com/ru/download/)
![КАРТИНКА](https://github.com/AlexGyver/imageProcessor/blob/master/docs/image.jpg)

## Возможности
- Поддержка популярных форматов изображений
- Встроенный редактор:
	- Перемещение/масштаб/поворот
	- Яркость/контрастность
	- Оттенки серого
	- Инверсия
	- Дисеринг (для OLED)
	- Порог (преобразовать в ЧБ)
	- Постеризация
	- Кисть
- Сохранение отредактированного изображения в файл
- Несколько вариантов кодировки:
	- OLED (вертикальный байт), 8 пикселей в байте, чёрный и белый (0-1)
	- 8 пикселей в байте, чёрный и белый (0-1)
	- 1 пиксель в байте, чёрный и белый (0-1)
	- 1 пиксель в байте, оттенки серого 8 бит (0-255)
	- RGB565, 1 пиксель в uint16
	- RGB888, 1 пиксель в uint32
- Настройка ширины и высоты
- Добавление слова PROGMEM
- Инверсия битмапа
- Отражение по горизонтали и вертикали
- Сохранение в файл, копирование в буфер обмена

## Управление
- Слайдеры можно перемещать колесом мыши (навести и вращать)
- Изображение можно перемещать удерживанием колеса мыши
- Изображение можно масштабировать вращением колеса мыши

## Скачать релиз
- [Windows 32](https://github.com/AlexGyver/imageProcessor/releases/download/imageProcessor/win32.zip)
- [Windows 64](https://github.com/AlexGyver/imageProcessor/releases/download/imageProcessor/win64.zip)
- [Linux 32](https://github.com/AlexGyver/imageProcessor/releases/download/imageProcessor/linux32.zip)
- [Linux 64](https://github.com/AlexGyver/imageProcessor/releases/download/imageProcessor/linux64.zip)
- [Linux arm64](https://github.com/AlexGyver/imageProcessor/releases/download/imageProcessor/linux-arm64.zip)
- [Linux armv6hf](https://github.com/AlexGyver/imageProcessor/releases/download/imageProcessor/linux-armv6hf.zip)

## Исходник
Программа сделана в [Processing](https://processing.org/). Используется библиотека **controlP5**, установить можно через встроенный менеджер библиотек (*Набросок/Импортировать библиотеку/Добавить библиотеку.../Libraries/* Искать **controlP5**). Также для работы Processing нужна [Java](https://www.java.com/ru/download/).

## Версии
- v1.0 - поехали
- v1.1 - добавил другие варианты вывода, инверсию и флип по Х и У, расширенный help
- v1.2 - изменена логика перемещения изображения, добавлено перемещение удерживанием колеса мыши и масштаба - вращением
