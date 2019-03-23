# Valgets kval

*Mål*: Hver spiller er en ... som ønsker å maksimere sin inntekt ved å stemme frem ulike satsningsområder.
Vinneren er spilleren med mest penger ved spillets slutt.

*Antall spillere*: 3-6

**Innhold**:
- 12 sett med områdekort fordelt på 8 områder (2 sett til hver spiller)
- 6 hvite stemmekonvolutter (1 til hver spiller)
- 12 blanke stemmekort
- Penger

## Forberedelser
Hver spiller starter med
- 2 av hvert områdekort (et sett til avstemming og et til prioritering)
- 1 hvit konvolutt
- 2 blanke stemmekort
- 6 penger

## Spillets gang
Spillet går i 5 runder der hver runde består av følgende trinn

### 0. Avstemmingsmetode
Standard: [Borda Count](https://en.wikipedia.org/wiki/Borda_count). Avansert spill: Den med lavest utbetaling i trinn 4 velger ny avstemmingsmetode, f.eks. [Approval Voting](https://en.wikipedia.org/wiki/Approval_voting).

### 1. Prioritering av satsningsområder
I første runde gjør hver spiller: 
- Velg fire av de åtte områdekortene. Dette er spillerens satsningsområder.
- Legg satsningsområdene i rekkefølge på bordet foran seg, primærområdet lengst fra deg.
- Når alle spillerne har lagt ned kortene snur alle primærområdet.

Resterende runder: Velg en eller ingen av to handlinger:
- Bytt rekkefølge på to av områdene på bordet
- Bytt ut et av de skjulte med et av de 4 områdene som ikke er på bordet.

### 2. Avstemming
Spillerne rangerer områdene fra topp til bunn i skjul og legger avstemmingen med alle de 8 områdekortene rangert i en hvit konvolutt.

### 3. Opptelling
De hvite konvoluttene stokkes og man legger frem stemmene.
Avgjør felles rangering ut fra avstemmingsmetode fra trinn 0.

### 4. Inntektsfordeling
(Hvis to eller flere områder får lik plassering, slås premiene for disse sammen og deles likt mellom seg, deretter forløper det som "normalt")
1. Fastsette premie: De tre øverste områdene i den felles rangeringen får følgende sum hver fra banken:
    1. Førsteplass: 3 x antall spillere
    2. Andreplass: 2 x antall spillere
    3. Tredjeplass: 1 x antall spillere
2. De resterende områder får en penge hver (som ikke blir betalt ut før området er blant topp tre).
3. De spillerne som ønsker kan nå velge om de vil åpne 2. og/eller 3. plassen sin for å få utbetalt premie. Denne plassen forblir åpen resten av spillet (eller skal det være et trekk å snu en plass).
4. Fordeling av premie: Hver av de tre øverste premiene fordeles slik:
```
A, A, B, A, A, B, C
```
der
```
A: 1 penge til alle som har området på 1.plass
B: 1 penge til alle som har området på en åpen 2.plass
C: 1 penge til alle som har området på en åpen 3.plass
```
Gjenta til premien er tom. Hvis man ikke kan fordele ut til alle som har samme plass, så går restpremien videre til neste plassering. 

## Idéer:
1. **Spillerpremie**: Hver spiller fordeler 6 (?) penger (fra egen lomme?) i de 8 premiepottene mellom trinn 1 og 2
2. **Progressiv premie**: Premiepotten fra banken økes med 1 (?) for hver runde?
3. **Rundehistorikk**: Skal områdene akkumulere noe for hver runde, slik at de "husker" resultatene for hver runde?
4. **Oppdrag**: Hver spiller trekker/velger et oppdragskort som gjelder etter siste runde, og som gir en ekstra utbetaling hvis man klarer oppdraget.
Eksempel på oppdrag:
    - Område X er på akkumulert sisteplass
    - Område X er ikke blant topp tre i siste runde
    - Område X har aldri hvert blant topp tre
    - Spilleren fikk ingen utbetaling i siste runde
5. **Bestikkelser**: Legges inn trinn 0.1 der spillerene kan sende svarte konvolutter anonymt til hverandre (krever at hver spiller har en skjult identitet som kun de kjenner til, og en offentlig identitet som de andre kan adressere). Konvolutten skal inneholde den offentlige identiteten til mottakeren (synlig i vinduskonvolutt), den skjulte identiteten til avsenderen (synlig i vindu), et ønske og en pengesum. Eksempler på ønsker kan være "ranger område A over B", "stem blankt". Mottaker kan da velge mellom:
    - Beholde pengene og utføre ønsket
    - Returnere konvolutten med hele innholdet
    - Offentligjøre innholdet
6. **Balansering**: Metode for å jevne ut forskjellen mellom erfarne og mindre erfarne spillere.

## Utfordringer:
- Ved å rangere alle kortene i en bunke er det ikke mulig å sette to områder på samme plass. Dette bør være mulig. Må man i tillegg til områdene ha nummerkort som indikerer plassering?
