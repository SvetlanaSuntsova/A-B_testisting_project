# A-B_testisting_project
1. Целевой группе была предложена новая механика оплаты услуг на сайте, у контрольной группы оставалась базовая механика. В качестве задания нужно проанализировать итоги эксперимента и сделать вывод, стоит ли запускать новый способ оплаты на всех пользователей.
Даны 4 таблицы:
- groups.csv - файл с информацией о принадлежности пользователя к контрольной или экспериментальной группе (А – контроль, B – целевая группа) 
- groups_add.csv - дополнительный файл с пользователями
- active_studs.csv - файл с информацией о пользователях, которые зашли на платформу в дни проведения эксперимента. 
- checks.csv - файл с информацией об оплатах пользователей в дни проведения эксперимента.

2. Задание на SQL.
- Необходимо написать оптимальный запрос, который даст информацию о количестве очень усердных студентов (решивших праильно з месяц 20 заданий).
-  Команда провела эксперимент, где был протестирован новый способ оплаты. Нужно в одном запросе выгрузить следующую информацию о группах пользователей:
ARPU 
ARPAU 
CR в покупку 
СR активного пользователя в покупку 
CR пользователя из активности по математикев покупку курса по математике

3. Задание на Python
- Реализуйте функцию, которая будет автоматически подгружать информацию из дополнительного файла groups_add.csv пересчитывать метрики.
- Реализуйте функцию, которая будет строить графики по получаемым метрикам.
