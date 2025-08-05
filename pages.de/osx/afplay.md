# afplay

> Command-Line Audio-Player.
> Weitere Informationen unter: <https://keith.github.io/xcode-man-pages/afplay.1.html>.

- Eine Audiodatei abspielen (wartet, bis die Wiedergabe beendet ist):

`afplay {{path/to/file}}`

- Eine Audiodatei mit doppelter Geschwindigkeit (Wiedergabegeschwindigkeit) abspielen:

`afplay --rate {{2}} {{path/to/file}}`

- Eine Audiodatei mit halber Geschwindigkeit abspielen:

`afplay --rate {{0.5}} {{path/to/file}}`

- Die ersten N Sekunden einer Audiodatei abspielen:

`afplay --time {{seconds}} {{path/to/file}}`
