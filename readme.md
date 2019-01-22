# pln
prolog life planner

poker player predictions

## schedule tasks for:
* [x] `number(N).`
* [x] `member(DS,[YEARS,MONTHS,DAYS]).`
* [ ] every `N` `DS` starting at `date/9`
	* [ ] `HOUR`, `MINUTE`, `SECOND` should never need to change, and should be anonymised for optimisation processing unless dependencies exist
	* [ ] 29ᵗʰ february; will goto 28ᵗʰ february during non leap years
* [x] `=(T,[HOUR,MINUTE,SECOND]).`; where `time(T1) = time(T2)` is possible
* [ ] between `time(T1)` and `time(T2)` every `N` `DS` starting at `date/9`
* [ ] between `time(T1)` and `time(T2)` every `NTH` day of the month starting at `date/9`
* [ ] between `time(T1)` and `time(T2)` every `NTH` weekday of the month starting at `date/9`
* [ ] every `NTH` day of the month starting at `date/9`
* [ ] every `NTH` weekday of the month starting at `date/9`
* [ ] every `NTH` day of the week starting at `date/9` **is** every `=(N,7)` `=(DS,DAYS)` starting at `date/9`
* [ ] some due dates can be scheduled earlier than due; due dates versus dead lines

## life rules:
* [ ] negative weather predictions = stock up on supplies depeding on the extremity of the predictions
* [ ] consumption of expired food = statistical probability of getting sick
