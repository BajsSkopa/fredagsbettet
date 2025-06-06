Masterplan – Fredagsbettet

🧭 App Overview and Objectives

Fredagsbettet är en ceremoniell spelplattform för en sluten vänkrets (t.ex. KTH-studenter) där en veckovis ritual iscensätts: en "slipsmästare" ställer en numerisk fråga, alla andra gissar, och poäng delas ut enligt ett inre, halvt skämtsamt men högtidligt regelverk. Plattformen ska förstärka känslan av tradition, spex och ceremoni – och samtidigt vara ett smart, automatiserat verktyg för poängberäkning och säsongshantering.

🎯 Target Audience

Studenter (främst KTH) i en sluten vänkrets

~10–25 deltagare som gillar ritualer, humor, statistik

Användare som triggas av återkommande ceremonier, internkultur

🚀 Core Features

Slipsportalen: Inloggning med namn + PIN

Fredagsfoajén: Fråga, countdown, statistik, citat, stiligt UI

Slipsmästarpanel: Admin skapar fråga, registrerar svar, utlöser resultat

Poängsystem med bonusar och historik

Säsongshantering: skapa/arkivera, hoppa över lov, auto-numrering

Spelarhantering: onboarding, inaktivering, export

🧱 Technical Stack (Recommended)

Frontend: Vite + React (TypeScript), Tailwind CSS, shadcn/ui

Backend: Supabase (auth, storage, realtime)

Authentication: Namn + PIN, ev. Google OAuth för admin

📐 Conceptual Data Model

Users: namn, PIN, aktiv/inaktiv, profilikon, historik

Questions: text, skapad av, vecka/säsong, rätt svar, gissningar

Guesses: user_id, question_id, värde, timestamp

Seasons: namn, start/slut, aktiv, lista över fredagsbett

Points: auto-beräknat per vecka, inkluderar bonus

🎨 UI Principles

Ceremoniellt: mörka färger, serif-rubriker, glödande detaljer

Mobilförst: enkel att hantera i mobilen på fredag lunch

Humor + högtidlighet i harmoni

Hierarki & Fokus, färgviktning

🔐 Security Considerations

Inloggning med PIN (kortlivad sessions-token)

Adminåtkomst begränsad till slipsmästare (ev. extra verifiering)

Säsong och användardata hålls isolerat i grupper

📆 Development Milestones

MVP (v1)

Inloggning (Namn + PIN)

Adminpanel: skapa fråga, se svar, lägga in rätt svar

Resultatflöde + auto-poäng

Säsongsskapande och gissningar

v2

Ed-ceremoni för nya användare

AI-insikter och sammanfattningar

Klädkodjusteringar, stilpoäng, emoji-profiler

⚠️ Potential Challenges

UI-timing (ex. countdown + svarsflöde)

PIN-login utan email – hantering av sessions och säkerhet

Automatiskt hopp över lovveckor kräver kalenderlogik

🌱 Future Expansion

Veckans meme / användargenererat content

Arkiv med slipsfrågor från tidigare terminer

Export till PDF/Notion/HTML för minnesvärde

