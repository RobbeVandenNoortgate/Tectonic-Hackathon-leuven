# Tectonic-Hackathon-leuven
gaten in text
cross reference
maw fact check
knowledge graph zoals palantir --> knooppunten 
wettelijk nog ok
doelgroep
evergreen checkmark(altijd reliable)
aan wie vragen stellen 


Hoe het werkt (Zonder AI Agents of Search Engines):

Deterministische Metadata & Trust Metric:
Elk document of HR-artikel krijgt een "Trust Score" op basis van vaste parameters:
Datum van de laatste review (bijv. Elke 6 maanden moet een beleid herzien worden).
Sponsor/Eigenaar (Wie is de inhoudelijk expert binnen de organisatie?).
Sectiespecificiteit (Voor wie geldt dit: Bedienden, Arbeiders, Belgium-only?).
Resultaat: Als iemand zoekt, ziet hij direct een groen vinkje ("Up-to-date - 98% Vertrouwd") of een rode waarschuwing ("Verouderd sinds 2024 - Vraag update aan bij Sarah K.").
Expert Routing System (Human-in-the-loop):
Als een gebruiker op een kennispagina leest en informatie ontbreekt (Knowledge Gap), is er een knop: "Meld een gat in deze kennis".
Het systeem stuurt via een eenvoudige webhook/database-trigger direct een taak door naar de toegewezen expert van die specifieke categorie.
Inzet van Hackathon Partners (Zonder Agents/Search):
ElevenLabs: Voeg een knop "Luister naar deze policy" toe. Het zet de vaste tekst om in audio via de Text-to-Speech API (zonder tussenkomst van AI-agents).
Google Cloud: Gebruik Cloud SQL / Firestore en Cloud Run om de applicatie supersnel en schaalbaar te hosten.
Aikido: Omdat je met rollen en rechten werkt (bijv. 'Werknemer' vs 'HR Admin'), test Aikido je code op Authorization/IDOR-kwetsbaarheden.
