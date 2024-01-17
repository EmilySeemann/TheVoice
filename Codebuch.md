# Karrierewege der The Voice of Germany Kandidaten

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# Edge-Attribute

**from**
- iniitierender Knoten, in diesem Fall: Halbfinalist/Coach einer The Voice of Germany Staffel (Staffel 1 bis 6) 

**to**
- erhaltender Knoten, in diesem Fall: Coach, Plattenlabel, Producer, andere TV-Shows

**relation**
- definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten, in diesem Fall:
  
1 = Kandidaten haben in derselben The Voice Staffel teilgenommen

2 = Coaches haben in derselben The Voice Staffel teilgenommen

3 = Arbeitsverhältnis

# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
- Name oder Bezeichnung des Knotens

**type**
-  Unterscheidung des Knotentyps:

1 = Person (Kandidat, Coach, Producer)

2 = Organisation (Plattenlabel)

3 = Show (andere Show, wie Sing meinen Song, Reality TV, ESC, DSDS)

**sex**
-  Geschlecht der Akteure:

1 = weiblich

2 = männlich 

3 = divers (gilt auch für gemischte Teams)

**staffel**
- In welcher Staffel hat der Kandidat/Coach teilgenommen (Staffel 1 bis 6)

**team**
- In welchem Team war der jeweilige Kandidat?
  
1 = The BossHoss

2 = Nena

3 = Rea Garvey

4 = Xavier Naidoo

5 = Max Herre 

6 = Samu Haber

7 = Fanta Vier 

8 = Stefanie Kloß

9 = Andreas Bourani

10 = Yvonne Catterfeld 

11 = Mark Forster

12 = Michael Patrick Kelly 

13 = Nico Santos 

14 = Alice Merton

15 = Sido

16 = Stefanie Kloß und Yvonne Catterfeld

17 = Samu Haber und Rea Garvey

18 = Michael Schulte

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










