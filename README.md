# AI-Image-Video-Processing
Repo skirtas "Vaizdų analizės" namų darbams. Detali info apie kiekvieno sprendimą yra patalpinta atitinkamuose aplankuose README failuose.

 

ND1. Užduotis

Sukurti Python pagrindu veikiančią programą, kuri:

    Nuskaitytų pateiktą medicininį vaizdą ir atliktų įvairias duomenų augmentacijos operacijas (pvz., sukimą, mastelio keitimą, triukšmo pridėjimą, kontrasto modifikavimą, sintetinį duomenų generavimą).
    Naudodama iš anksto apmokytą konvoliucinį neuroninį tinklą, atliktų medicininio vaizdo analizę ir objektų ar anomalijų aptikimą tiek originaliame, tiek sugeneruotame duomenų rinkinyje.
    Įvertintų, kaip duomenų augmentacija ir generavimas paveikia modelio tikslumą, palygindama rezultatų kokybę prieš ir po duomenų išplėtimo.
    Sugeneruotų rezultatų ataskaitą su vizualine analize, tikslumo palyginimu tarp skirtingų augmentacijos metodų ir rekomendacijomis optimaliam duomenų generavimo integravimui.

 

ND2. Užduotis

Sukurti Python pagrindu veikiančią programą, kuri:

    Nuskaitytų pateiktą vaizdo įrašą.
    Identifikuotų ir sektų žmonių rankas vaizdo įraše.
    Sugeneruotų naują vaizdo įrašą su vizualiai pažymėtomis sekamų rankų vietomis kiekviename kadre.
    Automatiškai aptiktų ir pažymėtų momentus, kai rankos susikerta tarpusavyje, bei vizualiai tai pažymėtų vaizdo įraše.

 

ND3. Užduotis

Sukurti web sprendimą, leidžiantį vartotojams įkelti vaizdo duomenis ir gauti apdorotus rezultatus, naudojant virtualiame serveryje veikiantį dirbtinio intelekto modelį.

Reikalavimai užduočiai:

1.       Dirbtinio intelekto modelis:

    Pasirinktinai tas, kurį naudojote ND1 ar ND2.
    Modelis turi būti įdiegtas ir veikiantis virtualiame serveryje.

2.       API sukūrimas:

    Sukurti API, leidžiantį vartotojams pateikti vaizdo duomenis modeliui per HTTP užklausas.
    API turi grąžinti analizės rezultatus JSON formatu arba vaizdinę išvestį su pažymėtais objektais ar vaizdo apdorojimo rezultatais.

3.       Web sąsaja:

    Sukurti vartotojui patogią web sąsają (naudojant HTML, CSS, JavaScript, React, Flask ar Django), leidžiančią: 

        Įkelti vaizdo failus arba pateikti jų URL modeliui analizuoti.
        Matyti apdorotus rezultatus (pvz., su pažymėtais aptiktais objektais, prognozių balais ar segmentuotais vaizdais).

 

Reikalavimai ND pateikimui:

1. Programos kodas, įkeltas į studento sukurtą GitHub repozitoriją.

2. Nuotrauka ar vaizdo įrašas su rezultatais (pvz., sekamas objektas pažymėtas visuose rastuose kadruose).

3. 1 puslapio trukmės ataskaita (README), kuri turi apimti:

    Naudotus metodus ir bibliotekas.
    Sistemos veikimo aprašymą.
    Iškilusias problemas ir kaip jos buvo išspręstos.
    Sistemos paleidimo instrukcijas.

 

Vertinimo kriterijai:

1. Naujausių metodų taikymas (4 balai)

    4 balai – Pritaikytos moderniausios kompiuterinės regos technologijos (pvz., pažangūs neuroniniai tinklai, transformeriai, Diffusion modeliai).
    2 balai – Naudoti populiarūs, bet ne patys naujausi modeliai (pvz., CNN, U-Net, Faster R-CNN).
    0 balų – Naudoti tik tradiciniai metodai (pvz., edge detection, thresholding) be giluminio mokymosi (jei aktualu).

2. Kodo struktūra ir kokybė (2 balai):

    2 balai – Tvarkingas, komentuotas kodas, laikomasi gerų programavimo praktikų.
    1 balas – Kode trūksta struktūros arba komentarų, bet jis suprantamas.
    0 balų – Netvarkingas kodas, sunkiai suprantamas, trūksta dokumentacijos.

3. Rezultatų vizualizacija (2 balai):

    2 balai – Aiškiai pažymėti visi rasti veidai, vizualizacija estetiška.
    1 balas – Veidai pažymėti, bet vizualizacija galėtų būti aiškesnė arba trūksta estetinio pateikimo.
    0 balų – Vizualizacija neaiški arba jos nėra.

4. Ataskaita (README) ir dokumentacija (2 balai):

    2 balai – Aiškus, struktūruotas README su detaliomis instrukcijomis ir problemų aprašymu.
    1 balas – README pateiktas, bet informacija neišsami arba trūksta svarbių detalių.
    0 balų – README nėra arba jis nesuteikia reikalingos informacijos.
