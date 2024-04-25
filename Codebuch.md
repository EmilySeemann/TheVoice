# Karrierewege der The Voice of Germany FinalistInnen

## Welche Verbindungen bestehen zwischen den FinalistInnen und anderen KünstlerInnen, ProduzentInnen, SongwriterInnen, Labels und/oder anderen Shows?

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# Edge-Attribute

**from**
- initiierender Knoten, in diesem Fall: Finalist/Coach einer The Voice of Germany Staffel (Staffel 1 bis 13), Staffel/TV-Show 

**to**
- erhaltender Knoten, in diesem Fall: Coach, Plattenlabel, Producer, andere Sänger(mit denen die Kandidaten an einem Lied beteiligt waren), andere TV-Shows

**relation**
- definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten, in diesem Fall:

1 = Person hat als Kandidat teilgenommen (gilt sowohl für The Voice, als auch für andere Shows) 

2 = Person hat als Coach teilgenommen (gilt sowohl für The Voice, als auch für andere Shows) 

3 = Kandidat-Kandidat-Beziehung (Kandidaten haben in der gleichen Staffel einer selben Show teilgenommen)

4 = Coach-Kandidat-Beziehung

5 = Arbeitsverhältnis (Kollaboration oder Zusammenarbeit an einem gemeinsamen Projekt/Song/Show/etc. , Beispiel: Ivy Quainoo hatte einen Gesangsauftritt bei Schlag den Raab)

**year**
- Wann hatten die Akteure (impliziert auch Shows) ab The Voice das erste Mal miteinander Kontakt?
- Jahreszahl wird mit vier Ziffern angegeben 


# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird:
- ID setzt sich zusammen aus dem ersten Buchstaben des Vor- und Nachnamens (z.B. Michael Schulte: ms)
- Wenn es die ID schon gibt, setzt sich die ID aus den ersten zwei Buchstaben des Vornamens und dem ersten Buchstaben des Nachnamens zusammen (z.B. Max Herre: mah)
- Wenn der Name nur aus einem Wort besteht, dann werden die ersten drei Buchstaben des Wortes verwendet (z.B. Nena: nen)
- Plattenlabels werden immer mit den ersten drei Buchstaben des ersten Wortes identifiziert (z.B. Motor Music: mot)
- Shows werden immer mit den ersten vier Buchstaben des ersten Wortes identifiziert (z.B. The Voice Kids: thev)
- Wenn einzelne IDs nicht nach den oben genannten Regeln kodiert werden können, weil es sonst zu ID-Dopplungen kommt, kann die ID frei gewählt werden. Diese Ausnahmen müssen jedoch in unserer Liste "Ausnahmen IDs" vermerkt werden.

**name**
- Name oder Bezeichnung des Knotens

**type**
-  Unterscheidung des Knotentyps (wir beziehen uns hier auf die Rolle, die die jeweilige Person in unserem Netzwerk als erstes hatte):

1 = Person 

2 = Organisation

**roles**
- Unterscheidung der jeweiligen Rolle eines Knotens: 

1 = Kandidat (gilt für egal welche Show)

2 = Plattenlabel

3 = Show (The Voice of Germany, andere Show, wie Sing meinen Song, Reality TV, ESC, DSDS)

4 = Coach/Juror (gilt für egal welche Show)

5 = Musikschöpfer (Producer, andere Sänger, Songwriter)

6 = Staffel (bezieht sich nur auf The Voice of Germany)

**sex**
-  Geschlecht der Akteure:

1 = weiblich

2 = männlich 

3 = divers (gilt auch für gemischte Teams)

**showkategorie**
- Um welche Art von Show handelt es sich?

1 = Musikshows (The Voice Kids, ESC, Sing meinen Song, The Masked Singer, DSDS)

2 = Realityshows (Are you the one, Love Island, Bachelor/Bachelorette, Ex on the Beach, Dschungelcamp, etc... 

3 = Fernsehen/Film (Schauspiel)

**charts**
- Wie viele Songs waren in den deutschen Top 100 Single- und Album-Charts?

1 = 0 Songs in den deutschen Charts

2 = 1-3 Songs in den deutschen Charts

3 = 4-6 Songs in den deutschen Charts

4 = Mehr als 6 Songs in den deutschen Charts

**platz**
- Welchen Platz hat der Kandidat im Finale von The Voice of Germany belegt?

1 = Platz 1

2 = Platz 2

3 = Platz 3

4 = Platz 4 

5 = Platz 5 

**Spotify**
- Wie viele monatliche Hörer haben die Knoten auf Spotify? (Stand Februar 2024)
- Monatliche Hörer werden als Ziffer ohne Punkte oder Kommas angegeben (z.B. 5,8 Millionen: 5800000/ z.B. 23.011: 23011) 

**Instagram**
- Wie viele Instagram Follower haben die Knoten? (Stand Februar 2024)
- Follower werden als Ziffer ohne Punkte oder Kommas angegeben (z.B. 374 Tsd: 374000)










