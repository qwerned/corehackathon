#Название BI системы

CoRe Hackathon powerfull BI system

#Функционал

Две BI-системы, которые получают данные из папки, которая указывается в запросе "folder".

Система №1
BI система умеет считать (кол-во звонков и CPA) и сравнивать три различных модели атрибуции звонков:
- По количеству просмотров страниц в рамках визита
- По длительности визита в рамках визита
- По модели U-Shape в рамках визита
Все данные были объеденены в разрезе рекламных систем, кампаний, групп и фраз. Данные модели атрибуции были сведены с расходами из Янжекс.Директа.

Также BI система имеет коррелированные данные по микроконверсиям, CR для каждой фразы и РК, сделали прогнозный CR для каждой фразы с учетом общего CR рекламной кампании.

Также учитывается разница от первого визита пользователя до его звонка (если он был), а затем происходит разбивка на группы отложенности и подсчет количества звонков в рамках той или иной группы.

В рамках BI системы используется модель данных "Звезда".

Система №2
BI система проводит базовую аналитику по звонкам и посетителям на основе текужих выгрузок из Comagic и Logs API.
Служит дополнительным инструментом для оценки работы операторов и для анализа аудитории сайта в целом.

#Участники команды

Александр Морин
Дмитрий Воронин
Денис Соболев
Павел Максимов

#Выявленные проблемы
Низкая скорость обработки первоначальных данных в рамках Power Query. 
Полная обработка данных второй BI системы занимает около часа на средней мощности  оборудовании.

#Типы анализа данных

- По количеству просмотров страниц в рамках визита
- По длительности визита в рамках визита
- По модели U-Shape в рамках визита

#Выдуманные веб-аналитические метрики и измерения (свойства)

- Группа отложенности звонков
- CPA атрибутивных моделей
- Прогноз конверсии по фразам

#Пример BI-системы в облаке

BI система №1:
https://app.powerbi.com/view?r=eyJrIjoiNGYyZDEyNjgtMzAzOC00ZTg0LWFmMWItZDYzMWZmYzNkZjU1IiwidCI6ImNmMzUzZDY1LWRiMDUtNDY3YS04OGFlLTkzNzk5Yzg5NTNkMiIsImMiOjl9

BI система №2:
https://app.powerbi.com/view?r=eyJrIjoiZWJlNDg1Y2YtMmU1NS00YmFkLWFhN2QtODRjODAwODUzYTNhIiwidCI6ImNlZjk4ZTU4LTgxZjctNDE5NC1iZTgyLWY2M2E3ZGU4YTdhZSIsImMiOjl9
#Файл PBIX для скачивания

BI система №1:
https://github.com/qwerned/corehackathon/raw/master/Hackaton_1.pbix

BI система №2:
https://github.com/qwerned/corehackathon/raw/master/Hackaton_2.pbix
