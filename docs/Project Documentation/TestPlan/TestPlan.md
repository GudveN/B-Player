### Содержание
  1. [Введение](#1)
  2. [Объект тестирования](#2)
  3. [Атрибуты качества](#3)
  4. [Риски](#4)
  5. [Аспекты тестирования](#5)<br>
    5.1. [Возможность начать воспроизведения аудиозаписи](#001)<br>
    5.2. [Возможность остановить воспроизведения аудиозаписи](#002)<br>
    5.3. [Возможность переключаться на следующую или предыдущую аудиозапись](#003)<br>
    5.4. [Возможность загрузки всех аудиофайлов в плейлист](#004)<br>
    5.5. [Возможность удаления аудиозаписи из плейлиста](#005)<br>
    5.6. [Изменение громкости воспроизведения](#006)<br>
    5.7. [Возможность воспроизводить плейлист заново, при его окончании](#007)<br>
    5.8. [Проигрывание аудиозапизей в разной последовательности](#008)<br>
6. [Подходы к тестированию](#6)
7. [Представление результатов](#7)
8. [Выводы](#8)


<a name="1"></a>
### 1. Введение
Данный план предназначен для тестирования приложения "B-Player". Цель проведения тестирования - проверка работоспособности и пригодности приложения для практического использования.
В данном плане используется терминология, соответствующая данному приложению, просьба перед его прочтением ознакомится с [глоссарием приложения "B-Player"](https://github.com/steppbol/B-Player/blob/master/docs/Project%20Documentation/Glossary.md)

<a name="2"></a>
### 2. Объект тестирования
Тестируемое приложение содержит 1 модуль, созданный для выполнения определённого функционала:
 - главное окно (окно управления приложением).


<a name="3"></a>
### 3. Атрибуты качества
1. Функциональность:
    - функциональная полнота: приложение должно соответствовать всем функциональным требованиям, заявленных в [SRS](https://github.com/steppbol/B-Player/blob/master/docs/Project%20Documentation/SRS.md);
2. Удобство использования:
    - простота пользовательского интерфейса: интерфейс должен быть достаточно простым для интуитивного использования новым пользователем.
3. Кроссплатформенность:
    - корректная работа приложения на платформах:
      - Windows
      - Linux.

<a name="4"></a>
### 4. Риски
Приложение использует системные средства для воспроизведения звука, из-за чего воспроизведение звука на разных операционных системах может отличаться. Также на разнных операционных системах имеются разные кодеки, поэтому воспроизведение некоторых форматов может оказаться недоступным.


<a name="5"></a>
### 5. Аспекты тестирования

#### Аспекты, подвергаемые тестированию:
- возможность начать воспроизведение аудиозаписи;
- возможность остановить воспроизведение аудиозаписи;
- возможность переключаться на следующую или предыдущую аудиозапись:
- возможность загрузки всех аудиофайлов в плейлист;
- возможность удаления аудиозаписи из плейлиста;
- изменение громкости воспроизведения;
- возможность воспроизводить плейлист заново, при его окончании;
- проигрывание аудиозапизей в разной последовательности.

<a name="001"></a>
##### Возможность начать воспроизведения аудиозаписи
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения на попытку начать воспроизведение аудиозаписи.
2. Выполнение данной операции (действительное воспроизведение аудиозаписи при нажатии кнопки).

<a name="002"></a>
##### Возможность остановить воспроизведения аудиозаписи
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения на попытку остановить воспроизведение аудиозаписи.
2. Выполнение данной операции (действительное воспроизведение аудиозаписи при нажатии кнопки).

<a name="003"></a>
##### Возможность переключаться на следующую или предыдущую аудиозапись
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения на переключение на следующую аудиозапись в выбранном направлении.
2. Выполнение данной операции (действительное переключение на следующую аудиозапись в выбранном направлении).

<a name="004"></a>
##### Возможность загрузки всех аудиофайлов в плейлист
Этот вариант использования небходимо протестировать на:
1. Отображение аудиофайлов с нужным расширением.
2. Загрузки всех выбранных аудиофайлов в плейлист.
3. Отмену операции при закрытии окна выбора аудиофайлов.

<a name="005"></a>
##### Возможность удаления аудиозаписи из плейлиста
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения на попытку удаления аудиозаписи из плейлиста.
2. Выполнение данной операции (удаление аудиозаписи из плейлиста).

<a name="006"></a>
##### Изменение громкости воспроизведения
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения на попытку изменить громкость.
2. Выполнение данной операции (действительное измение громкости воспроизведения).

<a name="007"></a>
##### Возможность воспроизводить плейлист заново, при его окончании
Этот вариант использования небходимо протестировать на:
1. Реакцию приложения на воспроизведение аудиозаписи следующей за последней в плейлисте, т. е. первой аудиозаписи в плейлисте.
2. Выполнение данной операции (переключение на первую аудиозапись в плейлисте).

<a name="008"></a>
##### Проигрывание аудиозапизей в разной последовательности
Этот вариант использования небходимо протестировать на:
1. Измение порядка воспроизведения при нажатии кнопки на последовательный или произвольный.
2. Выполнение данной операции (измение порядка воспроизведения).

<a name="6"></a>
### 6. Подходы к тестированию
Для тестирования приложения необходимо вручную проверить каждый аспект тестирования.

<a name="7"></a>
### 7. Представление результатов
|Сценарий|Действие|Ожидаемый результат|Фактический результат| Оценка|
|:---|:---|:---|:---|:---|
|001-1: Воспроизведение аудиозаписи, которая не выбрана| Нажать на кнопку "Play"| Началось воспроизведение первой аудиозаписи в плейлисте|||
|001-2: Воспроизведение аудиозаписи, которая выбрана|Выбрать аудиозапись и нажать на кнопку "Play"|Началось воспроизведение выбранной аудиозаписи |||
|002-1: Остановка воспроизведения аудиозаписи| Нажать на кнопку "Pause", когда воспроизводится аудиозапись| Остановка воспроизведения текущей аудиозаписи|||
|003-1:  Переключение на следующую аудиозапись| Нажать на кнопку "Next" |Переключение на следующую аудиозапись в плейлисте|||
|003-2: Переключение на следующую аудиозапись, при одной аудиозаписи в плейлисте| Нажать на кнопку "Next" |Нет никакой реакции|||
|003-3: Переключение на предыдущую аудиозапись| Нажать на кнопку "Previous" |Переключение на предыдущую аудиозапись в плейлисте|||
|004-1: Загрузка всех аудиофайлов в плейлист| Нажать на кнопку "Add", выбрать аудиофайлы. Нажать "OK" и проверить добавление всех аудиофайлов в плейлист|Все файлы добавятся в плейлист|||
|004-2: Отмена загрузки всех аудиофайлов в плейлист| Нажать на кнопку "Add", выбрать аудиофайлы, закрыть окно проводника|Приложение никак не отрагирует на это|||
|005-1: Удаление аудиозаписи из плейлиста| Выбрать аудиозапись, нажать кнопку "Remove"|Приложение удалит выбранную аудиозапись|||
|005-2: Удаление воспроизводимой аудиозаписи из плейлиста| Нажать на клавишу "Remove"|Приложение прекратит воспроизведение аудиозаписи и удалит ее из плейлиста|||
|006-1: Изменение громкости воспроизведения|Нажать на кнопку "Volume", перемещать ползунок для изменения громкости|Приложение изменит громкость воспроизведения аудиозаписей|||
|007-1: Воспроизведение плейлиста заново при его окончании|Переключиться на последнюю аудиозапись в плейлисте и нажать "Next"| Приложение воспроизведет первую аудиозапись в плейлисте|||
|008-1: Проигрывание аудиозапизей в произвольной последовательности|Нажать на кнопку "Random",иконка изменится на две "стрелочки", нажать на клавишу "Next"|Приложение начнет воспроизведение произвольной аудиозаписи в плейлисте|||
|008-2: Проигрывание аудиозапизей последовательно|Нажать на кнопку "Random", иконка изменится на "AB", нажать на клавишу "Next"|Приложение начнет воспроизведение следующей аудиозаписи в плейлисте|||

<a name="8"></a>
### 8. Выводы
Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов не гарантирует полной работоспособности на всех платформах и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.