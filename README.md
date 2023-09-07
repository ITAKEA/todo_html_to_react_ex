
## Øvelse: Omdan en HTML Todo Liste til en React App

### Mål:
I denne øvelse skal du omdanne en eksisterende HTML Todo Liste til en React App. Dette indebærer arbejde med Components, state, Events og Form elementer.

### Forudsætninger:
- Grundlæggende kendskab til HTML, CSS og JavaScript.
- Grundlæggende forståelse af React og JSX.

### Materialer:
- Startkode: En simpel Todo Liste skrevet i HTML, CSS (Bootstrap) og JavaScript. (Du kan bruge den HTML kode, jeg oprindeligt leverede).
- Node.js og npm installeret på din computer.
- En kode editor (f.eks. Visual Studio Code).

### Instruktioner:

1. **Oprettelse af en ny React App**
   - Brug Create React App til at oprette en ny React app med kommandoen `npx create-react-app react-todo-list`.
   - Gå ind i din nye app-mappe med kommandoen `cd react-todo-list`.

2. **Installation af Bootstrap**
   - Installer Bootstrap i din React app med kommandoen `npm install bootstrap`.
   - Inkluder Bootstrap i din app ved at tilføje følgende linje i `src/index.css`: `@import '~bootstrap/dist/css/bootstrap.min.css';`.

3. **Oprettelse af TodoList Komponent**
   - Opret en ny fil `TodoList.js` i `src` mappen.
   - I `TodoList.js`, opret en funktionel komponent `TodoList` der returnerer en JSX repræsentation af den oprindelige HTML-struktur (du kan tage udgangspunkt i den HTML-struktur, der blev leveret i startkoden).

4. **Tilføjelse af State og Funktioner**
   - Brug `useState` hook til at oprette state variabler for din todo liste og input-feltet.
   - Implementer funktionerne `addTodo`, `toggleDone` og `removeTodo` for at håndtere henholdsvis tilføjelse af nye todos, markering af todos som fuldført, og fjernelse af todos.

5. **Rendering af Todo Liste**
   - Brug `map` funktionen til at gennemgå alle todos og vise dem i en liste med en checkbox og en "fjern" knap for hver todo.
   - Tilføj en `key` prop til hvert element i listen for at hjælpe React med at identificere hvilke elementer der har ændret sig.

6. **Test din App**
   - Kør din app med kommandoen `npm start` og test funktionaliteten i din browser.
   - Sørg for at din app fungerer som forventet og ligner den oprindelige HTML-version.

### Aflevering:
- Aflever din færdige React app som et GitHub repository.
- Inkluder en `README.md` fil med instruktioner om, hvordan man kører din app og en beskrivelse af den funktionalitet, din app tilbyder.

### Bedømmelseskriterier:
- Korrekt implementering af React komponenter og state.
- Korrekt implementering af event handlers til at håndtere brugerinteraktioner.
- Korrekt brug af Bootstrap til at style din app.
- Din app skal fungere korrekt og uden fejl.

### Bonus:
- Tilføj yderligere funktionaliteter eller forbedringer til din app, såsom muligheden for at redigere todos, en "markér alle som fuldført" knap, eller en måde at filtrere og vise kun fuldførte eller ufuldførte todos.
