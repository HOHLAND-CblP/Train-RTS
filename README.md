# Train RTS (Project_G)

# Об игре
Игра относится к жанру стратегий в реальном времени (RTS). Задача игрока доставить поезд с одной станции на другую. У игрока имеется возможность строить/достраивать ж/д пути по его усмотрению. Также в игре присутсвтует повествовательная линия, представленная платформером с элементами повествоательной новеллы.

# Строительство
В игре отсутсвует уровень обучения строительству, поэтому обучение представлено в текстовом виде.

На выбор представлено 5 типов ж/д путей: прямой путь, поворот на 90 грудусов, поворот на 45 градусов, стрелка с поворотом на 45 и с прямым путем, а также станции.

Каждый из типов дорог можно повернуть: прямой путь можно крутить на 45 грудусов, повороты и стрелку на 90 в любом сторону, станции поворачиваются только только в том случае, если есть возможность присоединиться к другому пути.

Станции не могут образовывать повороты, т.е. чтобы соединить станцию с двумя другими путями, нужно чтобы эти пути примыкали к клетке со станцией с противоположных концов.

**Примеры того как правильно соединять станции:**

![image](https://user-images.githubusercontent.com/72488586/131981912-e54be0d6-7a46-41aa-843e-d97a839b335d.png)

![image](https://user-images.githubusercontent.com/72488586/131982192-5f584763-2b52-4a9c-9d32-6a36d91a7a48.png)

![image](https://user-images.githubusercontent.com/72488586/131982291-3bcfe0c1-294b-4c90-8ed5-04940e4d9f52.png)

**Примеры того как не правильно соединять станции:**

![image](https://user-images.githubusercontent.com/72488586/131982343-b992882e-c374-40de-bf19-fe089be9cd41.png)

![image](https://user-images.githubusercontent.com/72488586/131982404-f508889b-2509-4980-a2c5-f440bd051c9a.png)

![image](https://user-images.githubusercontent.com/72488586/131982443-702850d8-a46f-436c-8458-d211cddf90a5.png)


