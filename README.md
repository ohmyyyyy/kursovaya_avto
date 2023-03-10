# ERD диаграмма для базы данных "Аренда Авто"  
## Auto  
### Описание  
Таблица Auto хранит информацию о конкретных автомобилях  
### Поля  
ID – индетификатор автомобиля  
Color – цвет  
Horsepower – количество лошадиных сил  
ID box type – идентификатор типа коробки  
ID type of configuration – идентификатор комплектации  
ID body type – идентификатор кузова  
ID brand – идентификатор марки  

## Type of box  
### Описание  
Справочная таблица. Хранит информацию о типах коробок автомобилей, которые имеются в базе  
### Поля  
ID – индетификатор типа коробки  
Name of box type – название типа коробки  

## Type of configuration  
### Описание  
Справочная таблица. Хранит информацию о комплектациях автомобилей, которые имеются в базе    
### Поля  
ID – индетификатор комплектации  
Name of the configuration – название комплектации  

## Brand  
### Описание  
Справочная таблица. Хранит информацию о марках автомобилей, которые имеются в базе    
### Поля  
ID – индетификатор марки  
Brand name – название марки   

## Body type  
### Описание  
Справочная таблица. Хранит информацию о кузовах автомобилей, которые имеются в базе    
### Поля  
ID – индетификатор кузова  
Body type name – название кузова  

## Client  
### Описание    
Таблциа Client хранит информацию о зарегистрированных в системе пользователей    
### Поля  
ID – индетификатор клиента  
Name – имя  
Login – логин, указанный при регистарции  
Contact phone – контактный телефон, указывается по желанию  

## Order  
### Описание  
Таблциа Order хранит информацию заказах    
### Поля  
ID – индетификатор заказа   
Start data – дата начала аренды  
End data – дата конца аренды, если аренда не закончилась, поле остается пустым до окончания  
Price – цена аренды  
ID auto – идентификатор арендованного авто  
ID client – идентификатор клиента, оформишего аренду  

## Accident  
### Описание  
Таблциа Accident хранит информацию о авариях автомобилей    
### Поля  
ID – индетификатор аварии  
ID type of dtp – идентификатор типа дтп  
Date – дата аварии  
Damaged part – поврежденная часть  
ID order – идентификатор заказа, при котором произошла авария  

## Type DTP  
### Описание  
Справочная таблица. Хранит информацию о типах ДТП, которые имеются в базе     
### Поля  
ID – индетификатор типа ДТП   
Name of the type of accident – название типа ДТП

