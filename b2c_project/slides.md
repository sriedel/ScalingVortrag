!SLIDE bullets incremental

# Ziele #

* "Schöner"
* Mehr Mailtypen
* Verhaltenstrigger
* Inhalte dynamischer
* auch in Bestandsmails

!SLIDE bullets

# Ziele #

* Nachgeschoben: "Mehr PS"

!SLIDE bullets

# Zeitplan #

* Projektstart: Ende April 2009
* Erstes Going-Live: 01.07.2009

!SLIDE bullets incremental

# Änderungen #

* Grundstruktur beibehalten
* Logik vereinfachen

!SLIDE bullets

# Mehr PS #

* Threading
* :sendmail statt :smtp
* Offline Mailqueueing?
* QMQP?

!SLIDE bullets incremental

# Threading #

* schwach personalisiert: 10 -> 30 Mails/s 
* stark personalisiert: 7 -> 9 Mails/s

!SLIDE bullets incremental

# Exkursion: ActionMailer #

* SMTP langsam!
* delivery_method: :smtp vs. :sendmail
* keine persistente Verbindung
* QMQP nicht schneller

!SLIDE bullets

# Probleme im Produktionsmodus #

* Rails Eager Class Loading und Threads
* script/runner verschluckt Exceptions
* Debugging ohne Stacktraces: Suboptimal

