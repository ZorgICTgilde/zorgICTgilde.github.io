# ZorgICTgilde Website

De officiële website voor het **ZorgICTgilde**, gebouwd met [Astro](https://astro.build/) en gehost via GitHub Pages.

## 🚀 Project Structuur

Het project volgt de standaard Astro-structuur:

- `public/`: Statische bestanden (afbeeldingen, favicons, etc.)
- `src/components/`: Herbruikbare UI-componenten
- `src/content/`: Markdown / MDX content (pagina's, artikelen)
- `src/layouts/`: Pagina layouts
- `src/pages/`: Astro routes en pagina-templates

## 🛠 Lokale Ontwikkeling

Om het project lokaal op te starten, voer je de volgende opdrachten uit in je terminal:

1. **Afhankelijkheden installeren:**
   pnpm install

2. **Ontwikkelserver starten:**
   pnpm dev
   De website is vervolgens lokaal te bekijken op `http://localhost:4321`.

3. **Productie build testen:**
   pnpm build

4. **Preview van de productie build:**
   pnpm preview

## 📄 Content Aanpassen

Inhoudelijke pagina's kun je aanpassen in de map `src/content/`. Afbeeldingen die in de content gebruikt worden, kunnen geplaatst worden in de map `public/images/`.

## 📜 Licentie

Dit project is gebaseerd op een open-source sjabloon en valt onder de [MIT Licentie](LICENSE).