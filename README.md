# Home-Work-2
Проект выполнили студенты БММ182: Замятина Виктория, Лебедева Виктория, Короваева Анастасия, Шарапова Екатерина

В задании необходимо было использовать набор данных MovieLens, расположенный по адресу https://grouplens.org/datasets/movielens/latest/

В этом наборе есть две версии: маленькая и большая.

На маленькой версии удалось достигнуть показателя MSE = 0.5576 (файл permar2)

При этом использовалось несколько методов (SVD с разными параметрами и SVD++), которые в конце были объединены в ансамбль по принципу "голосование два из трех", что позволило еще немного улучшить значение MSE относительно отдельных методов. Наборы параметров для предикторов были подобраны в отдельном блокноте с помощью функции GridSearchCV.

На большой выборке удалось достигнуть хорошего показателя MSE = 0.6223 (файл permar1_full) При этом использовался один метод SVD без оптимизации параметров. На большой выборке для отличного результата хватило и его.
