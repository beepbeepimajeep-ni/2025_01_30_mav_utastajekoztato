### MÁV utastájékoztató
Ez a projekt egy egyszerű webes felületet biztosít a MÁV vonatindulások és érkezések megjelenítésére. A weboldal **HTML** és **CSS** segítségével készült, és egy táblázatos formátumban jeleníti meg az aktuális menetrendet. 
![githublogo] (github_logo.png)

### 📌 Funkciók
    -🚝Közlekedő vonatok
    -🕐Érkezési idők
    -🎨Modern dizájn


### 🚀 Használat
Nyisd meg a `https://beepbeepimajeep-ni.github.io/2025_01_30_mav_utastajekoztato/` weboldalt az adatokhoz.

Élőben megtekinthető:
[🎟MÁV Utastájékoztató](https://beepbeepimajeep-ni.github.io/2025_01_30_mav_utastajekoztato/)

### 👩‍💻 Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV Utastájékoztató</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <table>
       <thead>
          <tr>
            <th> 8:43:13</th>
            <th>MÁV induló járatok</th>
            <th> </th>
            <th> </th>
            <th> </th>
            <th> <img src="mav.png" alt="Mav jele" width="75px" title="Máv logo"> 
            </th>
         </tr>

         <tr> 
            <th> Tervezett érkezés</th>
            <th> Érkezés</th>
            <th> Vonat</th>
            <th> Honnan</th>
            <th> Hova</th>
            <th> Vágány</th>
         </tr>
        </thead>
        ```
        ## 🎁 CSS stílusok
        ```css
        table {
        border: 1px solid;
        background-color: rgb(122, 119, 85);
        /* color: chartreuse; betűszín */
            font-family: 'Courier New', Courier, monospace;
        /* betűtípus */
            font-size: larger; /* betűméret */
         }
        td{
            background-color: bisque;
    
     }
        th {
            border-collapse: collapse;
            border: 1px solid;
     }
     ```

     ###🔧 Fejlesztési lehetőségek
     - [ ] 🔁 Adatbetöltés API-n keresztül
     - [ ] 🔍 Keresési lehetőségek
     - [x] 📱 Reszponzív megjelenítés mobileszközökre