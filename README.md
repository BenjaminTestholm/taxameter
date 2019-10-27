# Taxameter.js
## En opgave i Strategy Pattern

### Opgave 1


Løsning:

I js filen "Taxameter" færdiggjorde jeg de nødvendige funktioner, så km og tid vil gå op og stoppe, samt indsat en funktion som vil udregne prisen når den bliver kaldt. Den bruger km og tid, samt pris per km, pris per tid og base pris.
Den får de forskellige pris værdier fra "krone-taxa", som giver den en funktion kaldet "PricePool" når den starter en ny "Taxameter". 

### Opgave 2
   

Løsning:

Jeg har lavet "krone-taxa-stor-vogn.js" og "krone-taxa-stor-vogn.html".
"krone-taxa-stor-vogn.html" matcher "krone-taxa.html", men har dog ændret det kaldet js script i "krone-taxa-stor-vogn.html" fra "krone-taxa.js" til "krone-taxa-stor-vogn.js"
"krone-taxa-stor-vogn.js" mathcer "krone-taxa.js", men har dog ændret priser til hver værdi til de givet priser i opgaven.

### Opgave 3
    
Løsning:
Jeg har lavet "city-bilen.js" og "city-bilen.html".
"city-bilen.html" matcher "krone-taxa.html", men har dog ændret det kaldet js script i "city-bilen.html" fra "krone-taxa.js" til "city-bilen.js"
"city-bilen.js" mathcer "krone-taxa.js", men har dog ændret priser til hver værdi til at stemme overens med de givet priser i opgaven.


### Opgave 4
    

Løsning:

Har indsat en rabat pris i "krone-taxa.js", som svare til 9-5 og ændret "Taxameter.js" CalcPrice til at udregne prisen for en normal tur og så sige minus rabat prisen.

### Bonus opgave 1 (overkommelig)
  

Løsning:

I "Taxameter.js" har jeg tilføjet en værdi af "Name", som får en værdi af "Name" fra den "PricePool" som bliver brugt til at skabe den. I "start.js" har jeg tilføjet et nyt element i constanten "elementer" kaldet "name", som lige efter elementer får dens "innerText" til at være det samme som værdien af "Name" fra "Taxameter.js"

Jeg har også opsat en alert som bliver kaldt når man trykker på start, som har den brugte beregningsmodel beskrivet, samt hvorvidt der er en rabat.

### Bonus opgave 2 (svær)
   
Løsning:

Jeg har lavet "elin-rejser.js" og "elin-rejser.html".
"elin-rejser.html" matcher "krone-taxa.html", men har dog ændret det kaldet js script i "elin-rejser.html" fra "krone-taxa.js" til "elin-rejser.js"
"elin-rejser.js" mathcer "krone-taxa.js", men har dog ændret priser til hver værdi til at stemme overens med de givet priser i opgaven. Har også tilføjet fire arrays som indholder de forskellige priser som "konkurrenterne" bruger. Når hver pris bliver kaldt fra "Taxameter.js" vil den se om en af "konkurrenternes" priser er lavere og hvis det er vil den nye pris være den mindste minus en. Hvis det er rabat, vil det være den størtes plus en.