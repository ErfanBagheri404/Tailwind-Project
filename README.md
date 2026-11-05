# Prime Properties - Tailwind landing page

Static real-estate landing page for a fictional agency, styled entirely with
Tailwind CSS utility classes. Layout practice, no framework and no JS behaviour.

## Run

```bash
git clone https://github.com/ErfanBagheri404/Tailwind-Project.git
cd Tailwind-Project
```

```bash
npm install
npm run build      # tailwindcss -i ./src/style.css -o ./public/style.css
```

Then open `public/index.html`. Use `npx tailwindcss -i ./src/style.css -o ./public/style.css --watch`
while editing.

## Structure

| path | role |
|---|---|
| `public/index.html` | the page, all utilities inline in class attributes |
| `public/real_estate/` | hero, city and agent imagery |
| `src/style.css` | the three `@tailwind` directives only |
| `tailwind.config.js` | content globs and theme extensions |

Sections: sticky navbar, hero, "why us", featured properties, agents, contact
strip, footer.
