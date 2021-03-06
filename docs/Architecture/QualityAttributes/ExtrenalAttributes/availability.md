# Availability ( Доступность )

Запланированное время доступности, в течение которого система действительно доступна для использования и полностью работоспособна.

!!! hint "Примеры" 

    AVL-001. Система должна быть доступна как минимум на 95% по рабочим дням, с 05:00 до 23:00 по местному времени и доступна как минимум на 99% по рабочим дням, с 13:00 до 18:00.

    AVL-002. Плановые простои на обслуживание системы в период с 18:00 по местному времени пятницы до 09:00 местного времени субботы вычитаются из вычислений для определения доступности.

!!! faq "Вопросы"
    
    - Для каких частей системы критически важно оставаться доступным?
    - Какие бизнес-последствия недоступности системы для ее пользователей?
    - Если требуется регулярное обслуживание, то когда его лучше всего планировать? Как это влияет на доступность системы? Какая минимальная продолжительность периодов обслуживания? Как во время периодов обслуживания обрабатывать попытки доступа со стороны пользователей?
    - Если обслуживание должно выполняться в работающей системе, то какое влияние оно будет оказывать на доступность и как минимизировать это влияние?
    - Каковы нужны уведомления пользователей о том, что система стала недоступной?
    - У каких частей системы более строгие требования к доступности по сравнению с остальными частями системы?
    - Какие зависимости доступности существуют между группами функциональности ( например, невозможность принять оплаты из-за недоступности функции авторизации системы оплат)?

!!! info "Источники"
    - [Разработка требований к программному обеспечению. Карл Вигерс. Джой Битти](https://www.yakaboo.ua/ua/razrabotka-trebovanij-k-programmnomu-obespecheniju-3-e-izd-dopolnennoe.html)