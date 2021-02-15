# test

1.
Part A:
Это вид для нашего таблицы: 
INSERT INTO mytable (id, , ticket_type, event_id, event_date, ticket_adult_price, ticket_adult_quantity, ticket_kid_price, ticket_kid_quantity, barcode, user_id, equal_price, created) VALUES ('$id', '$ticket_type', '$event_id', '$event_date', '$ticket_adult_price', '$ticket_adult_quantity', '$ticket_kid_price', '$ticket_kid_quantity', '$barcode', '$user_id', '$equal_price', '$created');

Решение:
Мы должны установить логическую переменную для нашей таблицы, где результат является “Истинным”, тогда такие значения, как цена, должны быть изменены на специальные цены(цена со скидкой)

+----+---------+----------+---------------------+--------------------+-----------------------+------------------+---------------------+----------+---------+-------------+---------------------+
| id | Special | event_id | event_date          | ticket_adult_price | ticket_adult_quantity | ticket_kid_price | ticket_kid_quantity | barcode  | user_id | equal_price | created             |
| 1  | 0       |   003    | 2021-08-21 13:00:00 | 700                | 1                     | 450              | 0                   | 11111111 | 00451   | 700         | 2021-01-11 13:22:09 |
+----+---------+----------+---------------------+--------------------+-----------------------+------------------+---------------------+----------+---------+-------------+---------------------+



Part B: 

баркод в этом случае должен представлять собой число, состоящее из 17 цифр. Что является дата, идентификатор пользователя и время.
Например:
баркод для этого билета должен быть: 20210821004511300 (Дата+идентификатор пользователя+время)


+----+----------+---------------------+--------------------+-----------------------+------------------+---------------------+----------+---------+-------------+---------------------+
| id | event_id |     event_date      | ticket_adult_price | ticket_adult_quantity | ticket_kid_price | ticket_kid_quantity | barcode  | user_id | equal_price |       created       |
+----+----------+---------------------+--------------------+-----------------------+------------------+---------------------+----------+---------+-------------+---------------------+
|  1 |      003 | 2021-08-21 13:00:00 |                700 |                     1 |              450 |                   0 | 20210821004511300 |   00451 |         700 | 2021-01-11 13:22:09 |
+----+----------+---------------------+--------------------+-----------------------+------------------+---------------------+----------+---------+-------------+---------------------+


2.

import React from 'react';

function TicketInput() {
  return (
    <div className="trip-finder">
      <div className="trip-finder-content">
        <div className="trip-finder-header">Bus ticets</div>
        <div className="trip-finder-form">
          <div className="input-wrapper">
            <span><i class="fas fa-search"><label for="time">Choose time</label>
<select name="time" id="time">
  <option value="18:00FromAtoB">18:00 From A to B</option>
  <option value="18:30FromAtoB">18:30 From A to B</option>
  <option value="18:45FromAtoB">18:45 From A to B</option>
  <option value="19:00FromAtoB">19:00 From A to B</option>
  <option value="19:15FromAtoB">19:15 From A to B</option>
  <option value="21:00FromAtoB">21:00 From A to B</option>
  <option value="18:30FromBToA">18:30 From B To A</option>
  <option value="18:45FromBToA">18:45 From B To A</option>
  <option value="19:00FromBToA">19:00 From B To A</option>
  <option value="19:15FromBToA">19:15 From B To A</option>
  <option value="19:35FromBToA">19:35 From B To A</option>
  <option value="21:50FromBToA">21:50 From B To A</option>
  <option value="21:55FromBToA">21:55 From B To A</option>
</select></i></span>
            <input className="full-width" placeholder="Search for trips"></input>
          </div>
          <div className="input-wrapper">
            <span><i class="fas fa-calendar-alt"></i></span>
            <select name="route" id="route">
  <option value="fromAToB">From B to A</option>
  <option value="fromAtToB">From A to B</option>
  <option value="roundway">Round way</option>
</select>
          </div>
          <div className="flex">
          <div className="input-wrapper">
          <label for="num">Number of Tickets</label>
<input id="num">
<button>Adults</button>
            <input className="full-width" placeholder="Passengers"></input>
        </div>
      </div>
    </div>
  )
}

export default TicketInput;

