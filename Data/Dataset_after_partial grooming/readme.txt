Please have a read this file.

For Covid dataset, I used what keiryn did. I couldn`t find his code(how he did grooming)
so I didn`t modify and just use it.

I tried to merged two dataset but it was not working well.
it will produce a lot of missing value as two dataset almost everything different.

so, I tried to grooming a bit more.

Firstly, I think in victimisation dataset, we only need date 
"March" , "April" ,"May" as they are corresponding with covid-19 Alert.level
So I filtered dataset that only keep those three months.
and additionally I added new column "Alert.Level" as if data month is March - lvl4 April - lvl3 May-lvl2

I did above thing, because I think our project purpose is we want to compare crime rate during lockdown,with previous year.

Also, I founds victim dataset, we are considering 5 different assault, but covid dataset we only have 4 different assault.
I think it`s better we just extract assault that both dataset have.
there are three common assault.

but still don`t know how should I handle 
"District"(from covid) column with "Terriory authority"(from victim)

------------------------------------
Maybe, I`m thinking wrong way or did wrong.
please let me know if I`m doing something really wrong.
I couldn`t write all the thing here, so maybe when we have a meeting again
I will try to talk. Thank you

