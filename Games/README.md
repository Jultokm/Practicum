
# Исследование поведения игроков мобильной игры "Космические братья"


## Данные

Для исследования были предоставлены два датасета. Основной датасет описывает события, совершенные в мобильной игре «Космические братья».  Для завершения первого уровня от игрока требуется выполнение одного из двух условий – победа над врагом или реализация проекта (разработка орбитальной сборки спутников).  
	Первый датасет содержит данные
- время события
- событие (возможны три варианта – объект построен, первый уровень завершен, проект завершен)
- тип здания (три типа – соборочный центр, космопорт, исследовательский центр)
- идентификатор пользователя
- тип реализованного проекта.

Второй датасет содерит 
- идентификатор пользователя
- рекламный источник, с которого пришел пользователь, установивший приложение.


## Задача

- проанализировать поведение игроков в зависимости от источника перехода
- проверить две гипотезы


## Используемые библиотеки
*pandas*  
*datetime*  
*seaborn*  
*scipy*
