!SLIDE bullets incremental

# Stopgap #

* dedizierte Newsletter-Hardware
* 4 parallele Prozesse 
* Separierung nach bekanntem Schema

!SLIDE bullets

# Neue Hardware #

* 8 Core Xeon
* 8 GB RAM
* 2 RAID Arrays
* Separierung des Mail Spools

!SLIDE bullets

# Rails Migration! #

* Ruby 1.8.5 -> REE 1.8.6
* Rails 1.2.5 -> 2.3.3
* GetText auf 2.0.4

!SLIDE bullets incremental

# Migration Pains #

* Memory Leak in GetText
* Neues GetText nicht Reentrant
* Probleme mit ca. 1 in 1000 Mails
* Mutexe um Rendering Blöcke

!SLIDE bullets incremental

# Performance November #

* 1.010.000 Empfänger
* 7h 40min Laufzeit
* ca. 20 Mails/s
* Woohoo!

!SLIDE bullets incremental

# Performance Dezember #

* 1.060.000 Empfänger
* 8h 10min Laufzeit

!SLIDE bullets

* Woohoo?

!SLIDE bullets

# Upgrade Backend Server #

* Hardware Upgrade aller Prod Server
* Separierung DB und Matching

!SLIDE bullets

# Performance Januar #

* 1.1 Mio Empfänger
* 6h 15min Laufzeit
* ca. 27 Mails/s

!SLIDE bullets
# Performance Februar #

* 1.2 Mio Empfänger
* 6h 35min Laufzeit

