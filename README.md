# DATABASE FIRST

## TRACCIA

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
potete usare una tabellina markdown o un semplice file di testo se vi riesce più comodo!
Mi raccomando: quello che ci interessa sono: il nome della colonna, il tipo di dato ed eventuali attributi!
Esempio:
COLONNA | TIPO | ATTRIBUTI
-- | -- | --
marca | varchar(50) | NOT NULL
modello | varchar(50) | NOT NULL
ecc..

## SVOLGIMENTO

| COLONNA     | TIPO         | ATTRIBUTI                   |
| ----------- | ------------ | --------------------------- |
| id_auto     | bigint       | PRIMATY KEY, AUTO_INCREMENT |
| img         | text         | NOTNULL                     |
| brand       | varchar(50)  | NOTNULL                     |
| model       | varchar(50)  | NOTNULL                     |
| manufacture | year         | NOTNULL                     |
| km          | int          | NULL,UNSIGNED               |
| fuel        | char(1)      | NOTNULL                     |
| info        | text         | NULL                        |
| price       | decimal(7,2) | NULL                        |

fuel:
D (diesel)
G (gasoline)
E (elettric)
H (hybrid)
