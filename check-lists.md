<details>
<summary>Чеклист: регистрация на сайте (проект FEHU) </summary>
<br>

|Модуль|Проверка|Результат|
|---|---|---|
|**Регистрация через Google**|Вход через существующий аккаунт Google|:ballot_box_with_check:|
| |Вход через не существующий аккаунт Google|:ballot_box_with_check:|
|Регистрация через Apple|Вход через существующий аккаунт Apple|:ballot_box_with_check:|
| |**Вход через не существующий аккаунт Apple**|:ballot_box_with_check:|
| |Приходит проверочный код|:ballot_box_with_check:|
|**Регистрация через FB**|Вход через не существующий аккаунт FB|:ballot_box_with_check:|
| |Вход через не существующий аккаунт FB|:ballot_box_with_check:|
|**Ввод Email**|С существующим адресом электронной почты|:ballot_box_with_check:|
| |Повторная регистрация|:ballot_box_with_check:|
| |Пустое значение|:ballot_box_with_check:|
| |Только буквы|:ballot_box_with_check:|
| |Только числа|:ballot_box_with_check:|
| |Только .com|:ballot_box_with_check:|
| |Ввод специальных символов|:ballot_box_with_check:|
| |Ввод двух и более @|:ballot_box_with_check:|
| |Ввод < или >|:ballot_box_with_check:|
|**Ввод пароля**|Скрыть/показать пароль|:ballot_box_with_check:|
| |Пустое значение|:ballot_box_with_check:|
| |Оставить одно поле пустым|:ballot_box_with_check:|
| |Ввод только буквы|:ballot_box_with_check:|
| |Только спецсимволы|:ballot_box_with_check:|
| |Только цифры|:ballot_box_with_check:|
| |Буквы и специальные символы|:ballot_box_with_check:|
| |Буквы и цифры|:ballot_box_with_check:|
| |Цифры и спецсимволы|:ballot_box_with_check:|
| |Буквы, спецсимволы и цифры|:ballot_box_with_check:|
| |Ввод 5 символов|:ballot_box_with_check:|
| |Ввод 7 символов|:ballot_box_with_check:|
|**Флажок запомнить пароль**|Поставить/убрать|:ballot_box_with_check:|
|**Кнопка ввести новый Email**|Нажать|:ballot_box_with_check:|
|**Ссылки на политику конфиденциальности**|Нажать на скачивание|:ballot_box_with_check:|
</details>

<details>
<summary>Чеклист: базовые проверки (проект FEHU)</summary>
<br>

|Проверка   |Результат|
|---|---|
|Все страницы сайта успешно открываются и отображаются|:ballot_box_with_check:|
|Отрабатывают эффекты ховера по наведению на активные элементы|:ballot_box_with_check:|
|Форма курсора меняется на поинтер при наведении на активные элементы|:ballot_box_with_check:|
|Активные элементы кликабельны и выполняют свою функцию|:ballot_box_with_check:|
|Верстка страниц десктоп версии сайта соответсвует макетам|:ballot_box_with_check:|
|Верстка страниц мобильной версии сайта соответсвует макетам|:ballot_box_with_check:|
|Кроссбраузерная верстка в соответсвии с тз|:ballot_box_with_check:|
|Адаптивная верстка в соответсвии с тз|:ballot_box_with_check:|
|Шрифты соответсвуют макетам|:ballot_box_with_check:|
|Элементы интерфейса расположены и отцентрированы в соответсвии с макетом|:ballot_box_with_check:|
|Элементы пропорционально масштабируются с изменением разрешения|:ballot_box_with_check:|
|Соответсвие UI листам макета|:ballot_box_with_check:|
|Позиция товара в категории|:ballot_box_with_check:|
</details>

<details>
<summary>Чеклист: проверка оплаты (проект FEHU)</summary>
<br>

|Модуль   |Проверка|Результат|
|---|---|---|
|**3D Secure**| Ввод валидного кода из смс – успешная оплата|:ballot_box_with_check:|
| |Ввод невалидного кода из смс – не успешная оплата|:ballot_box_with_check:|		
| |Ввод кода из смс после истечения времени на повторную отправку кода|:ballot_box_with_check:|		
| |Вовторный запрос кода и ввод: нового кода/предыдущего кода из смс|:ballot_box_with_check:|		
| |Вернуться на предыдущий экран (экран ввода данных карты)|:ballot_box_with_check:|
|**Общие кейсы**|Пользователь производит оплату товара|:ballot_box_with_check:|		
| |Пользователь переходит на экран оплаты, возвращается обратно и изменяет количество товаров|:ballot_box_with_check:|		
| |Корректное отображение итоговой стоимости после применения промокода|:ballot_box_with_check:|		
| |Корректный расчет комиссии|:ballot_box_with_check:|		
| |Переход на экран оплаты с отключенным соединением с интернетом – корректное отображение ошибки|:ballot_box_with_check:|
|**Проверка успешных сценариев оплаты**|Успешное заполнение всех необходимых полей на виджете оплаты||:ballot_box_with_check:|	
| |Успешная оплата полной стоимости|:ballot_box_with_check:|
|**Проверка неуспешных сценариев оплаты**|Оплата данным платежным средством отклонена по неизвестным причинам||:ballot_box_with_check:|	
| |Истек срок действия банковской карты|:ballot_box_with_check:|
| |Платеж заблокирован из-за подозрения в мошенничестве|:ballot_box_with_check:|		
| |Не хватает денег для оплаты (сумма на карте равна нулю)|:ballot_box_with_check:|		
| |Не хватает денег для оплаты (сумма на карте в минусе)|:ballot_box_with_check:|			
| |Не хватает денег для оплаты (сумма на карте меньше стоимости)|:ballot_box_with_check:|		
| |Неправильно указан номер карты|:ballot_box_with_check:|	
| |Организация, выпустившая платежное средство, недоступна|:ballot_box_with_check:|		
| |Исчерпан лимит платежей для данного платежного средства или вашего магазина|:ballot_box_with_check:|	
| |Запрещены операции данным платежным средством (например, карта заблокирована из-за утери, кошелек — из-за взлома мошенниками)|:ballot_box_with_check:|		
| |Нельзя заплатить банковской картой, выпущенной в этой стране|:ballot_box_with_check:|		
| |Неправильно указан код CVV2 (CVC2, CID)|:ballot_box_with_check:|
|**Что проверять после оплаты**|Проверка чека, который приходит после оплаты|:ballot_box_with_check:|		
| |удостовериться, что отобразился товар на экране, например, «Мои покупки»|:ballot_box_with_check:		
| |проверить уведомление на почту (например об успешной покупке, приход чека)|:ballot_box_with_check:		
| |проверить цены (например оплачен был товар со скидкой, значит итоговая (оплаченная стоимость) и отображается в чеке, на экране «Мои покупки»)|:ballot_box_with_check:	
| |возврат денег на ту карту, с которой была совершена оплата|:ballot_box_with_check:|
</details>

<details>
<summary>Чеклист: распродажа в маркете (проект YOU)</summary>
<br>

|Проверка|Результат|
|---|---|
|**Backend + Web**|
|Даты распродажи, их граничные значения|:ballot_box_with_check:|
|Динамическое отображение начала и конца распродажи|:ballot_box_with_check:|
|Список фичей, на которые действуют скидки|:ballot_box_with_check:|
|Скидки в определенных валютах|:ballot_box_with_check:|
|Скидки на определенный период подписки|:ballot_box_with_check:|
|Бесплатные товары/Скидка 100%|:ballot_box_with_check:|
|Начисление софт валюты за покупку со скидкой|:ballot_box_with_check:|
|Покупка в софт валюте со скидкой|:ballot_box_with_check:|
|Письма о покупке/подписке|:ballot_box_with_check:|
|Пуши о покупке/подписке|:ballot_box_with_check:|
|Коммуникации о распродаже|:ballot_box_with_check:|
|Проверка интерфейса для RTL языков|:ballot_box_with_check:|
|**Android + iOS**|
|Даты распродажи, их граничные значения|:ballot_box_with_check:|
|Динамическое отображение начала и конца распродажи|:ballot_box_with_check:|
|Список фичей, на которые действуют скидки|:ballot_box_with_check:|
|Скидки в определенных валютах|:ballot_box_with_check:|
|Скидки на определенный период подписки|:ballot_box_with_check:|
|Бесплатные товары/Скидка 100%|:ballot_box_with_check:|
|Начисление софт валюты за покупку со скидкой|:ballot_box_with_check:|
|Покупка в софт валюте со скидкой|:ballot_box_with_check:|
|Письма о покупке/подписке|:ballot_box_with_check:|
|Пуши о покупке/подписке|:ballot_box_with_check:|
|Баннер распродажи и таймер|:ballot_box_with_check:|
|Переводы на баннере|:ballot_box_with_check:|
|Проверка Mobile Web версии|:ballot_box_with_check:|
</details>

<details>
<summary>Чеклист: добавление нового товара в маркет (проект YOU)</summary>
<br>

|Проверка   |Результат|
|---|---|
|**Backend + Web**|
|Категория товара: существующая/новая|:ballot_box_with_check:|
|Позиция товара в категории|:ballot_box_with_check:|
|Реальный товар/пустышка|:ballot_box_with_check:|
|Рейтинг товара|:ballot_box_with_check:|
|Иконка и скриншоты|:ballot_box_with_check:|
|Описание, переводы|:ballot_box_with_check:|
|Отображение описания и скриншотов для RTL языков|:ballot_box_with_check:|
|Карточка товара в категории и открытая|:ballot_box_with_check:|
|Платформы, для которых доступен товар|:ballot_box_with_check:|
|Цена в реальной и софт валюте|:ballot_box_with_check:|
|Товар по подписке/единоразовая покупка|:ballot_box_with_check:|
|События аналитики web для некоторых категорий|:ballot_box_with_check:|
|Новые диплинки для товара|:ballot_box_with_check:|
|**iOS + Android**|
|Категория товара: существующая/новая|:ballot_box_with_check:|
|Позиция товара в категории|:ballot_box_with_check:|
|Реальный товар/пустышка|:ballot_box_with_check:|
|Рейтинг товара|:ballot_box_with_check:|
|Иконка и скриншоты|:ballot_box_with_check:|
|Описание, переводы|:ballot_box_with_check:|
|Отображение описания и скриншотов для RTL языков|:ballot_box_with_check:|
|Карточка товара в категории и открытая|:ballot_box_with_check:|
|Платформы, для которых доступен товар|:ballot_box_with_check:|
|Цена в реальной и софт валюте|:ballot_box_with_check:|
|Товар по подписке/единоразовая покупка|:ballot_box_with_check:|
|События аналитики ios/android для некоторых категорий|:ballot_box_with_check:|
|Новые диплинки для товара|:ballot_box_with_check:|

