# BigTrip: приложение для планирования путешествий.
автор: Влад Тимошенко < svenmaycry@yandex.ru >


---

Стек: HTML, CSS, JS, Babel, Webpack.

---

BigTrip: приложение для планирования путешествий. Приложение служит помощником в планировании логики вашего путешествия, будь то поездка из одного города в другой или перелет из одной страны в другую. Лаконичный интерфейс в сочетании с обширным функционалом помогает пользователю легко спланировать последовательность поездки и рассчитать общую стоимость с учетом даже небольших расходов.

Основной функционал приложения включает в себя редактирование и управление точками маршрута, применение фильтров, сортировку и взаимодействие с сервером.

* Пользователи могут создать новую точку маршрута, нажав «Новое событие», или отредактировать точки маршрута, нажав кнопку «стрелка вниз» в карточке точки маршрута, при которой открывается форма редактирования. Форма позволяет пользователям изменять поля точки маршрута и предоставляет возможности сохранения или удаления точки. Несохраненные изменения отбрасываются, если пользователь закрывает форму без сохранения.

* При создании или редактировании точки маршрута пользователям доступен блок дополнительных опций, специфичных для выбранного типа точки. Эти параметры могут различаться в зависимости от типа балла и могут включать флажки или раскрывающиеся меню для выбора доступных предложений. Поведение этих опций соответствует правилам, определенным для создания новой точки маршрута.

* При изменении типа точки маршрута блок дополнительных опций перерисовывается, если с новым выбранным типом есть связанные предложения, или скрывается, если доступных предложений нет. Введенные пользователем данные в других полях во время этого процесса сохраняются.

* Наличие предложений может улучшить качество обслуживания пользователей, предоставляя возможность настройки и гибкости при планировании поездки. Эти опции позволяют пользователям адаптировать точки маршрута к своим предпочтениям и потребностям, делая путешествие более персонализированным и приятным.

* В приложении также имеются фильтры, которые позволяют пользователям просматривать определенные подмножества точек маршрута. Доступные фильтры включают «Все» для полного списка, «Будущее» для запланированных точек, «Настоящее» для текущих точек и «Прошлое» для прошлых точек. Выбор фильтра соответствующим образом обновляет отображаемые точки маршрута.

* Для упорядочения точек маршрута предусмотрена функция сортировки. Пользователи могут сортировать по цене или продолжительности в порядке убывания.

* Приложение взаимодействует с сервером. Ответы сервера используются для обновления DOM, а любые изменения точек маршрута (например, удаление или обновление) отражаются только после успешной связи с сервером.

* Кроме того, интерфейс обеспечивает обратную связь с пользователем во время запросов к серверу и отправки форм. Кнопки меняют свои названия, чтобы указать на текущий процесс, а интерфейс временно блокируется до завершения запроса. В случае возникновения ошибки форма редактирования может дрожать, и отображаются соответствующие сообщения об ошибках.

* Общая стоимость поездки автоматически пересчитывается при создании, редактировании или удалении новой точки маршрута, а также при добавлении или изменении каких-либо предложений.

* Кроме того, заголовок приложения динамически генерирует первую и последнюю точки маршрута. Такое представление маршрута позволяет пользователям быстро понять основные пункты назначения.

* Пользователи могут легко получить доступ к важной информации, такой как общая стоимость поездки с учетом всех предложений, а также сводный обзор начальных и конечных точек маршрута с примененными предложениями. Эти дополнения способствуют более полному и информативному пользовательскому интерфейсу.
