# FiveVerstMapParse

## About
Sample python notebook for parsing 5verst map html. (5verst is a Russian successor of Parkrun)

## Подробнее
Это была попытка добавить старты "5 Верст" на Яндекс.Карты.

* Я отправил в Яндекс.Карты предложение добавить старты "5 Верст" (Ticket#23071505492780174)
* В ответ мне предложили сообщить им координаты всех 100+ стартов.
* В результате родилась данная программа. Она регуляркой достает из [Пяти Верст](https://5verst.ru/events/) инфу о стартах и сохраняет их в JSON
* Через неделю специалисты Я.Карт сообщили, что не смогут отметить точки старта "5 верст" из-за специфики мероприятия.

## Warning! Bug in Github Jupiter Viewer!

Complex string in Python renders incorrectly in Jupiter notebook preview.

Regexp expression may be damaged when viewing in github preview.

Real code contain a string literal: `'name:\s*"(?P<name>.*?)".*coord:\s*"(?P<coord>.*?)".*url:\s*"(?P<url>.*?)"'`

Preview renders it as: `'name:\s*"(?P.*?)".*coord:\s*"(?P.*?)".*url:\s*"(?P.*?)"'`

It skips words in angular brackets `<name>`, `<coord>`, `<url>`

Ticket [2256084](https://support.github.com/ticket/personal/0/2256084)
