# Aufgabe B1

Line 52 - pressClearKey()
* Code unterscheidet nicht ob Taste ein- oder zweimal gedrückt wird (C- bzw. CE-Taste). Sobald die Taste gedrückt wird, wird "0" angezeigt/ausgegeben.

Line 120
* Wenn zweimal hintereinander "=" gedrückt wird ohne weiteren Operanden, löst das zweite drücken die IllegalArgumentException aus. Das beschriebene "es passiert nichts" ist falsch.
* Wenn weiterer Operand hinzugefügt wird, dann wird er IMMER mit dem latestValue verrechnet.
Bsp.:
So sollte es sein: 5 + 6 = 11; 11 + 6 = 17 | So ist es: 5 + 6 = 11; 5 + 11 = 16