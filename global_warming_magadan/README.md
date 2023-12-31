# ИНТЕРАКТИВНАЯ ВИЗУАЛИЗАЦИЯ ИЗМЕНЕНИЯ ТЕМПЕРАТУРЫ ВОЗДУХА Г. МАГАДАН С ПОМОЩЬЮ TABLEAU

В данном эссе продемонстрирована **визуализация изменения температуры воздуха г. Магадан за 1933-2022 гг.** с помощью программного обеспечения для интерактивной аналитики и визуализации данных Tableau.

Работа выполнена на основе набора данных, предоставленного источником http://www.pogodaiklimat.ru, в котором собраны средние месячные значения температуры воздуха по метеостанции Магадан за период 1933-2022 гг.

В эссе обсуждаются следующие темы:
- общая тенденция изменения температуры воздуха с 1933 г.
- разница в изменении температуры по месяцам

## Введение

Как известно, во второй половине XX века на планете начался глобальный процесс изменения климата [Израэль и др., 2001], произошло потепление атмосферы и океана, запасы снега и льда сократились, уровень моря повысился, концентрации парниковых газов возросли [Climate…, 2013]. Отклик современного потепления зафиксирован и на большей части Северо-Восточной Азии [Пономарев и др., 2005]. 

По крайней мере в последнем оценочном докладе Межправительственной группы экспертов по изменению климата, опубликованном в 2021 году [Assessing the Global Climate in 2021], влияние человека отмечено как однозначная причина изменения климата. Можно, конечно, рассуждать, какой вклад в это вносят и естественная цикличность, и природные факторы. Но все основные климатические модели однозначно доказывают, что такого стремительного роста средних температур в последние десятилетия не было бы без антропогенных выбросов парниковых газов.

Никто не оспаривает наличие естественных орбитальных циклов планеты, которые вывел сербский ученый Милутин Миланкович в первой половине XX века [Миланкович, 1939]. Они действительно могут серьезно сказываться на климате. Но эти циклы действуют на протяжении геологических времен сотен и тысяч лет, то есть медленно. Вся проблема в том, что начиная с середины прошлого века климат характеризуется беспрецедентно быстрым ростом глобальных температур.

Какой-то год может быть прохладнее, чем предыдущие, но в среднем тренд пока однонаправленный: скорость потепления только увеличивается [NASA Earth Observatory. World of Change: Global Temperatures].


## 1. Визуализация изменения температуры по годам

Чтобы увидеть общую динамику изменения температуры воздуха за период 1933-2022 гг. была использована разница между средней температурой месяца и средней месячной температурой за период 1951-1980 гг. (принят за нулевой уровень). 

Команда NASA GISS определила период 1951-1980 гг. в качестве базового в основном потому, что Национальная метеорологическая служба США использует трехдесятилетний период для определения “нормальной” или средней температуры. Работа GISS по анализу температуры также началась примерно в 1980 году, так что самыми последними 30 годами были 1951-1980 годы [NASA Earth Observatory. World of Change: Global Temperatures].

 <p align="center">
 <img src="https://github.com/cryomary/climate_analysis/assets/130345096/f6924b06-70d5-4551-92f3-9b98609f255e.png" /p>
 </p>
 
Скользящая средняя кривая разницы температур за последние 10 лет позволяет выделить основные тенденции и циклы изменений, а также измерить их скорость. Так как в данном случае мы взяли окно равное 10 годам, то первое значение скользящего среднего мы получили только за декабрь 1942 года. Скользящее среднее за последние годы достигло 1,59 °С.

 <p align="center">
 <img src="https://github.com/cryomary/climate_analysis/assets/130345096/a2c8abb3-6c08-4a96-bf6e-21035f596d7c.png)" /p>
 </p>

В 1951-1980 годах среднегодовая температура атмосферного воздуха в Магадане составляла -3,5 °С. В 1990-х годах она уже поднялась до -2,7 °С, а сейчас близка к -2 °С Цельсия. Можно предположить, что если за последние 50 лет температура поднялась на 1,5 °С, то еще через 50 лет она может выйти на нулевые значения, а еще через 50 - на плюсовые температуры.

Если мы разделим общую тенденцию на разные времена года, нетрудно увидеть тенденцию изменения температуры для каждого из них.

 <p align="center">
 <img src="https://github.com/cryomary/climate_analysis/assets/130345096/40d36c0a-e9d4-4625-8fc0-9c300d9e1a57.png" /p>
 </p>

Для летнего периода с 1990-х гг. отмечается устойчивая тенденция на потепление (температуры в течение рассматриваемого периода выше температур нулевого уровня 1951-1980 гг.).

Более значительное потепление в холодное время года компенсируется тем фактом, что межгодовая изменчивость намного больше, чем в теплое (летом). Таким образом, зимой потепление климата может быть не столь очевидным для общественности, как летом, потому что количество снегопадов увеличивается с потеплением, и существует практика приравнивать обильные снегопады к суровым зимним условиям, даже если температуры не являются экстремально низкими [J. Hansen, 2011]. 

## 2. Визуализация изменения температуры по месяцам

При разделении общей динамики на месяцы можно увидеть изменение температуры для каждого месяца. Для сравнения разницы в величине изменения температуры построен график циклов. В марте и ноябре наблюдается наибольшее повышение температур в последние годы (до 9 °С), наименьшее - в августе (до 1,5 °С). 

 <p align="center">
 <img src="https://github.com/cryomary/climate_analysis/assets/130345096/54499d74-f06d-495d-a995-18d9d3ac1b04.png" /p>
 </p>

Построенная тепловая карта согласуется с первым линейным графиком и подтверждает тенденцию изменения температуры в сторону повышения в исследуемом районе.

 <p align="center">
 <img src="https://github.com/cryomary/global_warming_magadan/assets/130345096/1a01d62b-d53d-4723-bc7d-d5ee1ac18f78.png" /p>
 </p>

 ### Подробнее
 
- Интерактивная визуализация по ссылке - https://public.tableau.com/app/profile/mariia5346/viz/global_warming_magadan/Dashboard1?publish=yes

 ## Литература

 1. https://github.com/marileano/Climate-Change-Tableau-Visualization
 2. https://samuelzhaoy.github.io/global-warming-trend-analysis-with-tableau/
 3. Climate Change 2013: The Physical Science  Basis [Электронный ресурс]. URL: https://www.climatechange2013.org
 4. NASA Earth Observatory. World of Change: Global Temperatures [Электронный ресурс]. URL: https://earthobservatory.nasa.gov/world-of-change/global-temperatures
 5. NOAA National Centers for Environmental Information (2022, January 10) Assessing the Global Climate in 2021
 6. Израэль Ю. А., Груза Г. В., Катцов В. М., Мелешко В. П. Изменение глобального климата. Роль антропогенных воздействий // Метеорология и гидрология. 2001. № 5. С. 5–22.
 7. Миланкович М. Математическая климатология и астрономическая теория колебаний климата. — М., Л., 1939.
 8. Пономарев В.И., Каплуненко Д.Д., Крохин В.В. Тенденции изменений климата во второй половине XX века в Северо-Восточной Азии, на Аляске и северо-западе Тихого океана // Метеорология и гидрология. 2005. № 2. С. 15–26.
