# harvesting-optimization

Задача оптимизации сбора урожая


1) Данная задача может возникнуть у агропромышленного комплекса. Задача решает проблему оптимального маршрута уборки урожая с полей. 
2) ТЗ:

	Дано:

		1.0 N пронумерованных полей произвольной площади и база (точка, куда трактор доставляет собранный с полей урожай)
		1.1 На каждом поле M комбайнов 
		1.2 У каждого комбайна ширина жатки равна L, а объем бункера равен V 
		
		2.0 Урожай с каждого поля должен собрать трактор
		2.1 Длины путей между полями и базой (граф)


		Результат: Программа принимает на вход данные, возвращает: 1) оптимальный маршрут уборки для каждого поля; 2) оптимальный маршрут доставки урожая со всех полей до базы

3)	Уборка поля: пока не решалось

	Доставка со всех полей на базу: Генетический алгоритм

