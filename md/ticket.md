  Используемые технологии:

JavaScript,
HTML,
localStorage,
Qrcode-generator
 
   Описание кода:
 
Основная задача, которую здесь выполняет код, связанна с созданием билета на основе выбранных данных сеанса с учётом данных выбранного сеанса. Данные из localStorage сохраняем в  selectSeanse. Используем метод JSON.parse для преобразования строки JSON. Рассчитываются на основе данных сеанса переменные price и places. DOM элементы  с определенными селекторами классов обновляются соответствующей информацией, а именно: название зала, выбранные места,  и время начала сеанса.   Формируется строка для QR-кода путем объединения различных фрагментов информации, включая дату, время начала сеанса, выбранные места, название зала, название фильма. QRCreator применяется для генерации QR-кода на основе строки. В результате, QR-код загружается и добавляется к DOM элементу с классом ".ticket__info-qr". DOMContentLoaded применяется для обеспечения функции generateTicket, что бы она выполнялась по завершении полной загрузки HTML-страницы. 