# DB First

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

## Indice

Ho deciso di usare un ID numerico incrementale e renderlo 'unique'

Questo per essere sicuro che ogni elemento del database abbia un indice unico anche qualora si aggiungesse un elemento.

## Not Null

Vista l' importanza dell' oggetto in vendita ho deciso di settare ogni valore a 'not null' in modo che in fase di acquisto il cliente abbia sempre tutte le informazioni a disposizione.

## Varchar()

Per ogni varchar ho fatto una ricerca per avere le lunghezze massime delle stringhe.

Per evitare casi speciali ho comunque aumentato la lunghezza della stringa.

plate -> la targa, pur contntndo numeri, è una stringa (unique)

registration number -> la targa, pur contntndo numeri, è una stringa (unique)

brand

car model

color

engine power supply

trasmission

country of production

## Double()

vehicle displatement

km

horse power

## Decimal()

price -> essendo il prezzo una proprietà importante ho ritenuto necessario usare decimal per avere un arrotondamento più accurato

## Year

date of production
