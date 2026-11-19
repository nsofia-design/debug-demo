I denne opgave arbejdede jeg med debugging i IntelliJ IDEA.

Jeg startede med at bruge breakpoints til at stoppe programmet på de bestemte linjer jeg ville ændre.

Så brugte jeg debuggeren til at undersøge variabler og følge programmets flow.

Jeg fandt en fejl i placeringen af vandrette og lodrette skibe, som jeg rettede ved at ændre getRandomInteger(1) til getRandomInteger(2).

Så fandt jeg en fejl i metoden isSunk() og ændrede > til >=.

Dernæst skulle jeg undersøge fejlen ArrayIndexOutOfBoundsException. Den fik jeg rettet - placeringen af skibene, så de holder sig inden for spillepladen.

Til sidst testede jeg programmet igen og kontrollerede, at det kunne bygges

![01_Undersøgelse_med_Evaluate_Expression.png](../../Udvalgte_Debugging_Screenshots/01_Unders%C3%B8gelse_med_Evaluate_Expression.png)
![02_Debugging_af_hitCount.png](../../Udvalgte_Debugging_Screenshots/02_Debugging_af_hitCount.png)
![03_Rettelse_af_isSunk.png](../../Udvalgte_Debugging_Screenshots/03_Rettelse_af_isSunk.png)
![04_Rettelse_af_skibets_placering.png](../../Udvalgte_Debugging_Screenshots/04_Rettelse_af_skibets_placering.png)![05_Afsluttende_test.png](../../Udvalgte_Debugging_Screenshots/05_Afsluttende_test.png)