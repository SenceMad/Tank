Реализовал:
-	Передвижение танка (вперед-назад на W-S, стрелки вверх-вниз) (На A-D, либо стрелки влево-вправо танк крутится вокруг своей оси).
-	Камера зафиксирована.
-	Механика наводки башни в сторону курсора мыши. Скорость башни можно настраивать.
-	Механика выстрелов и полета снарядов (При клике на левую кнопку мыши вылетает снаряд затем идет перезарядка). При коллизии снаряд уничтожается.
-	Механика здоровья.
-	Противники (Стреляют в игрока в указанной области), случайно двигаются по сцене. Также есть турели, которые стоят на месте.
-	Уничтожение снарядов и объектов сопровождается анимацией.

Дополнения:
-	Добавил Аптечки, Броню которые рандомно выпадают или не выпадают из врагов после их уничтожения.
-	Переключаемые снаряды у игрока на кнопки («-» - листать влево, «+» - листать вправо). Различные типы снарядов:
   +	Фугасные (Урок в радиусе);
   +	Бронебойные (Больший урон);
   +	Медленные (Урон стандартный, но летят медленно);
   +	Бронебойно-Фугасные (Урон в радиусе и больший урон).
-	Переключаемая башня у игрока на кнопки («<» - листать влево, «>» - листать вправо) 
   +	Одиночная (Вылетает 1 снаряд);
   +	Двойная башня (Вылетает сразу 2 снаряда).
-	Переключаемый корпус танка на кнопки («{» - листать влево, «}» - листать вправо). Различные типы танков:
   +	Стандартный;
   +	Тяжелый (Скорость медленная, здоровье высокое);
   +	Средний (Скорость стандартная, здоровье немного увеличено);
   +	Быстрый (Скорость высокая, здоровье маленькое).
-	Перезагрузка уровня на кнопку «R».
-	Дополнительный параметр Броня. Показатель брони постепенно восстанавливается. При попадании - показатель брони уменьшается на количество полученного урона. Здоровье же уменьшается только тогда, когда показателя текущей брони недостаточно, чтобы погасить весь полученный урон.
-	Тряска камеры при выстрелах.

Были использованы:
-	Scriptable объекты
-	New Input System
-	2D Tilemap
