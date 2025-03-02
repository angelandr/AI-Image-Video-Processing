# AI-Image-Video-Processing
Repo skirtas "Vaizdų analizės" namų darbams. Detali info apie kiekvieno sprendimą yra patalpinta atitinkamuose aplankuose README failuose.

![Снимок экрана 2025-03-01 224545](https://github.com/user-attachments/assets/70b85fd2-c4fe-4c88-9c3b-e5479d8ec2b0)
![Снимок экрана 2025-02-26 113558](https://github.com/user-attachments/assets/da5319f6-2882-4c0a-9a99-81d84b587c46)
![Снимок экрана 2025-02-26 121705](https://github.com/user-attachments/assets/6a5618fb-022d-4560-b366-0630ce1cec84)

![Снимок экрана 2025-03-02 152043](https://github.com/user-attachments/assets/0c974684-7c0f-4553-865e-a231d566e884)
![Снимок экрана 2025-03-02 193339](https://github.com/user-attachments/assets/77ea236b-ac6c-414d-ab5d-c519422dacce)

ND1. Užduotis

Sukurti Python pagrindu veikiančią programą, kuri:

    1. Nuskaitytų pateiktą medicininį vaizdą ir atliktų įvairias duomenų augmentacijos operacijas (pvz., sukimą, mastelio keitimą, triukšmo pridėjimą, kontrasto modifikavimą, sintetinį duomenų generavimą).
    2. Naudodama iš anksto apmokytą konvoliucinį neuroninį tinklą, atliktų medicininio vaizdo analizę ir objektų ar anomalijų aptikimą tiek originaliame, tiek sugeneruotame duomenų rinkinyje.
    3. Įvertintų, kaip duomenų augmentacija ir generavimas paveikia modelio tikslumą, palygindama rezultatų kokybę prieš ir po duomenų išplėtimo.
    4. Sugeneruotų rezultatų ataskaitą su vizualine analize, tikslumo palyginimu tarp skirtingų augmentacijos metodų ir rekomendacijomis optimaliam duomenų generavimo integravimui.

 

ND2. Užduotis

Sukurti Python pagrindu veikiančią programą, kuri:

    1. Nuskaitytų pateiktą vaizdo įrašą.
    2. Identifikuotų ir sektų žmonių rankas vaizdo įraše.
    3. Sugeneruotų naują vaizdo įrašą su vizualiai pažymėtomis sekamų rankų vietomis kiekviename kadre.
    4. Automatiškai aptiktų ir pažymėtų momentus, kai rankos susikerta tarpusavyje, bei vizualiai tai pažymėtų vaizdo įraše.

 

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

DATA FROM:
https://www.kaggle.com/datasets/pkdarabi/brain-tumor-image-dataset-semantic-segmentation/data
https://www.kaggle.com/datasets/ultralytics/brain-tumor  (FOR FIRST TRIAL)
