# Анализ поведения пользователей в мобильном приложении

## ЗАДАЧИ ПРОЕКТА: 
Вы работаете в стартапе, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи вашего мобильного приложения.
После этого исследуйте результаты A/A/B-эксперимента. Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры испугались, что пользователям будет непривычно. 
Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми. 
Выясните, какой шрифт лучше.
Создание двух групп A вместо одной имеет определённые преимущества. Если две контрольные группы окажутся равны, вы можете быть уверены в точности проведенного 
тестирования. Если же между значениями A и A будут существенные различия, это поможет обнаружить факторы, которые привели к искажению результатов. Сравнение контрольных 
групп также помогает понять, сколько времени и данных потребуется для дальнейших тестов.

## СТАТУС ПРОЕКТА:
Проект завершен

## НАВЫКИ И ИНСТРУМЕНТЫ:
* A/B-тестирование
* Python
* Pandas
* Matplotlib
* Seaborn
* Событийная аналитика
* Продуктовые метрики
* Plotly
* Проверка статистических гипотез
* Визуализация данных

## ВЫВОДЫ ПРОЕКТА:
* Мы выяснили, что во всех трех группах количество пользователей примерно одинаково, что означает корректность всех механизмов и расчетов;
* Самое популярное событие - MainScreenAppear (посмотрело главный экран) - 98% пользователей всех трех групп совершили это действие;
* Для сравнения всех групп мы использовали ttest. Нулевой гипотезой (Но) определили, что доли привлечения пользователей в группах равны, а альтернативная гипотеза (Н1) 
означала, что доли привлечения пользователей в группах не равны. Проведя тест, выяснили, что никаких различий между контрольными группами нет, а значит, мы могли быть 
уверены в точности эксперимента;
* Так же не оказалось различий между каждой контрольной группой и экспериментальной и объединенных контрольных групп и экспериментальных;
* Следовательно, замена шрифта во всем приложении на активность пользователей никак не повлияет
