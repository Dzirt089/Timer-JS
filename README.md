# Timer-JS
Функция таймера в JS, честного таймера

Определяем дедлайн.
getTimeRamaining - парсит дедлайн (получает в строковом значении через input админки и т.д) в милисек.
Проводится математический расчет по определению разницы в милисек, и перевод в дни/часы и т.д.
Возвращается значение объектом

setClock - устанавливаем таймер. Получаем данные с верстки .
Затем следующей функцией выводим результат на страницу. обновляем каждые 1000 милисек интервал, и следим чтобы выводились
значения не 4, а 04. С помощьюпомощника-функции

После окончания акции и натупления дедлайна - таймер останавливается
