# Описание проекта "Определение перспективного тарифа для телеком-компании"

## Данные
В распоряжении имеются данные 500 пользователей телеком-компании: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за 2018 год.  

*Таблица calls.csv:*
- id - идентификатор звонка;
- call_date - дата совершения звонка;
- duration - продолжительность звонка;
- user_id - идентификатор клиента.   
  
*Таблица internet.csv:*
- id - идентификатор интернет-сессии;
- mb_used - объем интернет-трафика;
- session_date - дата интернет-сессии;
- user_id - идентификатор клиента.   

*Таблица messages.csv:*
- id - идентификатор сообщения;
- message_date - дата отправки сообщения;
- user_id - идентификатор клиента.  
 
*Таблица tariffs.csv:*
- messages_included - количество сообщений, включенных в тариф;
- mb_per_month_included - объем интернет-трафика, включенного в тариф;
- minutes_included - количество минут разговора, включенных в тариф;
- rub_monthly_fee - ежемесячная плата за тариф;
- rub_per_gb - стоимость 1Гб интернет-трафика сверх тарифа;
- rub_per_message - стоимость 1 сообщения сверх тарифа;
- rub_per_minute - стоимость 1 минуты разговора сверх тарифа;
- tariff_name - название тарифа.   

*Таблица users.csv:*
- user_id - идентификатор клиента;
- age - возраст клиента;
- churn_date - дата прекращения пользования тарифом;
- city - город проживания;
- first_name - имя клиента;
- last_name - фамилия клиента;
- reg_date - дата регистрации тарифа;
- tariff - название используемого тарифа.   

## Задача
Необходимо провести анализ поведения клиентов и сделать вывод — какой тариф лучше.

## Используемые библиотеки
`pandas`, `numpy`, `matplotlib`, `scipy`, `math`
