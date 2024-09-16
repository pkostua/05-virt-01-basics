Задача 2

высоконагруженная база данных MySql, критичная к отказу - **виртуализация уровня ОС потомучто это удобно, а MySql легко запускается на разных ОС. Отказоустойсивость обеспечить средствами MySql.**

различные web-приложения - **кросплатформенные веб приложения: виртуализация уровня ОС. А если приложение работает на чем нибудь уникальном типа IIS 8, то уж лучше на физическом сервере запустить**

Windows-системы для использования бухгалтерским отделом - **скорее всего это будут физические машины, кто знает что имеется под капотом этой "Windows-системы". Больше компании могу спозволить себе паравиртуализацию.**

системы, выполняющие высокопроизводительные расчёты на GPU - **виртуализация уровня ОС, потомучто это удобно**

Задача 3

100 виртуальных машин на базе Linux и Windows, общие задачи, нет особых требований. Преимущественно Windows based-инфраструктура, требуется реализация программных балансировщиков нагрузки, репликации данных и автоматизированного механизма создания резервных копий. **VMware vSphere**.

Требуется наиболее производительное бесплатное open source-решение для виртуализации небольшой (20-30 серверов) инфраструктуры на базе Linux и Windows виртуальных машин. **KVM**

Необходимо бесплатное, максимально совместимое и производительное решение для виртуализации Windows-инфраструктуры. **XEN VM**

Необходимо рабочее окружение для тестирования программного продукта на нескольких дистрибутивах Linux. **VirtualBox**

Задача 4

Возможные проблемы и недостатки гетерогенной среды виртуализации:

1.  **Управление сложностью**: Сочетание нескольких систем управления виртуализацией может привести к повышению уровня сложности, что затрудняет управление и поддержку.
2.  **Неполная интеграция**: Разные системы управления могут не иметь полной интеграции между собой, что может привести к проблемам при управлении и конфигурировании виртуальных машин.
3.  **Сложности с обновлениями**: Обновление одной системы управления может повлиять на другую систему или виртуальные машины, что может привести к ошибкам или сбоям.
4.  **Ресурсоёмкость**: Использование нескольких систем управления может потреблять больше ресурсов (например, памяти или процессорного времени), что может привести к проблемам с производительностью.

Чтобы минимизировать эти риски и проблемы:

1.  **Оцените требования**: Оцените реальные потребности и требования виртуальной инфраструктуры и определите, нужна ли гетерогенная среда.
2.  **Выбираем систему управления**: Выберите системы управления виртуализацией, которые имеют полную интеграцию или поддерживают друг друга.
3.  **Установите протоколы совместимости**: Установите протоколы совместимости между системами управления для обеспечения корректной работы и минимизации ошибок.
4.  **Тестируйте и тестируйте еще раз**: Тестируйте гетерогенную среду перед ее внедрением, чтобы выявить возможные проблемы или конфликты.

Если бы у меня был выбор, я предпочел бы использовать монолитную систему управления (виртуализацию), например VMware vSphere. Такая система обеспечивает полную интеграцию и управление всеми виртуальными машинами из одного интерфейса.

Мои основные причины:

1.  **Упрощенная управление**: Монолитная система управления упрощает управление виртуальными машинами, что снижает риск ошибок или конфликтов.
2.  **Повышенная производительность**: Монолитная система управления часто имеет лучшие характеристики производительности, чем гетерогенная среда.
3.  **Снижение стоимости**: Использование монолитной системы управления может снизить стоимость и сложность поддержки виртуальной инфраструктуры.

Окончательный выбор будет зависеть от конкретных требований, ресурсов и приоритетов организации.
