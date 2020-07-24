# Datensatz Kohlekommision # 
Codebuch Stand 2020-07-24
erstellt von Sebastian Br�ne (sb274@hdm-stuttgart.de)

## Inhalt 
- Edgelits
- Notelist

# Ursprung der Datenerhebung 

Das Netzwerk ist ein *gerichtetes two-mode Netzwerk*. 

# Edge-Attribute 

**from**
(ID Mitglied der Kommision)

**to** 
(alle Mitgliedschaften der Person, soweit recherchierbar, dazu geh�rt z.B. politische Partei, 

# Node-Attribute (Alles nicht zur verf�gungstehenden Informationen werden mit "99" gekennzeichnet)

**id**
eindeutige Identifikation jedes einzelnen Knotens 

**name**
Der Name dient der Beschriftung des Kontens

**type** 
Unterscheidung zwischen Person und Organization:
0 = person,
1 = organization,

**sex**
Geschlecht der Mitglieder der Kohlekommission:
1 = m�nnlich,
2 = weiblich,
3 = divers, 

**age**
Alter der Mitglieder der Kohlekommission:
1 = bis 30 Jahre,
2 = 31 - 40 Jahre,
3 = 41 - 50 Jahre,
4 = 51 - 60 Jahre,
5 = 61 - 70 Jahre,
6 = ab 71 Jahre,

**party**
Mitgliedschaft in politischer Parte:
1 = CDU/CSU,
2 = SPD,
3 = Gr�ne,
4 = Linke,
5 = FDP,
6 = AfD,

**representation**
Funktion innerhalb der Kommission: 
1 = Politik,
2 = Wirtschaft,
3 = Gewerkschaft,
4 = Umwelt,
5 = Region, 
6 = Wissenschaft,

**position**
Position in der Kohlekommission:
1 = Vorsitz,
2 = Mitglied,
3 = kein Stimmrecht,

**State**
Bundesl�nder: 
BW = Baden-W�rttemberg,	
BY = Bayern,
BE = Berlin,
BB = Brandenburg,
HB = Bremen,
HH = Hamburg,
HE = Hessen,
MV = Mecklenburg-Vorpommern,
NI = Niedersachsen,
NW = Nordrhein-Westfalen,
RP = Rheinland-Pfalz,
SL = Saarland,
SN = Sachsen,
ST = Sachsen-Anhat,
SH = Schleswig-Holstein,
TH = Th�ringen,
