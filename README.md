Прогнозирование количества заявок на одобрение кредитной карты

**Описание столбцов:**
ID - Номер клиента
CODE_GENDER - Пол клиента (F/M)
FLAG_OWN_CAR - Наличие автомобиля (Y/N)
FLAG_OWN_REALTY - Наличие недвижимости (Y/N)
CNT_CHILDREN - Количество детей (No children/1 children/..)
AMT_INCOME_TOTAL - Годовой доход
NAME_EDUCATION_TYPE - Уровень образовани ('Secondary / secondary special'/Higher education/..)
NAME_FAMILY_STATUS - Семейное положение (Married/'Single / not married'/..)
NAME_HOUSING_TYPE - Тип проживания ('House / apartment'/With parents/..)
DAYS_BIRTH - Возраст в днях
DAYS_EMPLOYED - Продолжительность работы в днях
FLAG_MOBIL - Наличие мобильного телефона (0/1)
FLAG_WORK_PHONE - Наличие рабочего телефона (0/1)
FLAG_PHONE - Наличие телефона (0/1)
FLAG_EMAIL - Наличие почты (0/1)
JOB - Работа
BEGIN_MONTHS - Рекордный месяц (Месяц для извлеченных данных является отправной точкой в обратном направлении, 0 - текущий месяц, -1 - предыдущий месяц и так далее)
STATUS - Статус (0: просрочка на 1-29 дней 1: просрочка на 30-59 дней 2: просрочка на 60-89 дней 3: просрочка на 90-119 дней 4: просрочка на 120-149 дней 5: Просроченные или безнадежные долги, списания более чем на 150 дней C: погашен в этом месяце X: Нет кредита в течение месяца)
TARGET - Целевой столбец (Пользователь с риском отмечен как "1", в противном случае - как "0")
