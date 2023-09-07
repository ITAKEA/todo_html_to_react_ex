# Øvelse: Omdan en HTML Todo Liste til en React App

## Mål
I denne øvelse vil I arbejde med at omdanne en eksisterende HTML Todo Liste til en React App. I vil få erfaring med at oprette og styre state i React samt håndtere begivenheder som klik og form indsendelser.

## Forudsætninger
- Grundlæggende kendskab til HTML, CSS og JavaScript.
- Grundlæggende forståelse af React og JSX.

## Materialer
- Startkode: En simpel Todo Liste skrevet i HTML, CSS (Bootstrap) og JavaScript. (Du kan bruge den HTML kode, jeg oprindeligt leverede).
- Node.js og npm installeret på din computer.
- En kode editor (f.eks. Visual Studio Code).

## Instruktioner

### Oprettelse af en ny React App
1. Brug Create React App til at oprette en ny React app med kommandoen `npx create-react-app react-todo-list`.
2. Gå ind i din nye app-mappe med kommandoen `cd react-todo-list`.

### Installation af Bootstrap
1. Installer Bootstrap i din React app med kommandoen `npm install bootstrap`.
2. Inkluder Bootstrap i din app ved at tilføje følgende linje i `src/index.css`: `@import '~bootstrap/dist/css/bootstrap.min.css';`.

### Oprettelse af TodoList Komponent
1. Opret en ny fil `TodoList.js` i `src` mappen.
2. I `TodoList.js`, opret en funktionel komponent `TodoList` der returnerer en JSX repræsentation af den oprindelige HTML-struktur (du kan tage udgangspunkt i den HTML-struktur, der blev leveret i startkoden).

### Tilføjelse af State og Funktioner
1. Brug `useState` hook til at oprette state variabler for din todo liste og input-feltet.
2. Implementer funktionerne `addTodo`, `toggleDone` og `removeTodo` for at håndtere henholdsvis tilføjelse af nye todos, markering af todos som fuldført, og fjernelse af todos.

### Rendering af Todo Liste
1. Brug `map` funktionen til at gennemgå alle todos og vise dem i en liste med en checkbox og en "fjern" knap for hver todo.
2. Tilføj en `key` prop til hvert element i listen for at hjælpe React med at identificere hvilke elementer der har ændret sig.

### Test din App
1. Kør din app med kommandoen `npm start` og test funktionaliteten i din browser.
2. Sørg for at din app fungerer som forventet og ligner den oprindelige HTML-version.

## Aflevering
Aflever din færdige React app som et GitHub repository. Inkluder en `README.md` fil med instruktioner om, hvordan man kører din app og en beskrivelse af den funktionalitet, din app tilbyder.

## Bedømmelseskriterier
- Korrekt implementering af React komponenter og state.
- Korrekt implementering af event handlers til at håndtere brugerinteraktioner.
- Korrekt brug af Bootstrap til at style din app.
- Din app skal fungere korrekt og uden fejl.

## Bonus
Tilføj yderligere funktionaliteter eller forbedringer til din app, såsom muligheden for at redigere todos, en "markér alle som fuldført" knap, eller en måde at filtrere og vise kun fuldførte eller ufuldførte todos.
