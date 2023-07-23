# FiveVerstMapParse
Sample python notebook for parsing 5verst map html

## Warning! Bug in Github Jupiter Viewer!

Complex string in Python renders incorrectly in Jupiter notebook preview.

Regexp expression may be damaged when viewing in github preview.

Real code contain a string literal: `'name:\s*"(?P<name>.*?)".*coord:\s*"(?P<coord>.*?)".*url:\s*"(?P<url>.*?)"'`

Preview renders it as: `'name:\s*"(?P.*?)".*coord:\s*"(?P.*?)".*url:\s*"(?P.*?)"'`

It skips words in angular brackets `<name>`, `<coord>`, `<url>`

Ticket [2256084](https://support.github.com/ticket/personal/0/2256084)
