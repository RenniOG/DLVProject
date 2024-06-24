# Overview

Text

<br>

## EDBs

### Events

* event(event_name, event_time)
* expected(event_name) ???
* 


### Rooms

* room(room)
* capacity(room, capacity)


### Deduced/Misc

* breaks(day, starts, time)
* importance(event, importance) 
* day(day, start, end)
* speaker(speaker, event, order, time)
* speech(speaker, speech)

## IDB

### Rules

* 

### Hard Constraints 

* Conferences cannot be scheduled during break periods
:- scheduled(
* Speakers cannot be scheduled with overlapping conferences (or speeches?)

### Weak Constraints

* Conferences are spread out
* As few conferences at a time as possible
* 


## Final output predicates in sets for each event
* scheduled(event, start, length, room)
* speaker(speaker, start, end, speech)
* break(start, end, room).

