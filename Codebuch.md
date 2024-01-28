# Karrierewege der The Voice of Germany Kandidaten

## Wer hat sich in der Musikbranche durch relevante Verbindungen zu anderen Künstlern, Produzenten, Labels und/oder anderen Show etabliert?

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# Edge-Attribute

**from**
- iniitierender Knoten, in diesem Fall: Finalist/Coach einer The Voice of Germany Staffel (Staffel 1 bis 13), Staffel/TV-Show 

**to**
- erhaltender Knoten, in diesem Fall: Coach, Plattenlabel, Producer, andere Sänger(mit denen die Kandidaten an einem Lied beteiligt waren), andere TV-Shows

**relation**
- definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten, in diesem Fall:

1 = Person hat als Kandidat teilgenommen (gilt sowohl für The Voice, als auch für andere Shows) 

2 = Person hat als Coach teilgenommen (gilt sowohl für The Voice, als auch für andere Shows) 

3 = Coach-Kandidat-Beziehung

4 = Arbeitsverhältnis

# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
- Name oder Bezeichnung des Knotens

**type**
-  Unterscheidung des Knotentyps:

1 = Kandidat

2 = Organisation (Plattenlabel)

3 = Show (andere Show, wie Sing meinen Song, Reality TV, ESC, DSDS)

4 = Coach 

5 = Andere (zum Beispiel Producer, andere Sänger, Songwriter)

**sex**
-  Geschlecht der Akteure:

1 = weiblich

2 = männlich 

3 = divers (gilt auch für gemischte Teams)

**staffel**
- In welcher Staffel hat der Kandidat/Coach teilgenommen (Staffel 1 bis 13)

**showkategorie**
- In welcher Art von Shows war der Kandidat nach The Voice?

1 = Musikshows - sowohl Kandidat als auch Juror (The Voice Kids, ESC, Sing meinen Song, The Masked Singer, DSDS)

2 = Realityshows (Are you the one, Love Island, Bachelor/Bachelorette, Ex on the Beach, Dschungelcamp, etc... )

**charts**
- Wie viele Songs waren in den deutschen Charts?

1 = 0 Songs in den deutschen Charts

2 = 1-3 Songs in den deutschen Charts

3 = 4-6 Songs in den deutschen Charts

4 = Mehr als 6 Songs in den deutschen Charts

**platz**
- Welchen Platz hat der Kandidat im Finale belegt?

1 = Platz 1

2 = Platz 2

3 = Platz 3

4 = Platz 4 

5 = Platz 5 










