# KlusKompas — eerste versie

Gratis mobiele webapp voor persoonlijke klusvragen.

## Wat werkt
- Vragen over klussen invoeren
- Interactieve demo: zoldervloer egaliseren, met vervolgvragen over ondergrond, vloerafwerking, hoogteverschil, vloerverwarming en vocht
- Voorwaardelijk stappenplan, aandachtspunten en theoretisch verbruiksvoorbeeld
- Klussen bewaren in de browser van hetzelfde apparaat
- Eigen foto bij een AI-vraag toevoegen
- Optionele Gemini API-koppeling met **een eigen API-sleutel** voor vrije AI-vragen

## Gratis publiceren via GitHub Pages
Ga naar **Settings → Pages → Build and deployment → Source: Deploy from a branch**. Kies **Branch: main**, **Folder: / (root)** en klik **Save**.

Daarna is de website in principe beschikbaar op: https://rsb-14.github.io/Kluskompas/

## Belangrijk
De ingebouwde demonstratie doet geen live fabrikantcontrole of wettelijke toetsing. Gebruik adviezen niet blind als uitvoerings- of veiligheidsgoedkeuring. Er is geen inlogaccount of synchronisatie. Gegevens worden lokaal opgeslagen.

## AI
De demo werkt zonder sleutel. Vrije AI-vragen vereisen een persoonlijke API-sleutel via https://aistudio.google.com/app/apikey. De browser stuurt vragen en eventuele foto's rechtstreeks naar Google. De API-sleutel wordt niet in de broncode gepubliceerd of permanent opgeslagen. Free-tier quota en verwerkingsvoorwaarden zijn van toepassing.

Deze versie is ontwikkeld zonder Lovable en zonder betaalde bouwcredits.