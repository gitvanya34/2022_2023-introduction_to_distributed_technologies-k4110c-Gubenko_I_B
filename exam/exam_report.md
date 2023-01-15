University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)  
Year: 2022/2023  
Group: K4110c  
Author: Gubenko Ivan Borisovich

---
## Экзамен

### 3. Что такое kubernetes? Архитектура, работа служебных сервисов, методы организации развертывания контейнеров.

kubernetes набор апи который создал гугл для управления своими контейнерами. k8s позволяет управлять нодами узлами подами.

Под это минимальная едница в один под могут входить несколько контейнеров 



K8s похволяет:

- Разворачивать приложения
- Настривать реплики приложения
- Выделять конкретное значение ресурсов на конкретный узел
- Распределять нагрузку между узлами
- Настраивтаь внутрисетевые доступы и доступы пользовтаелей
- Управлять деплоем приложения


Работающий кластер Kubernetes включает в себя агента, запущенного на нодах (kubelet), и компоненты мастера (APIs, scheduler, etc) поверх решения с распределённым хранилищем.

Разработчик обращается к апи k8s мастер,  апи общается с нодами, а ноды общаются с конечным пользователем через внешний порт прокси



### 17. Блокчейн. Его основные характеристики.
Блокчейн это децентрализованная технология 
 
используется в криптоволютах, банковских деле, кибербезопасности
Если расценивать блокчейн как структуру данных то он представляет из себя связный список содержащий информацию. 

Если обратиться к этимологии данного слова то переводится как "цепочка блоков", под блоками понимается какое-то количество информации. 
данная цепочка блоков информации подчинаяется определееныым правилам и является последовательной и непрерывной. 
блоки связаны друг с другом не только нумерацией, каждый блок содержит свою хешсумму и хешсумму предыдущего блока. И суть состоит в том что при иземеенении в блоке изменяеет ее хеш сумму.
То есть при изменении родителького блока нужно будет перерасчитывать всю цепочку что может быть очень вычислительно сложно или попросту невозможно на текущем уровне развития вычислительной техники.
Плюс ко всему этому цепочки хранятся на множестве устройств по всему миру.

Процесс майнинга заключается в расчете хеша (выходных данных) заголовка блока в блокчейне. Один блок включает в себя: