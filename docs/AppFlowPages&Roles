# App Flow, Pages & Roles – Fredagsbettet

## 🧭 Översiktligt flöde

1. Spelare öppnar appen och loggar in med namn + PIN
2. Landar i Fredagsfoajén: ser fråga, countdown, statistik
3. Skickar sin gissning
4. Admin (slipsmästaren) lägger in rätt svar
5. Resultatflöde triggas, poäng räknas
6. Tabell uppdateras, ny vecka väntar

## 📄 Sidor och funktioner

### 🔐 **Slipsportalen (Login)**

* Dropdown med namn (auto-filter)
* PIN-input
* Felhantering, ev. PIN-återställning via admin

### 🏛 **Fredagsfoajén (Huvudsidan)**

* Visa veckans fråga, countdown till svarsstopp
* Status: "x av y har svarat"
* Din placering, historik, slipsinnehavare
* Citat från lagboken / röstning på klädsel

### 🎩 **Slipsmästarpanel (Admin)**

* Skapa ny fråga
* Se inkomna svar
* Registrera rätt svar → triggar resultat
* Resultatflöde: avslöja en spelare i taget (i felordning)
* Arkivera fråga och poäng

### 🧾 **Poäng & Historik**

* Topp 5-tabell (live)
* Poänghistorik per vecka
* Profilvisning med säsongsstatistik
* "Veckans största felgissning™"

### ⚙️ **Admininställningar (säsong & spelare)**

* Skapa ny säsong (namn, datumintervall)
* Markera inaktiva spelare
* Export av säsongsdata
* PIN-hantering

## 👥 Roller

### 👤 Spelare

* Loggar in med PIN
* Ser fråga, svarar, följer resultat
* Har personlig poängstatistik

### 🎩 Slipsmästare (Admin)

* Full åtkomst till skapa/hantera fråga
* Kan se alla svar
* Kan justera spelardata

## 🔄 Navigationslogik

* Inloggad spelare går alltid till Fredagsfoajén
* Admin får access till extra meny (skapa fråga etc.)
* Resultatflödet låses tills rätt svar är registrerat

## 🔔 Extra flöden

* Ny spelare onboarding: sätt PIN + svär eden (v2)
* Säsongsbyte → nollställning av poäng, ny räknare
* Om ingen fråga skapas en vecka → inget sker, veckan hoppas över
