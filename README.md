# Volkstuinvereniging Lisserbroek 🌱

Conceptwebsite van **Volkstuinvereniging Lisserbroek** (Nederlandstalig, mobielvriendelijk).

## Pagina's
Home, Over ons, Onze tuinen, Nieuws & activiteiten, Lid worden, Fotogalerij en Contact.

## Afbeeldingen
In `assets/` staan tijdelijke SVG-illustraties zodat de website meteen bruikbaar is. De eerder door ChatGPT gemaakte originele illustraties zijn **nog niet naar GitHub overgezet**. Download de websitebestanden uit de chat (versie 3) en upload de volgende bestanden uit de map `assets/` naar de gelijknamige map van deze repository:

- `logo.webp`
- `welkom.webp`
- `samen.webp`
- `oogst.webp`
- `seizoenen.webp`

Zodra die bestanden er staan, gebruikt de site automatisch de originele illustraties; anders verschijnen de SVG-varianten.

## Contactgegevens
De vereniging heeft nog geen e-mailadres of domeinnaam. Vul gegevens later in bij `js/gegevens.js`. Er worden geen verzonnen adressen gepubliceerd.

## Website publiceren via GitHub Pages
1. Voeg desgewenst eerst de originele afbeeldingen toe.
2. Merge de pull request naar `main`.
3. Ga naar **Settings → Pages**.
4. Kies **Deploy from a branch**; selecteer `main` en **/(root)**.
5. De site verschijnt dan na verwerking op `https://volkstuin.github.io/website/`.

GitHub Pages publiceren kan een wijziging aan repository-instellingen en eventueel publieke zichtbaarheid vereisen, afhankelijk van het GitHub-abonnement. De repository is op dit moment privé; controleer daarom de beschikbare Pages-opties.

## Later aanpassen
Alle pagina's zijn losse HTML-bestanden. Opmaak staat in `css/style.css` en het menu en de fotogalerij in `js/main.js`.
