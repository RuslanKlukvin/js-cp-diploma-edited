  Используемые технологии:

JavaScript,
HTML,
localStorage
 
   Описание кода:
 
Основная задача, которую здесь выполняет код, связанна  с бронирования билетов с учётом данных выбранного сеанса.  Данные из localStorage сохраняем в  selectSeanse.  Задаём переменные price и places с нулем и пустыми строками соответственно. Их будем использовать для отображения на странице информации о стоимости заказа и выбранных местах.  Методом перебора массива selectSeanse.salesPlaces цикл for извлекает значения row, place и type из каждого элемента selectSeanse.salesPlaces.  В зависимости от типа места обновляется переменная цены. Если тип "стандартный", к цене добавляется значение selectSeanse.priceStandart, а если тип "vip", к цене добавляется значение selectSeanse.priceVip. В строке let newHallConfig меняем значения "selected" в свойстве hallConfig объекта selectSeanse на "taken"  методом replace. В конце функция fetch для отправки использует  HTTP POST-запрос на указанный URL-адрес (https://jscp-diplom.netoserver.ru/). Запрос включает в тело запроса необходимые параметры (event=sale_add, timestamp, hallId, seanceId и hallConfiguration). Если запрос прошел успешно, то мы перенаправляем пользователя на страницу "ticket.html".