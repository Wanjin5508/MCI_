# Aufgabe 4.3

## 4.3.2

### Taste / Bedienelemente
- operate
- tapeIn
- record
- stop_eject. --> 弹出
- rewind --> 倒带
- play
- pause
- fastForward

### Zustand
insgesamt 14 Zustände + 48 Transitionen
1. ausgeschaltet
2. eingeschaltet
3. tape eingelegt
4. kein Tape eingelegt
5. wiedergebend
6. beschleunigte Wiedergabe
7. zurückgehende Wiedergabe
8. angehaltene Wiedergabe
9. vorgespultes Tape
10. zurückgespultes Tape
11. beendete Wiedergabe
12. normaler Modus der Aufnahme
13. automatischer Modus der Aufnahme
14. pausierte Aufnahme


### Bedienung
*Operate*: Ein- und Ausschalten. 
**Ausschalten ist jederzeit möglich**
*Tape in*: kann auch Einschalten

#### Tape wiederzugeben:
- Voraussetzungen:
	1. ein Tape eingelegt ist
	2. Gerät eingeschaltet ist

noch kein Tape --> *Tape in*

*play*: wiedergeben 
- -> wiedergebend -> *fast forward*: beschleunigte Wiedergabe 
	- --> nochmal *play*: normales Tempo
	- --> *pause*: angehaltene Wiedergabe
- -> wiedergebend -> *rewind*: zurückgehende Wiedergabe
	- --> nochmal *play*: normales Tempo
	- --> *pause*: angehaltene Wiedergabe

**kein tape eingelegt / angehaltene Wiedergabe:**
kann man auch *fast forward* und *rewind* betätigen:
*fast forward*  -> vorgespultes Tape -> *Stop/Eject* --> originaler Zustand (保留暂停状态, 仅仅是取消快进和快退, 并不能恢复正常播放)
*rewind* -> zurückgespultes Tape --> *Stop/Eject*  --> ..

5, 6, 7, 8 -> *Stop/Eject* -> beendete Wiedergabe

#### Aufnahme eines Tapes und Aufnahmesteuerung
- Vor der Aufnahme: 
	- ein Tape eingelegt
	- Gerät eingeschaltet
	- kein Vorgang der Wiedergabesteuerung (wiedergebend, angehaltene Wiedergabe, vor- und zurückgespultes Tape)

eingeschaltet -> Tape einlegend -> *Record* -> normaler Modus der Aufnahme -> *Record* -> automatischer Modus der Aufnahme ---> in 30 min automatisch stoppen

Aufnahme-Zustände (12, 13) -> *Pause* -> pausierte Aufnahme --> *Play* -> 12 oder 13

normaler Modus der Aufnahme --> pausierte Aufnahme -> *Record* -> automatischer Modus der Aufnahme

12, 13, 14 -> *Stop/Eject* -> Zustand vor der Aufnahme (**tape eingelegt**)

#### Entnahme des Tapes
Voraussetzung: Ein eingeschaltetes Gerät darf keine Wiedergabe oder Aufnahme erfolgen, inkl.Pausieren
-> d.h. Wiedergabe oder Aufnahme muss beendet werden, um das Tape zu entnehmen

tape eingelegt -> *Stop/Eject* -> kein Tape eingelegt


