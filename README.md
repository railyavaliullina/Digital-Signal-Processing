# Digital-Signal-Processing

1) Реализация вычисления отношения сигнал-шум;

2) Построение спектрограммы сигнала (изменение спектра частот во времени) в виде изображения с использованием окна Хеннинга;

3) Фильтрация сигнала;

        Реализация фильтра, котрорый пропускает только указанную частоту в сигнале. 
        Фильтр представлен в виде соединения FIR и  IIR фильтров. 
        Фильтр применяется таким образом, чтобы минимизировать фазовый сдвиг. 
        Построены графики передаточной функции FIR, IIR и итогового фильтра, спектрограммы и графики сигнала до и после фильтрации.



4) Осуществление сдвига спектра сигнала на указанную частоту;

        Использование гребенки фильтров для избежания наложения сдвинутых копий спектра сигнала.
        Гребенка представляет собой набор полосовых фильтров + ФНЧ (для крайней левой полосы) + ФВЧ (для крайней правой полосы).

5) Осуществление демодуляции сигнала с использованием аналитического сигнала.

        В сигнале передается битовая последовательность, которую необходимо извлечь. 
        С использованием аналитического сигнала строится последовательность мгновенных частот сигнала. 
        На основе полученной последовательности извлекаются передаваемые биты.
