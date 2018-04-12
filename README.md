Условие задачи
 
Василий Петрович хочет создать банк. В его банке будут клиенты, обладающие следующими свойствами:
Идентификационный номер
 Имя
 Фамилия
 Пол
 Дата Рождения
 
Клиенты могут вкладывать деньги под разные проценты. Каждый депозит находится на отдельном счету. 
 
На все депозиты, согласно процентам, каждый месяц начисляется сумма и добавляется к сумме депозита (депозит с капитализацией). Каждый депозит выдается на индивидуальных условиях.
 
Проценты начисляются каждый месяц. Если депозит был сделан 17 апреля, проценты начисляются каждый месяц 17-го числа. Если депозит был сделан 31 числа, проценты начисляются в последний день месяца.
 
Со всех депозитов каждый месяц снимается комиссия за использование счета. Комиссия зависит от суммы на счету:
 Баланс на счету: 0 - до 1000 у.е. Комиссия 5%, но не менее чем 50 у.е.
 Баланс на счету: 1000 у.е. - до 10,000 у.е. Комисcия 6%
 Баланс на счету: от 10,000 у.е. Комиссия 7%, но не более чем 5000 у.е.
 
Комиссия взимается каждый месяц 1-го числа. Комиссия взимается частично, если счет был заведен в прошлом месяце. Например:
Счет заведен 31 марта, комиссия будет равна 1/31 стандартной комиссии.
 
Если по депозиту нужно начислить проценты и снять комиссию в один и тот же день, то порядок следующий:
 Начисление процентов
 Снятие комиссии.
 
 
 
Необходимо реализовать
 
1.Структуру базы данных MySQL, в которой:
1.Хранятся клиенты и депозиты клиентов (у клиента может быть больше чем один депозит)
2.История начислений процентов и снятия комиссий
 
0.Cron, который выполняет расчет:
1.Начисления процентов и снятия комиссий


 
0.Реализовать репорты (можно без верстки, просто выдать в виде Dos-таблицы, или как удобно):
1.Убыток или прибыль банка по месяцам. (Сумма комиссий - Сумма начисленных процентов)
2.Средняя сумма депозита (Сумма депозитов/Количество депозитов) для возрастных групп:
1.I группа - От 18 до 25 лет
2.II группа - От 25 до 50 лет
3.III группа - От 50 лет
Требования
 
 Использовать ООП
 Версия PHP не ниже 5.6
 Можно использовать любой фреймворк
 Не использовать сторонних библиотек для PHP
 
 1-е задание нужно сделать обязательно
 2-е или 3-е (на выбор) нужно сделать обязательно