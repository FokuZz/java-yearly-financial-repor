# Yearly Financial Report #Java 
Описание программы "Yearly Financial Report":

Программа "Yearly Financial Report" позволяет создавать годовой финансовый отчет на основе месячных отчетов. Для работы программы необходимы месячные отчеты в формате CSV, которые содержат информацию о доходах и расходах за каждый месяц.

Структура месячных отчетов:
item_name (название товара/услуги)
is_expense (булевое значение, указывающее является ли позиция расходом или доходом)
quantity (количество единиц товара/услуги)
sum_of_one (цена за единицу товара/услуги)

Структура годового отчета:
month (номер месяца)
amount (общая сумма дохода или расхода за месяц)
isExpense (булевое значение, указывающее является ли позиция расходом или доходом)
Программа считывает месячные отчеты и создает годовой отчет, содержащий по две записи на каждый из 12 месяцев - общий доход и расход за этот месяц.

Программа написана на языке программирования Java. Она использует стандартную библиотеку Java для работы с файлами и коллекциями данных.

Пользователю необходимо запустить программу и ввести год, за который он хочет получить годовой отчет. Если для указанного года имеются месячные отчеты, программа автоматически создаст годовой отчет и выведет его на экран. Если же месячные отчеты отсутствуют, программа выведет сообщение об ошибке.

Программа имеет следующие классы:

Accounting: главный класс, содержащий точку входа в программу, связывающий остальную логику
MonthlyReport: класс, описывающий месячный отчет
YearlyReport: класс, описывающий годовой отчет

Программа написана в учебных целях и может быть использована как пример для создания подобных финансовых отчетов.
