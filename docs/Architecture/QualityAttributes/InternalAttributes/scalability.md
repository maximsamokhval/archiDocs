# Scalability (Масштабируемость)

Масштабируемость (**scalability**) определяет способность приложения расти
и обслуживать больше пользователей, данных, серверов, географических точек, транзакций, сетевого трафика, операций поиска и других сервисов без снижения производительности и корректности. Масштабируемость предъявляет требования к оборудованию и ПО. Масштабирование системы вверх подразумевает приобретение более быстрых компьютеров, увеличение памяти или дискового пространства, добавление серверов, зеркальное отображение баз данных или увеличение пропускной способности сети.

!!! hint "Примеры" 

    - SCA-1. Надо обеспечить возможность увеличения пропускной способности
    аварийной телефонной системы с 500 до 2500 звонков в день в течение 12 ча-
    сов.
    - SCA-2. Веб-сайт должен уметь справляться с 30-процентным ростом ча-
    стоты запросов страниц в квартал на протяжении как минимум двух лет без
    ощутимого пользователями снижения производительности.
    - SCA-3. Система распространения должна поддерживать до 20 новых
    складских комплексов.

!!! faq "Вопросы"

    - Какова оценка числа общего числа и числа одновременных пользователей, которое должна обслуживать система через несколько месяцев, кварталов или лет?
    - Не могли бы вы описать, как и почему в будущем могут вырасти потребности в мощностях хранения данных?
    - Какие минимально приемлемые критерии производительности должны быть удовлетворены независимо от числа пользователей?
    - Каковы планы будущего роста в плане числа серверов, центров обработки данных или числа установленных экземпляров системы?


!!! info "Источники"
    - [Разработка требований к программному обеспечению. Карл Вигерс. Джой Битти](https://www.yakaboo.ua/ua/razrabotka-trebovanij-k-programmnomu-obespecheniju-3-e-izd-dopolnennoe.html)