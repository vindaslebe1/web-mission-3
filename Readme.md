Part 0-2  
[Link to video](https://youtu.be/l9qxVFuOlWU)
Part 3  
- Вопрос 1
select username from users
- Вопрос 2
select "from", count(*) as number_of_sent_messages from messages group by "from"**
- Вопрос 3
select "to" as username, count(*) as number_of_received_messages from messages group by "to" order 
